# Neoantigen Melanoma — Literature Index

Browseable, searchable index of the curated literature corpus supporting the **Theodore F. Logan, MD** vaccine + VDLN-derived in-vitro-sensitized T-cell (IVS-T) adoptive immunotherapy revival program (Indiana University Melvin and Bren Simon Comprehensive Cancer Center).

**Live site:** https://laulpogan.github.io/neoantigen-melanoma-paper-index/

## What's in here

- **`index.html`** — single-page searchable / filterable / sortable table of all 4,329 papers. Click any row to expand its abstract. PMIDs link to PubMed.
- **`corpus.json`** (~1.9 MB) — compact paper metadata (no abstracts) for fast initial load.
- **`corpus-full.json`** (~7.6 MB) — full corpus including abstracts; loaded lazily when a row is expanded.
- **`MASTER_CORPUS.csv`** — original CSV (downloadable).
- **`eras.json`** — era manifest (slug + count).
- **`by-era/*.md`** — 20 per-era markdown files (top-papers narrative for each era bucket).
- **`ERAS.md`**, **`ERA_SUMMARIES.md`** — era guide and era-by-era summary doc.
- **`CORPUS_STATS.md`**, **`AUTHOR_FREQUENCY.md`** — corpus statistics and top-author frequency.

## Era buckets (20)

| Era | Description | Count |
|---|---|---|
| 01 | IVS / LAK era | 200 |
| 02 | TIL + IL-2 era | 46 |
| 03 | Defined-antigen era | 200 |
| 04 | ACT + lymphodepletion era | 193 |
| 05 | Neoantigen-discovery era | 200 |
| 06 | Personalized-vaccine era | 199 |
| 07 | TIL clinical modern era | 154 |
| 08 | Theodore-curated PDFs | 55 |
| 09 | Pan-cancer mechanism | 175 |
| 10 | Bridging era 2006–2014 | 297 |
| 11 | Lifileucel + KEYNOTE-942 pivotal | 300 |
| 12 | Top authors 2018+ | 300 |
| 13 | Grant-infrastructure | 300 |
| 14 | Stratified pull 2007–2012 | 1,198 |
| **15** | **Logan published works (anchor)** | **48** |
| 16 | Chang–Shu lineage | 182 |
| 17 | Berd / DNP / M-Vax | 143 |
| 18 | Sondel anti-CD3 + IL-2 | 113 |
| 19 | Autologous tumor + BCG + VDLN | 51 |
| 20 | Hoover / Mukherji / Wallack historical | 127 |

## Why a separate repo?

The full grant package (`neoantigen-melanoma-grant`) contains pre-publication grant drafts, outreach drafts, and operational planning material that should not be public. This repo is the **literature index only** — citation metadata + abstracts pulled from PubMed E-utilities. All metadata is from the public PubMed corpus.

## Source of truth

- PubMed via NCBI E-utilities (`esearch` + `efetch`)
- Pull period: 1972–2026 (window varies by era query)
- Last full pull: 2026-04-30
- 64 of these papers are also archived as PDFs in Theodore's curated set (era 08); PDF licensing precludes hosting them publicly here.

## License

CC0 / public domain — this is a curated index over PubMed public-domain metadata; the literature itself remains under its respective publishers' copyright.
