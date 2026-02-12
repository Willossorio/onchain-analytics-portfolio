# On-chain Analytics Portfolio (Solana)

This repository showcases structured on-chain research dashboards built using Dune Analytics, SQL, and Python. The work focuses on perpetual futures positioning, liquidity dynamics, wallet behavior, execution quality, and market regime classification across the Solana ecosystem. Each dashboard is designed to translate raw blockchain data into actionable market structure insights.


Author: William Manuel Ossorio  
Dune Profile: https://dune.com/wossorio


---

## Portfolio Overview

This portfolio presents a structured, multi-layered analysis of Solana’s on-chain market structure, spanning derivatives positioning, liquidity regimes, execution quality, protocol reflexivity, and validator-level infrastructure dynamics.

The dashboards are designed to:

- Translate raw blockchain data into interpretable structural signals
- Diagnose leverage expansion vs deleveraging environments
- Quantify liquidity stress and informed flow regimes
- Benchmark execution quality across DEXs and aggregators
- Measure reflexivity through protocol buyback activity
- Assess validator concentration and MEV distribution risks

Together, these projects form an integrated analytical framework that connects derivatives markets, spot liquidity, execution routing, and infrastructure-level incentives into a cohesive structural view of the ecosystem.

---

## Research Framework

This portfolio is structured around three core analytical pillars:

1. **Market Structure & Leverage Dynamics**  
   Derivatives positioning, funding rate pressure, open interest expansion, and crowding diagnostics.

2. **Liquidity & Flow Regimes**  
   Rolling liquidity stress indicators, informed flow proxies, and regime classification models.

3. **Execution & Microstructure Quality**  
   Slippage diagnostics, routing efficiency, liquidity depth, and DEX benchmarking.

Each dashboard is designed to translate raw on-chain and derivatives data into interpretable structural signals.


---

## Dashboards

### 1. Perpetual Futures Market Structure & Leverage Cycles — Solana

Live Dashboard:  
https://dune.com/wossorio/perpetual-futures-market-structure-leverage-cycles

Focus:  
Analyzes open interest, funding rates, leverage expansion vs deleveraging cycles, crowding regimes, and funding-weighted directional bias to classify market structure across SOL, ETH, and BTC perpetual markets.

Key Concepts:
- Open Interest (USD Notional)
- Funding Rate Dynamics (1d & 7d)
- OI vs Funding Divergence (Normalized Z-score)
- Leverage Expansion vs Deleveraging Regimes
- Funding-Weighted Directional Bias
- Crowding Classification (Long / Short / Neutral)

---
---

### 2. Solana DEX Execution Benchmark


Live Dashboard:
https://dune.com/wossorio/solana-dex-execution-benchmark

Focus:
Evaluates execution quality across major Solana decentralized exchanges by analyzing slippage patterns, trade size impact, liquidity depth, and routing efficiency.

Key Concepts:

- Slippage Distribution by Trade Size
- Price Impact vs Liquidity Depth
- Aggregator vs Direct Routing Comparison
- Execution Quality Benchmarking Across DEXs
- Market Microstructure Diagnostics

---

### 3. Liquidity Stress & Informed Flow Regimes — Solana (30D Rolling)

Live Dashboard:
https://dune.com/wossorio/liquidity-stress-and-informed-flow-regimes-solana-30d-rolling

Focus:
Constructs composite liquidity and informed flow indicators using rolling 30-day metrics to classify stress environments and directional conviction across the Solana ecosystem.

Key Concepts:

- Liquidity Imbalance Metrics
- Rolling Volume Concentration
- Informed Flow Proxy Signals
- Stress Regime Classification
- Structural Shift Detection

---

### 4. JUP Buybacks vs Organic Market Demand — Solana

Live Dashboard:
https://dune.com/wossorio/jup-buybacks-vs-organic-market-demand

Focus:
Quantifies the impact of Jupiter protocol buybacks relative to organic market demand by comparing programmatic token repurchases against natural trading flows to assess reflexivity, price support strength, and sustainability of upward moves.

Key Concepts:

- Buyback Volume vs Total Volume Share
- Buyback Intensity Ratio
- Net Organic Flow Estimation
- Price Response vs Buyback Activity
- Reflexivity Diagnostics

---

### 5. Solana Aggregator Routing & Execution — Jupiter

Live Dashboard:
https://dune.com/wossorio/solana-aggregator-routing-execution-jupiter

Focus:
Analyzes routing efficiency and execution quality across Jupiter aggregator paths versus direct DEX execution to evaluate slippage optimization, liquidity sourcing behavior, and cross-venue price impact.

Key Concepts:

- Aggregator vs Direct Execution Comparison
- Route Efficiency by Trade Size
- Slippage Differential Analysis
- Liquidity Source Composition
- Execution Cost Diagnostics

---

### 6. Solana Validator & MEV Landscape — Jito Focus

Live Dashboard:  
https://dune.com/wossorio/solana-validator-and-mev-landscape-jito-focus

Focus: Analyzes validator distribution, Jito adoption, MEV block production share, fee market concentration, and stake centralization to assess structural risk and execution layer dynamics across the Solana ecosystem.

Key Concepts:

- Validator Stake Distribution
- Jito vs Non-Jito Block Share
- MEV Reward Concentration
- Fee Market Capture Analysis
- Infrastructure Centralization Diagnostics


