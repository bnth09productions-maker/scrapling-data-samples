# Scrapling Data x402 dataset samples

Scrapling Data sells 14 downloadable datasets at [https://scraplingdata.xyz/datasets](https://scraplingdata.xyz/datasets), from $0.01, paid in USDC via x402. This repository holds only the official free preview CSV rows so people and AI engines can see the format and a few real values before buying the full file.

Paid rows are not included. Each CSV was copied from the public sample on its dataset page on Thursday, Nov 12, 2026, 8:09 AM CT. Most live feeds refresh about every 30 minutes; the GPU and RAM file is a snapshot of eBay sold prices as of Nov 11, 2026, not a live feed.

A machine-readable index is in [datasets.json](datasets.json). The same samples are prepared as the Hugging Face dataset [`scraplingdata/x402-dataset-samples`](https://huggingface.co/datasets/scraplingdata/x402-dataset-samples).

## Datasets, prices, and links

| Dataset | ID | Price | Catalog rows (full file) | Sample rows in this repo | Links |
|---|---|---:|---:|---:|---|
| Live Crypto Prices (Chainlink On-Chain, ~155 Assets): Price, 1h/24h/7d/30d Change | `live_crypto_top500_markets` | $0.09 | 155 | 10 | [page](https://scraplingdata.xyz/datasets/live_crypto_top500_markets) · [sample.csv](https://scraplingdata.xyz/datasets/live_crypto_top500_markets/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_crypto_top500_markets/buy) |
| Live DeFi Protocols by Tracked On-Chain TVL with 1d/7d Change | `live_defi_protocols_tvl` | $0.09 | 870 | 10 | [page](https://scraplingdata.xyz/datasets/live_defi_protocols_tvl) · [sample.csv](https://scraplingdata.xyz/datasets/live_defi_protocols_tvl/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_defi_protocols_tvl/buy) |
| Live Blockchain TVL Rankings (On-Chain Protocol Reads, 56 Chains) | `live_chain_tvl` | $0.05 | 54 | 10 | [page](https://scraplingdata.xyz/datasets/live_chain_tvl) · [sample.csv](https://scraplingdata.xyz/datasets/live_chain_tvl/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_chain_tvl/buy) |
| Live DeFi Yield Pools (1,000+ DEX pools, 16 chains): APY, TVL, Risk | `live_defi_yield_pools` | $0.09 | 1547 | 10 | [page](https://scraplingdata.xyz/datasets/live_defi_yield_pools) · [sample.csv](https://scraplingdata.xyz/datasets/live_defi_yield_pools/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_defi_yield_pools/buy) |
| Live Stablecoin Supply & Peg Tracker | `live_stablecoin_supply` | $0.05 | 15 | 7 | [page](https://scraplingdata.xyz/datasets/live_stablecoin_supply) · [sample.csv](https://scraplingdata.xyz/datasets/live_stablecoin_supply/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_stablecoin_supply/buy) |
| Live DEX Trading Volume Rankings (24h, On-Chain) | `live_dex_volumes` | $0.05 | 16 | 8 | [page](https://scraplingdata.xyz/datasets/live_dex_volumes) · [sample.csv](https://scraplingdata.xyz/datasets/live_dex_volumes/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_dex_volumes/buy) |
| Live Polymarket Prediction Market Odds + 1h/24h/7d Odds Change (Top 400 by Volume) | `live_polymarket_odds` | $0.09 | 200 | 10 | [page](https://scraplingdata.xyz/datasets/live_polymarket_odds) · [sample.csv](https://scraplingdata.xyz/datasets/live_polymarket_odds/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_polymarket_odds/buy) |
| Live US Stocks, ETFs & Commodities via Chainlink On-Chain: Price, 1d/5d Change | `live_us_stocks_etfs` | $0.05 | 15 | 7 | [page](https://scraplingdata.xyz/datasets/live_us_stocks_etfs) · [sample.csv](https://scraplingdata.xyz/datasets/live_us_stocks_etfs/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_us_stocks_etfs/buy) |
| New Token Pool Launches on Base & Solana (Last 3 Hours) with Risk Flags | `live_new_pools_base_solana` | $0.09 | 301 | 10 | [page](https://scraplingdata.xyz/datasets/live_new_pools_base_solana) · [sample.csv](https://scraplingdata.xyz/datasets/live_new_pools_base_solana/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_new_pools_base_solana/buy) |
| Base New Token Security Scan: Honeypot, Tax & Owner Risk Score | `live_base_new_token_risk` | $0.01 | 1 | 1 | [page](https://scraplingdata.xyz/datasets/live_base_new_token_risk) · [sample.csv](https://scraplingdata.xyz/datasets/live_base_new_token_risk/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_base_new_token_risk/buy) |
| DeFi Yields Ranked by Risk-Adjusted APY (Pools ≥ $5M TVL) | `live_risk_ranked_yields` | $0.09 | 309 | 10 | [page](https://scraplingdata.xyz/datasets/live_risk_ranked_yields) · [sample.csv](https://scraplingdata.xyz/datasets/live_risk_ranked_yields/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_risk_ranked_yields/buy) |
| Live US Spot Bitcoin, Ethereum & Litecoin ETF Holdings (coins held, bought, sold, totals) | `live_crypto_etf_holdings` | $0.05 | 31 | 10 | [page](https://scraplingdata.xyz/datasets/live_crypto_etf_holdings) · [sample.csv](https://scraplingdata.xyz/datasets/live_crypto_etf_holdings/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_crypto_etf_holdings/buy) |
| Live Perpetuals Snapshot: Stock Perps + Crypto Funding, OI and Volume | `live_perps_snapshot` | $0.02 | 350 | 10 | [page](https://scraplingdata.xyz/datasets/live_perps_snapshot) · [sample.csv](https://scraplingdata.xyz/datasets/live_perps_snapshot/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_perps_snapshot/buy) |
| GPU and RAM eBay Sold Prices: 15 GPUs + 6 DDR4/DDR5 Kits (Median, P25/P75, Used vs New) | `live_gpu_ram_prices` | $0.02 | 21 | 3 | [page](https://scraplingdata.xyz/datasets/live_gpu_ram_prices) · [sample.csv](https://scraplingdata.xyz/datasets/live_gpu_ram_prices/sample.csv) · [buy](https://scraplingdata.xyz/v1/datasets/live_gpu_ram_prices/buy) |

## What each dataset answers

- **Live Crypto Prices (Chainlink On-Chain, ~155 Assets): Price, 1h/24h/7d/30d Change** ($0.09). Current USD prices and 1-hour, 24-hour, 7-day, and 30-day percent change for about 155 crypto assets, read from Chainlink on-chain USD price feeds on Ethereum, Arbitrum, and Base. Market cap, volume, and fully diluted valuation are not available on-chain and are null in the file. Full file: https://scraplingdata.xyz/datasets/live_crypto_top500_markets
- **Live DeFi Protocols by Tracked On-Chain TVL with 1d/7d Change** ($0.09). Tracked on-chain total value locked (TVL) for DeFi protocols, with 1-day and 7-day change, category, and chains. Coverage is the pools Scrapling Data reads on-chain, not every contract. Full file: https://scraplingdata.xyz/datasets/live_defi_protocols_tvl
- **Live Blockchain TVL Rankings (On-Chain Protocol Reads, 56 Chains)** ($0.05). Blockchain TVL rankings built from on-chain protocol reads, with 1-day change. The dataset title describes 56 chains; the store catalog listed 54 rows at the time these samples were fetched. Full file: https://scraplingdata.xyz/datasets/live_chain_tvl
- **Live DeFi Yield Pools (1,000+ DEX pools, 16 chains): APY, TVL, Risk** ($0.09). APY, TVL, and risk fields for 1,000+ DEX yield pools across 16 chains. Full file: https://scraplingdata.xyz/datasets/live_defi_yield_pools
- **Live Stablecoin Supply & Peg Tracker** ($0.05). Stablecoin supply and peg tracker: circulating supply, USD price, peg type, and change versus the prior day, week, and month. Full file: https://scraplingdata.xyz/datasets/live_stablecoin_supply
- **Live DEX Trading Volume Rankings (24h, On-Chain)** ($0.05). 24-hour DEX trading volume rankings computed from on-chain pool fee accumulators, with TVL and fees. Full file: https://scraplingdata.xyz/datasets/live_dex_volumes
- **Live Polymarket Prediction Market Odds + 1h/24h/7d Odds Change (Top 400 by Volume)** ($0.09). Polymarket prediction-market odds for top markets by volume, plus 1-hour, 24-hour, and 7-day odds change, volume, and liquidity. The title describes the top 400 markets; the store catalog listed 200 rows at the time these samples were fetched. Full file: https://scraplingdata.xyz/datasets/live_polymarket_odds
- **Live US Stocks, ETFs & Commodities via Chainlink On-Chain: Price, 1d/5d Change** ($0.05). US stock, ETF, and commodity prices with 1-day and 5-day change, read from Chainlink on-chain oracles. Volume and 52-week high/low may be unavailable on-chain and are null when missing. Full file: https://scraplingdata.xyz/datasets/live_us_stocks_etfs
- **New Token Pool Launches on Base & Solana (Last 3 Hours) with Risk Flags** ($0.09). New token pool launches on Base and Solana in the last three hours, with risk flags, liquidity, and early volume. Full file: https://scraplingdata.xyz/datasets/live_new_pools_base_solana
- **Base New Token Security Scan: Honeypot, Tax & Owner Risk Score** ($0.01). Security scan of a new Base token, including honeypot, tax, and owner risk score and flags. The store catalog listed this full dataset as 1 row at the time these samples were fetched. Full file: https://scraplingdata.xyz/datasets/live_base_new_token_risk
- **DeFi Yields Ranked by Risk-Adjusted APY (Pools ≥ $5M TVL)** ($0.09). DeFi yield pools with at least $5 million TVL, ranked by risk-adjusted APY, with a 0-100 risk score. Full file: https://scraplingdata.xyz/datasets/live_risk_ranked_yields
- **Live US Spot Bitcoin, Ethereum & Litecoin ETF Holdings (coins held, bought, sold, totals)** ($0.05). US spot Bitcoin, Ethereum, and Litecoin ETF holdings from official issuer reports: coins held, bought, and sold, plus totals. Full file: https://scraplingdata.xyz/datasets/live_crypto_etf_holdings
- **Live Perpetuals Snapshot: Stock Perps + Crypto Funding, OI and Volume** ($0.02). A perpetual futures snapshot covering stock perps plus crypto funding rates, open interest, and volume. Full file: https://scraplingdata.xyz/datasets/live_perps_snapshot
- **GPU and RAM eBay Sold Prices: 15 GPUs + 6 DDR4/DDR5 Kits (Median, P25/P75, Used vs New)** ($0.02). eBay sold prices for 15 GPUs and 6 DDR4/DDR5 RAM kits, with median, 25th and 75th percentile, and used vs new splits. Built from cleaned completed sales. Shipping is not included. The free sample is 3 of 21 items. Full file: https://scraplingdata.xyz/datasets/live_gpu_ram_prices

## Example: buy a full dataset with x402 (HTTP 402)

The GPU and RAM sold-price dataset is $0.02. This unpaid request shows the payment challenge:

```bash
curl -i "https://scraplingdata.xyz/v1/datasets/live_gpu_ram_prices/buy?format=json"
```

Expected response shape (shortened from a live unpaid call; payment details are in the full 402 body):

```
HTTP/2 402
Content-Type: application/json

{
  "x402Version": 2,
  "error": "Payment Required",
  "priceUsd": 0.02,
  "accepts": [
    {"scheme": "exact", "network": "eip155:8453", "chainName": "Base Mainnet", "amountUsd": 0.02, "assetSymbol": "USDC"},
    {"scheme": "exact", "network": "eip155:137", "chainName": "Polygon PoS", "amountUsd": 0.02, "assetSymbol": "USDC"},
    {"scheme": "exact", "network": "eip155:42161", "chainName": "Arbitrum One", "amountUsd": 0.02, "assetSymbol": "USDC"},
    {"scheme": "exact", "network": "solana:5eykt4UsFv8P8NJdTREpY1vzqKqZKvdp", "chainName": "Solana", "amountUsd": 0.02, "assetSymbol": "USDC"}
  ]
}
```

Pay the listed USDC amount with any x402 client, then retry the same URL with the payment proof. No account or API key is required. Failed calls are not charged. The paid GPU and RAM file is 21 rows; this repo only has the 3-row free sample.

Replace `live_gpu_ram_prices` in the URL with any dataset ID in the table to buy that file.

## Other store links

- Catalog: https://scraplingdata.xyz/datasets
- Agent index: https://scraplingdata.xyz/llms.txt
- Longer store description: https://scraplingdata.xyz/llms-full.txt
- API docs: https://scraplingdata.xyz/docs
- x402 manifest: https://scraplingdata.xyz/.well-known/x402
- Terms: https://scraplingdata.xyz/terms

## License and disclaimer

These preview rows may be copied and redistributed for discovery and attribution with a link back to [https://scraplingdata.xyz](https://scraplingdata.xyz) and the matching dataset page. See [LICENSE](LICENSE). Data is provided as-is, without warranties. Nothing here is financial, investment, or legal advice.
