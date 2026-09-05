# GeoTrade: Geopolitical Shocks and Sectoral Equity Mispricing

I became fascinated by how information becomes prices. After building a sentiment classifier for financial headlines, I kept wondering about a harder question: when geopolitical shocks hit, do markets price them correctly relative to fundamental value, or do they systematically over or underreact?

This is my attempt to investigate that computationally.

## Research Question

Do geopolitical shocks lead to temporary mispricing or permanent repricing in economically exposed sectors, and are market responses asymmetric across escalation and de-escalation events?

## Methodology

Event study methodology applied to GDELT geopolitical event data and sector ETF returns (2014-2023). Market model estimation, cumulative abnormal returns across multiple windows, DCF-implied value comparison, and asymmetry testing across escalation and de-escalation events.

## Structure

- `data/` — raw GDELT data, processed event lists, external reference data
- `notebooks/` — one notebook per stage of analysis
- `src/` — reusable Python modules
- `images/` — charts and visualizations
- `results/` — model outputs and tables
- `paper/` — research paper drafts

## Status

Work in progress. Started September 2026.

*Independent research project. Inspired by questions left unanswered after building a sentiment-driven trading pipeline — if NLP can extract signal from financial headlines, what about geopolitical news?*