# Awesome World Models: Represent, Simulate, and Act 🌍

A curated collection of papers, datasets, benchmarks, and resources for **World Models**.

This repository organizes world models from an information-flow perspective:

```
Observation
     ↓
Representation
     ↓
Simulation
     ↓
Action
     ↓
Environment
```

## Contents

| Category | Description | Link |
|---|---|---|
| Survey | World model surveys and tutorials | [SURVEY.md](SURVEY.md) |
| Representation | Predictive internal states | [REPRESENT.md](REPRESENT.md) |
| Simulation | Future prediction and generation | [SIMULATE.md](SIMULATE.md) |
| Action | Embodied control and VLA systems | [ACTION.md](ACTION.md) |
| Datasets | Training resources | [DATASETS.md](DATASETS.md) |
| Benchmarks | Evaluation platforms | [BENCHMARKS.md](BENCHMARKS.md) |

## Taxonomy

### Representation Models

Learning compact and predictive states from observations.

Main directions:

- Latent-State Representation
- Tokenized Representation
- Structured Representation

### Simulation Models

Expanding internal states into possible futures.

Main directions:

- Latent Dynamics
- Observation-Space Generation
- Physical Simulation

### Action Models

Using predicted futures for executable behavior.

Main directions:

- Policy Grounding
- Vision-Language-Action Models
- World Action Models

## Repository Structure

```
.
├── README.md
├── REPRESENT.md
├── SIMULATE.md
├── ACTION.md
├── DATASETS.md
├── BENCHMARKS.md
├── SURVEY.md
├── references/
├── data/
└── scripts/
```

## Citation

If this repository helps your research, please cite:

```
Learning to Represent, Simulate, and Act: A Survey of World Models
```
