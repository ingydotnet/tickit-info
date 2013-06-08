# Current Tickit Widgets

This document has pictures and thoughts of all the current Tickit.pm
widgets.

| Name                           | Source         | Style | RCtx | Container | Notes |
|--------------------------------|----------------|-------|------|-----------|-------|
| Tickit::Widget::Border         | Tickit-Widgets | 0.32  | 0.33 | Cont 1    |       |
| Tickit::Widget::Box            | Tickit         | 0.32  | 0.33 | Cont 1    |       |
| Tickit::Widget::Button         | Tickit-Widgets | 0.32  | 0.33 |           |       |
| Tickit::Widget::CheckButton    | Tickit-Widgets | 0.32  | 0.33 |           | Test-case for Tickit::Style |
| Tickit::Widget::Entry          | Tickit-Widgets | 0.32  |      |           |       |
| Tickit::Widget::Frame          | Tickit-Widgets | 0.32  |      | Cont 1    |       |
| Tickit::Widget::GridBox        | Tickit-Widgets | 0.32  | 0.33 | Cont      |       |
| Tickit::Widget::HBox           | Tickit         | 0.32  | 0.33 | Cont      |       |
| Tickit::Widget::HSplit         | Tickit-Widgets | 0.32  | 0.33 | Cont      |       |
| Tickit::Widget::Menu           | self           | 0.32  | 0.07 |           | Test-case for Tickit::RenderContext |
| Tickit::Widget::Placegrid      | Tickit-Widgets | 0.32  | 0.33 |           |       |
| Tickit::Widget::Progressbar    | self           |       |      |           |       |
| Tickit::Widget::RadioButton    | Tickit-Widgets | 0.32  | 0.33 |           | Test-case for Tickit::Style |
| Tickit::Widget::Scroller       | self           | 0.32  | 0.07 |           | Test-case for Tickit::RenderContext |
| Tickit::Widget::SegmentDisplay | self           | 0.32  | 0.07 |           |       |
| Tickit::Widget::SparkLine      | self           |       |      |           |       |
| Tickit::Widget::Static         | Tickit         | 0.32  | 0.33 |           |       |
| Tickit::Widget::Tabbed         | self           |       |      | (no)      |       |
| Tickit::Widget::Table          | self           |       |      |           |       |
| Tickit::Widget::Tree           | self           |       |      |           |       |
| Tickit::Widget::VBox           | Tickit         | 0.32  | 0.33 | Cont      |       |
| Tickit::Widget::VSplit         | Tickit-Widgets | 0.32  | 0.33 | Cont      |       |

RCtx == 0.33: using Tickit's RenderBuffer

Tickit.pm seems to be the best candidate for the future of
interactive terminal apps, but currently lacks the basic widgets to
build serious apps.

