# Widget Comparison

This document indicates (near) equivalents between UI widgets in Tickit and other widget-based UI systems

| Tickit::Widget::* | Curses::Toolkit::* | GTK 3                 |
|-------------------|--------------------|-----------------------|
| Border            | -                  | GtkAlignment          |
| Box               | -                  | (GtkAlignment)        |
| Button            | Button             | GtkButton             |
| CheckButton       | -                  | GtkCheckButton        |
| Decoration        | -                  | -                     |
| Entry             | Entry              | GtkEntry              |
| Frame             | Border             | GtkFrame              |
| GridBox           | -                  | GtkGrid               |
| HBox              | HBox               | GtkBox                |
| HSplit            | HPaned             | GtkPaned              |
| Layout::Relative  | -                  | -                     |
| Menu              | -                  | GtkMenu               |
| Placegrid         | -                  | -                     |
| Progressbar       | {H,V}ProgressBar   | GtkProgressBar        |
| RadioButton       | -                  | GtkRadioButton        |
| Scroller          | -                  | GtkTextView [*]       |
| ScrollBox         | ScrollArea         | GtkScrolledWindow     |
| SegmentDisplay    | -                  | -                     |
| SparkLine         | -                  | -                     |
| Spinner           | -                  | GtkSpinner / GtkImage |
| Static            | Label              | GtkLabel              |
| Statusbar         | -                  | GtkStatusbar          |
| Tabbed            | -                  | GtkNotebook           |
| Table             | -                  | GtkTreeView [*]       |
| Table::Paged      | -                  | GtkTreeView [*]       |
| Tree              | -                  | GtkTreeView           |
| VBox              | VBox               | GtkBox                |
| VSplit            | VPaned             | GtkPaned              |

*:

|       | notes                                      |
|-------|--------------------------------------------|
| GTK 3 | Scroller = GtkTextView + GtkScrolledWindow |
| "     | Table = GtkTreeView + GtkTableStore        |

URLs:

| Toolkit         | URL                                         |
|-----------------|---------------------------------------------|
| Curses::Toolkit | https://metacpan.org/release/Curses-Toolkit |
| GTK 3           | https://developer.gnome.org/gtk3/stable/    |
