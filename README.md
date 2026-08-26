# IMIT 1898 / ORZSE-MANDA – Mózes első könyve

Ez a repó egy statikus, GitHub Pages alatt futtatható párhuzamos korrektúra-nézőt tartalmaz az IMIT 1898-as Mózes első könyve XML-rétegéhez és a hozzá tartozó PDF-hez.

## Tartalom

- `docs/index.html` – párhuzamos XML/JSON + PDF néző, versenkénti kommentexporttal
- `docs/data/imit_1898_orzse_manda_genesis.xml` – IMIT XML az `IMIT_1898_ORZSE_MANDA` réteggel
- `docs/assets/pdf/1_Moz.pdf` – forrás PDF

A teljes OCR JSON nincs a repóban. A néző továbbra is képes JSON betöltésére helyi fájlból, de az opcionális ellenőrzési bemenet marad.

## GitHub Pages beállítás

Repository Settings → Pages → Build and deployment → Source: `Deploy from a branch` → Branch: `main` → Folder: `/docs`.

Ezután az oldal a GitHub Pages URL-en nyílik meg.
