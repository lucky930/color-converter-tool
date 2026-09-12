# Color Converter

A standalone, responsive color converter website.

## Supported input formats

- Visual color picker: hue, saturation/value, and alpha.
- RGBA: R, G, B and A values from 0–255.
- HEX:
  - `#RRGGBB` for opaque colors.
  - `#RRGGBBAA` for colors with alpha.
- ARGB: `#AARRGGBB`.
- Integer: signed 32-bit ARGB integer, matching the common Android/Java representation.

## Examples

- White: RGBA `255,255,255,255`
- HEX: `#FFFFFF`
- ARGB: `#FFFFFFFF`
- Integer: `-1`

## Behavior

- Changes are applied as the user types.
- Invalid HEX/ARGB/integer values do not replace the last valid color.
- Invalid RGBA components do not replace the last valid color.
- All formats update immediately after a valid change.
- Each HEX, ARGB and Integer field has a Copy button.
- No external libraries or network connection are required.

## Run

Simply open `index.html` in any modern browser or go to https://color-converter-tool.web.app/.
