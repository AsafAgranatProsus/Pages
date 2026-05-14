# hello-nanobot

**Purpose**: Test deployment — interactive WebGL background that responds to cursor movement.

**Status**: Active prototype

**Tech**: Single-file HTML + WebGL fragment shader (fractal metaball pattern with randomized seed per page load)

**URL**: https://asafagranatprosus.github.io/pages/apps/hello-nanobot/

## Features

- WebGL fluid background (performant, single-pass shader)
- Cursor-reactive distortion
- Randomized color palette + animation speed on each refresh
- Timestamp display + color-cycling button (original test elements)

## Open threads

- None — shipped as intended

## Notes

- No build step, no dependencies
- Pattern randomization via `Math.random()` seed fed to shader uniforms
- Smooth mouse interpolation for fluid response
