# Current Tickit Widgets

This document has pictures and thoughts of all the current Tickit.pm
widgets.

| Name                             | Source         | Tested | Win  | Container | Notes | Exp |
|----------------------------------|----------------|--------|------|-----------|-------|-----|
| Tickit::Widget::Border           | Tickit-Widgets | 0.43   | 0.42 | Cont 1    |       | S   |
| Tickit::Widget::Box              | Tickit         | 0.43   | 0.42 | Cont 1    |       | S   |
| Tickit::Widget::Button           | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::CheckButton      | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Decoration       | self           |        |      |           |       |     |
| Tickit::Widget::Entry            | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Frame            | Tickit-Widgets | 0.43   | 0.42 | Cont 1    |       | S   |
| Tickit::Widget::GridBox          | Tickit-Widgets | 0.43   | 0.42 | Cont      |       | S   |
| Tickit::Widget::HBox             | Tickit         | 0.43   | 0.42 | Cont      |       | S   |
| Tickit::Widget::HSplit           | Tickit-Widgets | 0.43   | 0.42 | Cont      |       | S   |
| Tickit::Widget::Layout::Relative | self           | 0.43   |      | Cont      |       |     |
| Tickit::Widget::Menu             | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Placegrid        | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Progressbar      | self           |        |      |           |       |     |
| Tickit::Widget::RadioButton      | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Scroller         | self           | 0.43   |      |           |       |     |
| Tickit::Widget::ScrollBox        | self           | 0.43   | 0.42 | Cont 1    |       |     |
| Tickit::Widget::SegmentDisplay   | self           | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::SparkLine        | self           |        |      |           |       |     |
| Tickit::Widget::Spinner          | Tickit-Widgets | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Static           | Tickit         | 0.43   | 0.42 |           |       |     |
| Tickit::Widget::Statusbar        | self           |        |      |           |       |     |
| Tickit::Widget::Tabbed           | self           | 0.43   |      | (no)      |       |     |
| Tickit::Widget::Table            | self           |        |      | Cont      |       |     |
| Tickit::Widget::Table::Paged     | self           |        |      | Cont      |       |     |
| Tickit::Widget::Tree             | self           |        |      |           |       |     |
| Tickit::Widget::VBox             | Tickit         | 0.43   | 0.42 | Cont      |       | S   |
| Tickit::Widget::VSplit           | Tickit-Widgets | 0.43   | 0.42 | Cont      |       | S   |

Exp == Experiments:
  S: container using ->requested_* for sizing

Tickit.pm seems to be the best candidate for the future of
interactive terminal apps, but currently lacks the basic widgets to
build serious apps.

