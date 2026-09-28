# tinyvit-notes

Tiny CNN experiments on synthetic image data

Started as a weekend hack, grew on me.

## Install

```bash
pip install -r requirements.txt
```

## What it does

- Single file model definition, easy to hack
- Synthetic dataset mode: no download needed to smoke-test
- Metrics logged to CSV for plotting
- Gradient clipping and clean metrics logging
- Cosine LR schedule with warmup

## How to use

```bash
python train.py --epochs 5 --synthetic
# metrics land in runs/metrics.csv
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── SECURITY.md
├── model.py
├── requirements.txt
└── train.py
```
