# Contributing

## Add or revise a paper

1. Edit `data/papers.yaml`, which is the canonical catalog.
2. Run `python scripts/export_catalog.py` after editing the YAML to regenerate JSON, CSV, and category pages.
3. Use one primary category: `represent`, `simulate`, `action`, or `supporting`.
4. Add secondary categories only when the paper technically implements and evaluates those stages.
5. Prefer an official open-access PDF URL: arXiv, OpenReview, PMLR, NeurIPS proceedings, or an author-hosted manuscript.
6. Record uncertain or conflicting metadata in `quality_flags` and `docs/metadata-audit.md`; never guess a PDF URL.
7. Run validation and commit both the canonical YAML and regenerated files.

## Classification test

Assign the primary category by locating the paper's dominant technical novelty:

- **represent**: predictive latent state, tokenization, object/scene structure, or geometry-aware encoding;
- **simulate**: latent rollout, observation/world generation, or physically constrained future prediction;
- **action**: executable policy, VLA action generation, or prediction-guided control;
- **supporting**: survey, theory, dataset, benchmark, metric, simulator, interface, or talk.

A downstream robot experiment alone does not make a representation paper an action paper. Likewise, a video output alone does not make a tokenization paper primarily a simulation paper.

## Validate

```bash
python -m pip install -r requirements.txt
python scripts/validate_catalog.py
python scripts/export_catalog.py
python scripts/make_reading_list.py
git diff --exit-code
```
