# Tickit Deprecations

This table lists the legacy features of Tickit that are scheduled for deprecation and eventual removal.

'announce' gives the version at which the deprecation was announced, 'warn' when it first creates a warning, 'die' when use of the feature will immediately fail, and 'remove' when all trace of the feature will be removed.

The exact schedule of each feature's progress will be decided on a per-case basis, considering the length of time the feature has been in existence, how widely used it currently is, and how easily it can be replaced.

Future versions given in this table are lower limits; if Tickit versions are released more often than anticipated, these limits may be extended.

| Name                                        | Announce | Warn   | Die    | Remove |
|---------------------------------------------|----------|--------|--------|--------|
| Old-style $win->set_on_EVENT                | 0.57     |  0.59  | *0.61* | *0.63* |
| Hash key access of Tickit::Term event info  | 0.58     |  0.60  | *0.62* | *0.64* |
| $term->bind_event_with_flags                | ---      |  0.59  | *0.61* | *0.63* |
| $term->bind_event_default                   | ---      |  0.60  | *0.62* | *0.64* |
| $win->term yielding the same object value   |  0.60    | ---    | ---    | *0.62* |
| Non-newapi $info->type yielding boolean     |  0.60    | *0.62* | ---    | *0.66* |
