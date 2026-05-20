# patchwerk-wasm YouTube channel assets

YouTube channel art for the PatchWerk WASM project.

## Files

| File | Purpose |
|---|---|
| `avatar.png` / `avatar.svg` | Channel avatar (square) |
| `banner.png` / `banner.svg` | Channel banner (16:9, YouTube spec) |
| `watermark.png` | Subscribe-bug watermark overlay |

## Raw URLs

Use these for embedding in markdown or video descriptions:

- `https://raw.githubusercontent.com/draakaap/gumroad-product-images/main/patchwerk-wasm/youtube/avatar.png`
- `https://raw.githubusercontent.com/draakaap/gumroad-product-images/main/patchwerk-wasm/youtube/banner.png`
- `https://raw.githubusercontent.com/draakaap/gumroad-product-images/main/patchwerk-wasm/youtube/watermark.png`

## Source repo

These were originally tracked at `marketing/youtube/` inside
`github.com/draakaap/patchwerk-wasm`. Moved here 2026-05-20 to keep
the source repo lean and follow the standing rule: media artifacts
live in the public image-host repo, not in source.

## Regenerating

The SVG files are the editable source for the PNG raster outputs.
Edit the SVG in any vector editor, then export PNG at the target
size (banner: 2560×1440 with 1546×423 safe area, avatar: 800×800,
watermark: 150×150).
