# World Models: Represent, Simulate, and Act

[中文说明](README.zh-CN.md)

A reproducible literature library built from **Learning to Represent, Simulate, and Act: A Survey of World Models** and its supplied BibTeX bibliography.

## What is included

- **64 bibliography records** from the supplied reference file. Citation key `56` is absent in the source.
- Primary method-paper taxonomy: **10 represent**, **13 simulate**, and **16 action**.
- **25 supporting resources** covering surveys, theory, datasets, benchmarks, metrics, simulators, and talks.
- BibTeX split by category, plus YAML/JSON/CSV catalogs.
- A resumable downloader for open-access PDFs.
- Validation scripts and a metadata-audit report.

> The three model categories are intentionally not treated as mutually exclusive. The catalog stores a primary category for navigation and secondary categories for cross-stage systems.

## Repository layout

```text
.
├── data/
│   ├── papers.yaml          # canonical catalog
│   ├── papers.json
│   └── papers.csv
├── references/
│   ├── all.bib
│   └── by-category/
├── docs/
│   ├── represent.md
│   ├── simulate.md
│   ├── action.md
│   ├── supporting.md
│   ├── classification-policy.md
│   └── metadata-audit.md
├── papers/                  # downloaded locally; ignored by Git by default
├── scripts/
│   ├── download_papers.py
│   ├── export_catalog.py
│   ├── validate_catalog.py
│   └── make_reading_list.py
└── .github/workflows/validate.yml
```

## Download the papers

Python 3.10+ is recommended.

```bash
python -m pip install -r requirements.txt
python scripts/download_papers.py --all --workers 4
```

Download only one core category:

```bash
python scripts/download_papers.py --category represent
python scripts/download_papers.py --category simulate
python scripts/download_papers.py --category action
```

The downloader verifies the `%PDF` signature, resumes safely by skipping existing files, records SHA-256 checksums, and writes `data/download-manifest.json` plus `data/download-report.csv`.

The catalog currently contains **59 direct PDF records**, **2 webpage records**, **2 manual records**, and **1 blocked/unresolved record**. Non-PDF items remain visible instead of being silently omitted; an identifier that resolves to the wrong paper is explicitly blocked.

## Validate the library

```bash
python scripts/validate_catalog.py
```

## Generate a concise reading list

```bash
python scripts/make_reading_list.py
```

## Publishing PDFs to GitHub

The repository ignores downloaded PDFs by default so that the public Git history stays lightweight and respects each paper's redistribution terms. To version open-access PDFs explicitly, use Git LFS and review each source license first:

```bash
git lfs install
git lfs track "papers/**/*.pdf"
git add .gitattributes papers/
```

## Taxonomy entry points

- [Represent](docs/represent.md)
- [Simulate](docs/simulate.md)
- [Action](docs/action.md)
- [Supporting resources](docs/supporting.md)
- [Classification policy](docs/classification-policy.md)
- [Metadata audit](docs/metadata-audit.md)
- [Download status](docs/download-status.md)
- [Citation-key note](docs/citation-key-map.md)
- [Contributing](CONTRIBUTING.md)

## Citation and licensing

Bibliographic metadata and repository code are provided for research organization. Each paper remains subject to its publisher or author license. Do not redistribute paywalled copies without permission.
