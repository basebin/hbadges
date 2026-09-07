<p align="center">
  <img src="https://raw.githubusercontent.com/Coccinella-Labs/hbadges/main/.github/assets/thumbnail.png" alt="hbadges" width="100%">
</p>

badge generation for light and dark mode.

Generates 512px badge assets from `assets/icon.png` via `scripts/generate_badges.py` (Pillow): `badge-light.png`, `badge-dark.png` (300px icon, 12px border).

## Run

```bash
pip install pillow
python scripts/generate_badges.py
```