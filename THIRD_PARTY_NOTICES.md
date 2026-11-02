# Third-party notices

This repository is an unofficial Orca port maintained by [faisalmuhammad](https://github.com/faisalmuhammad). Attribution to upstream authors is retained separately from the port's maintenance credit.

## Monospace Theme

- **Author:** Keksi (keksiqc).
- **Copyright:** Copyright (c) 2024 Keksi.
- **Source:** [keksiqc/monospace-theme](https://github.com/keksiqc/monospace-theme/tree/50761831abba262d3c259925fbddb1f6492ef891), extension version 1.5.0.
- **Pinned commit:** `50761831abba262d3c259925fbddb1f6492ef891`.
- **License:** MIT; the original notice is preserved in [LICENSE](LICENSE).
- **Use in this port:** Monospace Light and Dark palettes, supported syntax rules, and terminal colors adapted to Orca's public theme format.

The upstream README describes Monospace as a modified version of the theme used in Google IDX. That provenance is credited here without implying endorsement by Google or the upstream author.

The port maps VS Code UI colors to Orca tokens, filters unsupported syntax selectors/settings and low-contrast foregrounds, and composites terminal selection alpha against the terminal background. Supported rules preserve upstream order, colors, and font styles. Unsupported selectors/settings and low-contrast foregrounds are omitted.

## Retained icon notices

The following notices from the upstream icon directory are retained alongside the theme's preview artwork and any depicted upstream icons:

| Upstream notice | License and attribution | Local copy |
| --- | --- | --- |
| [icons/LICENSE-GOOGLE](https://github.com/keksiqc/monospace-theme/blob/50761831abba262d3c259925fbddb1f6492ef891/icons/LICENSE-GOOGLE) | Apache License, Version 2.0 | [LICENSE-GOOGLE](LICENSE-GOOGLE) |
| [icons/LICENSE-SETI](https://github.com/keksiqc/monospace-theme/blob/50761831abba262d3c259925fbddb1f6492ef891/icons/LICENSE-SETI) | MIT; Copyright (c) 2014 Jesse Weed | [LICENSE-SETI](LICENSE-SETI) |

These notices apply to their respective upstream-derived assets. The Monospace MIT license does not supersede third-party asset licenses.

## Preview artwork

The cover and dark/light previews are rendered illustrations based on the port's palettes and syntax colors. They are not screenshots captured from Orca. Any depicted third-party assets retain their original attribution and license.
