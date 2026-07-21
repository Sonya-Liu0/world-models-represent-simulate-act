# Awesome World Models: Represent, Simulate, and Act 🌍

A curated collection of world model papers, datasets, benchmarks, and resources organized around the three-stage information flow:

**Representation → Simulation → Action**

World models learn internal representations of environments, predict possible futures, and use these predictions to support decision-making and embodied intelligence.

## Contents

| Topic | Description |
|---|---|
| 📖 Survey | Surveys and foundations |
| 🧠 Representation | Predictive latent states and structured representations |
| 🌎 Simulation | Future prediction, generation, and physical simulation |
| 🤖 Action | VLA models and world action models |
| 📦 Datasets | Training resources |
| 📊 Benchmarks | Evaluation platforms |

## Taxonomy

### 🧠 Representation

Learning what information should be preserved from observations.

- Latent-State Representation
- Tokenized Representation
- Structured Representation

See: [REPRESENT.md](REPRESENT.md)

### 🌎 Simulation

Expanding internal states into possible futures.

- Latent Dynamics
- Observation-Space Generation
- Physical Simulation

See: [SIMULATE.md](SIMULATE.md)

### 🤖 Action

Grounding predicted futures into executable behavior.

- Policy Grounding
- Vision-Language-Action Models
- World Action Models

See: [ACTION.md](ACTION.md)

## Database-driven Maintenance

This repository maintains structured metadata in `data/papers.yaml`.
Markdown pages can be regenerated using:

```bash
python scripts/generate_awesome.py
```

## Citation

If this repository helps your research, please cite the related survey:

"Learning to Represent, Simulate, and Act: A Survey of World Models"

## License

Paper copyrights belong to their respective authors and publishers.
