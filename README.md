# Clickbait Detection

This repository explores clickbait headline detection using both supervised and unsupervised approaches.

## Repository structure

- `supervised-approach/` — notebook for the supervised CNN-based approach.
- `unsupervised-approach/` — notebook for the unsupervised approach.

## Requirements

The notebooks were built for Python and use common data-science libraries, including:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `tensorflow` (supervised notebook)
- `nltk`, `torch`, and `transformers` (unsupervised notebook)

## Data

The supervised workflow expects:

- `train.jsonl`
- `validation.jsonl`

The unsupervised workflow includes preprocessing and split generation utilities that produce files such as:

- `train_split.jsonl`, `val_split.jsonl`, `test_split.jsonl`
- `train_preprocessed.jsonl`, `val_preprocessed.jsonl`, `test_preprocessed.jsonl`

## How to run

1. Open either notebook in Jupyter or Google Colab.
2. Place the required `.jsonl` data files in the same working directory as the notebook.
3. Run the notebook cells in order.

## Current status

- Supervised model: implemented and tested.
- Unsupervised model: work in progress.
