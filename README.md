# RC Logo Studio

Slider-driven generator for the Brophy RC club mark: an R + C monogram with a prop in the R,
a tire-tread C with a joystick, and a chapel-steeple antenna.

Live: https://elmagoct.github.io/brophy-rc-logo-studio/

- Plain HTML/JS, no build step. Open `index.html` or serve the folder.
- The mark is built as polygons and merged with [Clipper](http://www.angusj.com/clipper2/)
  (`vendor/clipper.js`, Boost Software License), so every corner can be filleted and
  exports are a single outlined path.
- **Copy link to this design** saves every slider in the URL, so a design can be shared.
- `?sheet` shows all presets side by side.
