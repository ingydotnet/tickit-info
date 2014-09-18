# Tickit Deprecations

This table lists the legacy features of Tickit that are scheduled for deprecation and eventual removal.

'announce' gives the version at which the deprecation was announced, 'warn' when it first creates a warning, 'die' when use of the feature will immediately fail, and 'remove' when all trace of the feature will be removed.

The exact schedule of each feature's progress will be decided on a per-case basis, considering the length of time the feature has been in existence, how widely used it currently is, and how easily it can be replaced.

Future versions given in this table are lower limits; if Tickit versions are released more often than anticipated, these limits may be extended.

| Name                             | Announce | Warn   | Die    | Remove |
|----------------------------------|----------|--------|--------|--------|
| $win->getpenattrs                |  0.16    |  0.45  |  0.46  |  0.48  |
| $win->get_effective_penattrs     |  0.16    |  0.45  |  0.46  |  0.48  |
| $term->mode_...                  |  0.26    |  0.45  |  0.46  |  0.48  |
| $win->set_on_key without ev      |  0.42    |  0.44  |  0.46  |  0.48  |
| $win->set_on_mouse without ev    |  0.42    |  0.44  |  0.46  |  0.48  |
| $win->set_on_expose without rb   |  0.42    |  0.44  |  0.46  |  0.48  |
| "$ev" type overloading           |  0.44    |  0.44  |  0.46  |  0.48  |
| Disabling CHILD_WINDOWS_LATER    |  0.45    |  0.47  | *0.49* | *0.51* |
| $rb->flush_to_window             |  0.45    |  0.48  | *0.50* | *0.52* |
| $win->print, ->erasech, ->goto   |  0.45    |  0.48  | *0.50* | *0.52* |
| Disabling WIDGET_PEN_FROM_STYLE  |  0.47    | *0.49* | *0.51* | *0.53* |
