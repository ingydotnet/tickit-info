# A Layout Use Case

I would like to make apps with a user interface like this:

    .-------------------------------------------------------------------------.
    |                                  App Title                   (TitleBar) |
    | [File]  [Help]                                               (MenuBar)  |
    .------------------.------------------------------------------------------.
    |                  |  .-------. .-------. .-------.                       |
    | » Foo            |  | Good  | |  Bad  | | Ugly  |                       |
    |  .-----------.   |--'-------'-'-------'-'       '-----------------------|
    |  | Foodstuff |   |                                                      |
    |  | Foozball  |   |                                                      |
    |  '-----------'   |                                                      |
    | » Bar            |                                                      |
    | » Baz            |                                                      |
    |                  |                                                      |
    |                  |                                                      |
    |                  |                                                      |
    |    (SideBar)     |            (TabSet)                                  |
    '------------------'------------------------------------------------------'
    |                                (ContextBar)                             |
    |                                (StatusBar)                              |
    '-------------------------------------------------------------------------'

I would expect the code to look something like this:

    my $screen = Tickit::Widget::Screen->new;
    my $header = Tickit::Widget::Header->new;
    my $title = Tickit::Widget::MenuBar->new(
        text => 'App Title',
    );
    my $menu = Tickit::Widget::MenuBar->new(
        layout => [
            File => ['Save', 'Quit'],
            Help => ['Documentation', 'About']
        ]
    );
    my $side = Tickit::Widget::Sidebar->new;
    my $foo = Tickit::Widget::ExpandableMenuItem->new(
        layout => ['Foo', 'Foodstuff', 'Foozball'],
    );
    my $content = Tickit::Widget::TabSet;
    $content->add_tab(
        label => 'Good',
        content => Tickit::Widget::SomethingGood,
    );
    $screen->add($header, $footer, $side, $content);
    $header->add($title, $menu);
    $footer->add($context, $status);

    Ticket->new(
        root => $screen,
    )->run;

Note that I haven't said a single thing about layout (although the order of the
`->add()` arguments is important) and everything just works.

This is because:

* Tickit::Widget::MenuBar knows it has a height of 1 and a width or 100% (by default).
* Same with Tickit::Widget::TitleBar.
* Tickit::Widget::Header shrinks to the absolute values its children and positions itself at the top of its parent.
* Tickit::Widget::Footer is the same but positions itself at the bottom.
* Ticket::Widget asks to be at least as wide as it's children, preferably between 15% and 25% of its parent's remaining room.
* Ticket::Wigdet::Tabset expands to 100% of the remaining parent room.

I think we might need to add a few more types of boxes for things to inherit
from, like Tickit::Widget::Box::Shrink and Tickit::Widget::Box::Expand.
