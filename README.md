# quran-qcf4-fonts

Self-hosted Quran fonts for the qanit app's QCF4 (QPC V4) mushaf reader, so the
app doesn't depend on third-party hosts.

- `pages/`  — per-page layout JSON (604; `001.json`..`604.json`)
- `fonts/`   — regular Hafs page faces (48; mirror of the QCF4 set)
- `bold/`    — emboldened +0.8% Hafs faces (47; shown at 1× zoom)
- `tajweed/` — per-page COLRv0 tajweed color fonts (604; `p1.ttf`..`p604.ttf`)

Fetched via raw.githubusercontent. The bold set is generated reproducibly by
`scripts/generate-bold-mushaf-fonts.py` in the app repo. Sources: QCF4 (QUL /
King Fahd Complex QPC V4) and the v4-tajweed set; redistributed for Quran use.
