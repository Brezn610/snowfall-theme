# Third-party notices

## theme-examples (snow-pines scene)

`hooks/scene.js` contains portions adapted from `plugins/theme-examples/hooks/scenes/snow-pines.ts` in
[anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/theme-examples),
licensed under the Apache License, Version 2.0. The full license text is in `licenses/Apache-2.0.txt`.

What was taken, and what was changed:

- The `hash()` function is copied unchanged.
- The approach to the forest is adapted: trees at three depths, the side facing the light drawn lighter than
  the side in shadow, snow resting on the exposed boughs, and each tier darkened where the tier above overhangs it.
  In snow-pines these are built from character cells; here they are redrawn as vector shapes, with new geometry,
  colours and code.

Everything else in this mod (the cabin, the mountains, the ground, the badge and the snowfall) is original to it.
