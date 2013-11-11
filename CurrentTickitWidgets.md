# Current Tickit Widgets

This document has pictures and thoughts of all the current Tickit.pm
widgets.

| Name                             | Source         | Style | RB   | Container | Notes | Exp |
|----------------------------------|----------------|-------|------|-----------|-------|-----|
| Tickit::Widget::Border           | Tickit-Widgets | 0.32  | 0.33 | Cont 1    |       | RS  |
| Tickit::Widget::Box              | Tickit         | 0.32  | 0.33 | Cont 1    |       | RS  |
| Tickit::Widget::Button           | Tickit-Widgets | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::CheckButton      | Tickit-Widgets | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Decoration       | self           | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Entry            | Tickit-Widgets | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Frame            | Tickit-Widgets | 0.32  | 0.33 | Cont 1    |       | RS  |
| Tickit::Widget::GridBox          | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | RS  |
| Tickit::Widget::HBox             | Tickit         | 0.32  | 0.33 | Cont      |       | RS  |
| Tickit::Widget::HSplit           | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | RS  |
| Tickit::Widget::Layout::Relative | self           | 0.32  | 0.33 | Cont      |       | R   |
| Tickit::Widget::Menu             | self           | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Placegrid        | Tickit-Widgets | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Progressbar      | self           | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::RadioButton      | Tickit-Widgets | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Scroller         | self           | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::ScrollBox        | self           | 0.32  | 0.33 | Cont 1    |       | R   |
| Tickit::Widget::SegmentDisplay   | self           | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::SparkLine        | self           | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Spinner          | Tickit-Widgets | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Static           | Tickit         | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Statusbar        | self           | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::Tabbed           | self           | 0.32  | 0.33 | (no)      |       | R   |
| Tickit::Widget::Table            | self           | 0.32  | 0.32 | Cont      |       | R   |
| Tickit::Widget::Table::Paged     | self           | 0.32  | 0.32 | Cont      |       | R   |
| Tickit::Widget::Tree             | self           | 0.32  | 0.33 |           |       | R   |
| Tickit::Widget::VBox             | Tickit         | 0.32  | 0.33 | Cont      |       | RS  |
| Tickit::Widget::VSplit           | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | RS  |

Exp == Experiments:
  R: render_to_rb
  S: container using ->requested_* for sizing

Tickit.pm seems to be the best candidate for the future of
interactive terminal apps, but currently lacks the basic widgets to
build serious apps.

