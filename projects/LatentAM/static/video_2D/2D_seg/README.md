# Open-vocabulary 3D segmentation images (2D_seg)

Naming convention used by the Open-vocabulary 3D segmentation section:

- **RGB (one per scene):** `{scene}_rgb.png` — e.g. `tum1_rgb.png`, `tum3_rgb.png`
- **Feature-3DGS / M3 / LatentAM (per scene + query):** `{scene}_{slot}_{query}.png`
  - **slot:** `feat` | `m3` | `pro` (Feature-3DGS, M3, LatentAM)
  - **query:** see below

## TUM1 queries
- book, monitor, keyboard

Example: `tum1_feat_book.png`, `tum1_m3_monitor.png`, `tum1_pro_keyboard.png`

## TUM3 queries
- keyboard, monitor, teddy

Example: `tum3_feat_teddy.png`, `tum3_m3_monitor.png`, `tum3_pro_keyboard.png`

## Columns (left to right)
1. **RGB** — `{scene}_rgb.png`
2. **Feature-3DGS (Online)** — `{scene}_feat_{query}.png`
3. **M3 (Online)** — `{scene}_m3_{query}.png`
4. **LatentAM (ours)** — `{scene}_pro_{query}.png`
