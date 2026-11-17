# assets

Static assets shared across OpenWeir: the apps, websites and documentation take files from here instead of keeping their own copies.

| File | What it is |
| --- | --- |
| `openweir.svg` | The OpenWeir mark, 100×100, no fill set (renders black; set `fill` or use `fill="currentColor"` inline to colour it). |

Brand colours and the rest of the design system live in the `design` repo.

## Adding an asset

- Keep sources as vector (SVG) where possible; add raster exports only when a consumer needs them.
- Name files in lowercase with hyphens, and list each one in the table above.
