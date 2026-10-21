# Mochi Karten-Collection – Season 1 (aktive Karten)

Dieses Paket ist für das öffentliche Bild-Repository `Shialyn/mochi-karten-collection` vorbereitet. Es enthält alle **77 aktiven Kartenbilder** als WebP sowie das passende `cards-manifest.json`.

- **77 aktive Karten** mit eindeutigen IDs
- **Rank Rare ist nicht enthalten**; diese Karten liegen im separaten Reserve-Paket
- WebP-Dateien einheitlich auf 220 × 320 Pixel optimiert
- Varianten behalten eigene IDs; vorhandene Karten werden nicht überschrieben

## In das GitHub-Repository übernehmen

1. ZIP lokal entpacken.
2. Im öffentlichen Repository `Shialyn/mochi-karten-collection` die 77 `.webp`-Dateien hochladen und committen.
3. Danach `cards-manifest.json` durch die Version aus diesem Paket ersetzen und committen.
4. `README.md` kann ebenfalls durch diese Version ersetzt werden.

Wichtig: Erst die Bilder hochladen, dann das Manifest aktualisieren. So verweist das Manifest nicht vorzeitig auf Bilder, die noch nicht veröffentlicht wurden.

## Dateiformat

Alle aktiven Bilddateien und `cards-manifest.json` liegen im Paket-Root. Die Anwendung kann die Bilder über Raw-GitHub-URLs und `CARD_ASSET_BASE_URL` laden.
