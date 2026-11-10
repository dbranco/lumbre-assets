# lumbre-assets

3D models, textures and HDRIs served to the Lumbre app (https://lumbre.pt) for the map street view. The files are static; nothing here receives any data.

## Rules for adding a file

- Only CC0, public domain or CC BY. Never non-commercial, no-derivatives or unlicensed. An itch.io pack goes in only when its own page states one of those licences.
- Every file or pack has a row in `LICENSES.md` (name, author, licence, source URL, date added) before it is committed.
- Files are copied unchanged from the source. `SHA256SUMS` lists every file.
- Keep each asset small: textures at 1K or 2K, models as `.glb`.

## Sources considered

| Source | Licence | Use |
|---|---|---|
| Kenney (https://kenney.nl/assets) | CC0 | models, props |
| Quaternius (https://quaternius.com) | CC0 on most packs, check each | low-poly models and animations |
| Poly Haven (https://polyhaven.com) | CC0 | textures, HDRIs, models |
| ambientCG (https://ambientcg.com) | CC0 | PBR textures |

Layout: `models/`, `textures/`, `hdri/`.
