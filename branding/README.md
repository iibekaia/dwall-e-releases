# dwall-e logo assets

The transparent `logo-master.png` is the approved-source artwork prepared from
the user's robot reference with the built-in ImageGen editor. PNG exports retain
its alpha channel. No SVG is supplied: the source is raster, not editable vectors.

- `icon-16.png` through `icon-1024.png`: raster size variants.
- `icon.ico`: Windows installer/application, seven embedded sizes (16–256 px).
- `icon.icns`: macOS application, seven PNG representations (16–1024 px).
- `favicon.ico`: browser, 16/32/48 px.
- UI uses `icon-128.png`; Linux packaging uses `icon-512.png`.

Regenerate the containers and size variants on Windows with
`powershell -File scripts/export-icons.ps1` from the repository root.
The script only resizes and packages the master; it does not generate artwork.

ImageGen edit prompt:

> Edit target: attached robot logo. Create a clean production app logo from this
> EXACT artwork. Preserve its identity, proportions, shapes, two large purple
> rimmed eyes, cream face panels, tiny burgundy and tan neck/base, palette and flat
> faceted illustration style. Remove the white background including empty spaces
> between limbs. Remove the enormous surrounding margins. Center the complete robot
> on a square transparent canvas with about 10% padding. Refine pixelated edges at
> high resolution, without redesigning or adding details. No text, no additional
> objects, no shadow, no white square, actual alpha transparency. Intended as dwall-e
> desktop app icon master.
