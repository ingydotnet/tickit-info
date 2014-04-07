# Current Tickit Widgets

This table lists the current Tickit::Widget subclasses, their source, the latest Tickit
version they are tested with and known to work against, and some internal notes detailing
levels of API conformence or current code experiments ongoing.

| Name                             | Source         | Tested | Win  | Container | Notes | Exp |
|----------------------------------|----------------|--------|------|-----------|-------|-----|
| Tickit::Widget::Border           | Tickit-Widgets | 0.43   | 0.42 | Cont 1    |       | S   |
| Tickit::Widget::Box              | Tickit         | 0.43   | 0.42 | Cont 1    |       | S   |
| Tickit::Widget::Button           | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::CheckButton      | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Decoration       | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Entry            | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Frame            | Tickit-Widgets | 0.43   | 0.42 | Cont 1    |       | S   |
| Tickit::Widget::GridBox          | Tickit-Widgets | 0.43   | 0.42 | Cont      |       | S   |
| Tickit::Widget::HBox             | Tickit         | 0.43   | 0.42 | Cont      |       | S   |
| Tickit::Widget::HSplit           | Tickit-Widgets | 0.43   | 0.42 | Cont      |       | S   |
| Tickit::Widget::Layout::Relative | self           | 0.43   | 0.42 | Cont      | [1,2] |     |
| Tickit::Widget::Menu             | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Placegrid        | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Progressbar      | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::RadioButton      | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Scroller         | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::ScrollBox        | self           | 0.43   | 0.42 | Cont 1    |       |     |
| Tickit::Widget::SegmentDisplay   | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::SparkLine        | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Spinner          | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Static           | Tickit         | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Statusbar        | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Tabbed           | self           | 0.43   | 0.42 | (no)      |       |     |
| Tickit::Widget::Table            | self           | XXX    |      | Cont      |       |     |
| Tickit::Widget::Table::Paged     | self           | 0.43   | 0.42 | Cont      |       |     |
| Tickit::Widget::Tree             | self           | 0.43   | 0.42 |           | [3]   |     |
| Tickit::Widget::VBox             | Tickit         | 0.43   | 0.42 | Cont      |       | S   |
| Tickit::Widget::VSplit           | Tickit-Widgets | 0.43   | 0.42 | Cont      |       | S   |

Exp == Experiments:
  S: container using ->requested_* for sizing

Notes:

 [1]: Tickit::Widget::Layout::Relative gut-wrenches inside Tickit::RenderBuffer to obtain cell
      state in order to set rounded corners.

 [2]: Tickit::Widget::Layout::Relative subclasses Tickit::Window to provide an 'on_expose'
      callback

 [3]: Tickit::Widget::Tree imports Term::TermKey just so it can get KEYMOD_CTRL
