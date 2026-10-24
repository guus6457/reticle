### Fixed

- **`@reticlehq/browser` — synthetic taps sent pointer events at (0, 0).** Tap pointer events now carry the target element's centre. Canvas hit tests can use the same coordinates as the touch events. Closes [#1851](https://github.com/reticlehq/reticle/issues/1851).
