# Current Tickit Widgets

This document has pictures and thoughts of all the current Tickit.pm
widgets.

| Name                           | Source         | Style | RB   | Container | Notes | Exp |
|--------------------------------|----------------|-------|------|-----------|-------|-----|
| Tickit::Widget::Border         | Tickit-Widgets | 0.32  | 0.33 | Cont 1    |       | cR  |
| Tickit::Widget::Box            | Tickit         | 0.32  | 0.33 | Cont 1    |       | cR  |
| Tickit::Widget::Button         | Tickit-Widgets | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::CheckButton    | Tickit-Widgets | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::Entry          | Tickit-Widgets | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::Frame          | Tickit-Widgets | 0.32  | 0.33 | Cont 1    |       | cR  |
| Tickit::Widget::GridBox        | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | cR  |
| Tickit::Widget::HBox           | Tickit         | 0.32  | 0.33 | Cont      |       | cR  |
| Tickit::Widget::HSplit         | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | cR  |
| Tickit::Widget::Menu           | self           | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::Placegrid      | Tickit-Widgets | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::Progressbar    | self           |       |      |           |       |     |
| Tickit::Widget::RadioButton    | Tickit-Widgets | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::Scroller       | self           | 0.32  | 0.07 |           | Still using RenderContext | C   |
| Tickit::Widget::ScrollBox      | self           | 0.32  | 0.33 | Cont 1    |       | cR  |
| Tickit::Widget::SegmentDisplay | self           | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::SparkLine      | self           |       |      |           |       |     |
| Tickit::Widget::Static         | Tickit         | 0.32  | 0.33 |           |       | cR  |
| Tickit::Widget::Tabbed         | self           | 0.32  | 0.33 | (no)      |       | cR  |
| Tickit::Widget::Table          | self           | 0.32  | 0.32 | Cont      |       | cR  |
| Tickit::Widget::Tree           | self           |       |      |           |       | C   |
| Tickit::Widget::VBox           | Tickit         | 0.32  | 0.33 | Cont      |       | cR  |
| Tickit::Widget::VSplit         | Tickit-Widgets | 0.32  | 0.33 | Cont      |       | cR  |

Exp == Experiments:
  C: CLEAR_BEFORE_RENDER => 0
  R: render_to_rb

Tickit.pm seems to be the best candidate for the future of
interactive terminal apps, but currently lacks the basic widgets to
build serious apps.

