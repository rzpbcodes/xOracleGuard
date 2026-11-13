# Dataset Notes

Each dataset is a processed 1-minute CSV of Chainlink oracle prices aligned across four chains.

## Files

- `btc-janmar24/1min.csv`: BTC/USD, Jan-Mar 2024
- `btc-janmar26/1min.csv`: BTC/USD, Jan-Mar 2026
- `eth-janmar24/1min.csv`: ETH/USD, Jan-Mar 2024
- `eth-janmar26/1min.csv`: ETH/USD, Jan-Mar 2026

## Columns

- `block_time`: UTC timestamp at 1-minute resolution.
- `avalanche_c`: Avalanche Chainlink oracle price.
- `bnb`: BNB Chain Chainlink oracle price.
- `ethereum`: Ethereum Chainlink oracle price.
- `optimism`: Optimism Chainlink oracle price.

