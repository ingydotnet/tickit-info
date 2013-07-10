# Current Tickit Widgets

This document has pictures and thoughts of all the current Tickit.pm
widgets.

| Name                           | Source         | Style | RCtx | Container | Notes | Exp |
|--------------------------------|----------------|-------|------|-----------|-------|-----|
| Tickit::Widget::Border         | Tickit-Widgets | 0.32  | 0.33 | Cont 1    |       | C   |
| Tickit::Widget::Box            | Tickit         | 0.32  | 0.33 | Cont 1    |       | C   |
| Tickit::Widget::Button         | Tickit-Widgets | 0.32  | 0.33 |           |       | C   |
| Tickit::Widget::CheckButton    | Tickit-Widgets | 0.32  | 0.33 |           |       | C   |
| Tickit::Widget::Entry          | Tickit-Widgets | 0.32  |      |           |       | C   |
| Tickit::Widget::Frame          | Tickit-Widgets | 0.32  |      | Cont 1    |       | C   |
| Tickit::Widget::GridBox        | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | C   |
| Tickit::Widget::HBox           | Tickit         | 0.32  | 0.33 | Cont      |       | C   |
| Tickit::Widget::HSplit         | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | C   |
| Tickit::Widget::Menu           | self           | 0.32  | 0.07 |           |       | C   |
| Tickit::Widget::Placegrid      | Tickit-Widgets | 0.32  | 0.33 |           |       | C   |
| Tickit::Widget::Progressbar    | self           |       |      |           |       |     |
| Tickit::Widget::RadioButton    | Tickit-Widgets | 0.32  | 0.33 |           |       | C   |
| Tickit::Widget::Scroller       | self           | 0.32  | 0.07 |           |       | C   |
| Tickit::Widget::SegmentDisplay | self           | 0.32  | 0.07 |           |       | C   |
| Tickit::Widget::SparkLine      | self           |       |      |           |       |     |
| Tickit::Widget::Static         | Tickit         | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::Tabbed         | self           |       |      | (no)      |       | C   |
| Tickit::Widget::Table          | self           |       |      |           |       |     |
| Tickit::Widget::Tree           | self           |       |      |           |       | C   |
| Tickit::Widget::VBox           | Tickit         | 0.32  | 0.33 | Cont      |       | C   |
| Tickit::Widget::VSplit         | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | C   |

RCtx == 0.33: using Tickit's RenderBuffer

Exp == Experiments:
  C: CLEAR_BEFORE_RENDER => 0
  R: render_to_rb

Tickit.pm seems to be the best candidate for the future of
interactive terminal apps, but currently lacks the basic widgets to
build serious apps.

