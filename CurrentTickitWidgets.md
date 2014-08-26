# Current Tickit Widgets

This table lists the current Tickit::Widget subclasses, their source, the latest Tickit
version they are tested with and known to work against, and some internal notes detailing
levels of API conformence or current code experiments ongoing.

| Name                             | Source         | Tested | Container | Notes | Exp |
|----------------------------------|----------------|--------|-----------|-------|-----|
| Tickit::Widget::Border           | Tickit-Widgets | 0.44   | Cont 1    |       | SP  |
| Tickit::Widget::Box              | Tickit         | 0.44   | Cont 1    |       | SP  |
| Tickit::Widget::Breadcrumb       | self           | 0.44   |           |       |     |
| Tickit::Widget::Button           | Tickit-Widgets | 0.44   |           |       |  P  |
| Tickit::Widget::CheckButton      | Tickit-Widgets | 0.44   |           |       |  P  |
| Tickit::Widget::Decoration       | self           | 0.44   |           |       |     |
| Tickit::Widget::Entry            | Tickit-Widgets | 0.44   |           |       |  P  |
| Tickit::Widget::FloatBox         | self           | 0.44   | Cont      |       | SP  |
| Tickit::Widget::FileViewer       | self           | 0.44   |           |       |  P  |
| Tickit::Widget::Fill             | Tickit-Widgets | 0.44   |           |       |  P  |
| Tickit::Widget::Frame            | Tickit-Widgets | 0.44   | Cont 1    |       | SP  |
| Tickit::Widget::GridBox          | Tickit-Widgets | 0.44   | Cont      |       | SP  |
| Tickit::Widget::HBox             | Tickit-Widgets | 0.44   | Cont      |       | SP  |
| Tickit::Widget::HSplit           | Tickit-Widgets | 0.44   | Cont      |       | SP  |
| Tickit::Widget::Layout::Desktop  | self           | 0.44   |           | [3]   |  P  |
| Tickit::Widget::Layout::Relative | self           | 0.44   | Cont      | [1]   |  P  |
| Tickit::Widget::Menu             | self           | 0.44   |           |       |  P  |
| Tickit::Widget::Placegrid        | Tickit-Widgets | 0.44   |           |       |  P  |
| Tickit::Widget::Progressbar      | self           | 0.44   |           |       |     |
| Tickit::Widget::RadioButton      | Tickit-Widgets | 0.44   |           |       |  P  |
| Tickit::Widget::Scroller         | self           | 0.44   |           |       |  P  |
| Tickit::Widget::ScrollBox        | self           | 0.44   | Cont 1    |       |  P  |
| Tickit::Widget::SegmentDisplay   | self           | 0.44   |           |       |  P  |
| Tickit::Widget::SparkLine        | self           | 0.44   |           |       |     |
| Tickit::Widget::Spinner          | Tickit-Widgets | 0.44   |           |       |  P  |
| Tickit::Widget::Static           | Tickit         | 0.44   |           |       |  P  |
| Tickit::Widget::Statusbar        | self           | 0.44   |           |       |  P  |
| Tickit::Widget::Tabbed           | self           | 0.44   | Cont      |       |  P  |
| Tickit::Widget::Table            | self           | 0.44   |           |       |  P  |
| Tickit::Widget::Table::Paged     | self           | 0.44   | Cont      |       |  P  |
| Tickit::Widget::Tree             | self           | 0.44   |           | [2]   |  P  |
| Tickit::Widget::VBox             | Tickit-Widgets | 0.44   | Cont      |       | SP  |
| Tickit::Widget::VSplit           | Tickit-Widgets | 0.44   | Cont      |       | SP  |

Exp == Experiments:

  S: container using ->requested_* for sizing

  P: Widget default pen is from style

Notes:

 [1]: Tickit::Widget::Layout::Relative subclasses Tickit::Window to provide an 'on_expose'
      callback

 [2]: Tickit::Widget::Tree imports Term::TermKey just so it can get KEYMOD_CTRL

 [3]: Tickit::Widget::Layout::Desktop isn\'t a direct container subwidget, but the ::Window
      items are. May eventually use FloatBox (there are some minor complications around
	  window tracking logic and rendering)

