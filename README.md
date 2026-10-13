<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="lockup/open-pencil-horizontal-colour-on-dark.svg">
    <img src="lockup/open-pencil-horizontal-colour.svg" alt="OpenPencil" width="480">
  </picture>
</p>

> **Status: proposal.** This logo kit is proposed for [OpenPencil](https://github.com/open-pencil/open-pencil) by [@rcoenen](https://github.com/rcoenen). It is not the project's adopted brand; OpenPencil's current logo lives in its repository under `assets/brand/`.

# OpenPencil logo kit (v5)

## The mark
A P built from three primitives on a 2 x 3 grid of equal square cells: a square stem, a half-disc bowl and a rounded-square foot. One colour per piece, flat, in the same modular language as Figma's tools. Rounded corners are half a cell. The counter is a circle of 0.4 cell with one sharp corner, centred on the seam between stem and bowl so it locks them together; its sharp corner points down-left toward the foot, the pencil.

## Colours
| Piece           | Name   | Hex     |
|-----------------|--------|---------|
| Stem            | Flame  | #F5501E |
| Bowl            | Sun    | #FFD43B |
| Foot (pencil)   | Dusk   | #9B5CFF |
| One-colour mark | Ink    | #111111 |

A sunset read top to bottom: flame stem, sun bowl, dusk foot. Flat colour only, no gradients.

## Backgrounds
- White, black and neutral greys (including dark UI grey #2C2C2C): use the colour mark directly.
- Coloured or busy backgrounds: use a tile (svg/open-pencil-icon-ink.svg or -white.svg), or the one-colour mark. Never place the bare colour mark on flame, sun or dusk.

## Wordmark
Outfit SemiBold (600), letter-spacing -2%. In the lockup files the wordmark is outlined to shapes, so no font is needed. Horizontal lockup: mark height 1.6 x cap height, gap half the mark width, mark centred on the cap height. Stacked lockup: mark centred above the wordmark.

## Which file to use
- **open-pencil-logo-guidelines.pdf**: ten-page visual overview of everything below.
- **lockup/open-pencil-horizontal-colour.svg**: default logo with wordmark; **-on-dark** for dark backgrounds; **-black / -white** one colour.
- **lockup/open-pencil-stacked-*.svg**: stacked lockup for square spaces.
- **lockup/open-pencil-wordmark-*.svg**: wordmark alone.
- **svg/open-pencil-mark-colour.svg**: the mark on its own.
- **svg/open-pencil-mark-black.svg / -white.svg**: one colour; best below 24 px and for single-ink print.
- **svg/open-pencil-mark-line-*.svg**: single outline (outer edge + counter).
- **svg/open-pencil-mark-line-colour.svg**: colour line, each piece stroked in its own colour.
- **svg/open-pencil-mark-exploded-*.svg**: the three pieces pulled apart, in colour, colour line, black or white line. Expressive use only, 64 px and up; never as app icon or favicon.
- **svg/open-pencil-mark-outline-*.svg**: modular outline showing the three pieces; 48 px and up only.
- **svg/open-pencil-icon-ink.svg**: default app icon tile; **-white.svg** alternative; **-square-ink.svg / -square.svg**: full bleed for iOS/Android.
- **ui-icon/open-pencil-ui-24.svg**: in-product icon on a 24 px grid, 1.5 px stroke, uses currentColor. Works at 24 and 16 px. **open-pencil-ui-modular-48plus.svg** for 48 px and up.
- **favicon/**: favicon.ico (16, 32, 48), favicon.svg, apple-touch-icon.png (180), icon-192.png, icon-512.png, all from the ink tile.

## Rules
- Clear space: at least half a cell (a quarter of the mark's width) on all sides.
- Minimum size: colour mark 24 px tall; one-colour mark and UI icon 16 px.
- Don't recolour or swap the pieces, add gradients, rotate the mark, or fill the counter.

## Favicon snippet
```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
```

## License

[MIT](LICENSE), the same license as OpenPencil.
