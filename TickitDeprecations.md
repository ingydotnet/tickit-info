# Tickit Deprecations

This table lists the legacy features of Tickit that are scheduled for deprecation and eventual removal.

'announce' gives the version at which the deprecation was announced, 'warn' when it first creates a warning, 'die' when use of the feature will immediately fail, and 'remove' when all trace of the feature will be removed.

The exact schedule of each feature's progress will be decided on a per-case basis, considering the length of time the feature has been in existence, how widely used it currently is, and how easily it can be replaced.

Future versions given in this table are lower limits; if Tickit versions are released more often than anticipated, these limits may be extended.

| Name                             | Announce | Warn   | Die    | Remove |
|----------------------------------|----------|--------|--------|--------|
| Disabling WIDGET_PEN_FROM_STYLE  |  0.47    |  0.49  |  0.51  | *0.53* |
| Pen observers                    |  0.49    |  0.51  | *0.55* | *0.57* |
| Disabling window expose_after_scroll | 0.39 |  0.52  | *0.54* | *0.56* |
| Mutable Widget pens              |  0.51    | *0.53* | *0.55* | *0.57* |
