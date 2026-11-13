# Cross-Chain Oracle Price Deviation Study

This repository contains python notebooks for experiments on BTC/USD and ETH/USD Chainlink oracle price deviations across Ethereum, BNB Chain, Avalanche, and Optimism.

The included datasets cover:

- BTC/USD, Jan-Mar 2024
- BTC/USD, Jan-Mar 2026
- ETH/USD, Jan-Mar 2024
- ETH/USD, Jan-Mar 2026

## Repository Layout

```text
dataset/      Processed 1-minute cross-chain price datasets.
notebooks/    Python notebooks, one per dataset.
results/      CSV, JSON, and PDF files.
```

## Execution

Create an environment and install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebooks in `notebooks/`:

```text
btc-janmar24.ipynb
btc-janmar24-twap.ipynb
btc-janmar26.ipynb
eth-janmar24.ipynb
eth-janmar26.ipynb
```

The TWAP notebook reuses `dataset/btc-janmar24/1min.csv` and exports the Step 4b TWAP window sensitivity outputs in `results/btc-janmar24-twap/`.


## Data

The processed datasets are in `dataset/`. See `dataset/README.md` for column descriptions and provenance notes.
