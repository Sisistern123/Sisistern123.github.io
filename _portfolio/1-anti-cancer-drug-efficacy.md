---
title: "OncoTox — Predicting Anti-Cancer Drug Efficacy"
excerpt: "Multi-task deep learning that predicts per-drug cancer cell viability from single-cell RNA-seq. Research project at the Tsunoda Lab, University of Tokyo (2026)."
collection: portfolio
---

A research project at the **Tsunoda Lab, University of Tokyo (Todai)**
(March–August 2026), using machine learning to **predict anti-cancer drug
efficacy scores** — i.e. how effective candidate drugs are likely to be.

- Multi-task model (`OncoMLP`) predicting per-drug cell viability with masked MSE
  over many CTRPv2 drugs at once.
- Inputs from single-cell RNA-seq (SCP542) with scGPT embeddings.
- Cell-line–grouped, leakage-free train/validation/test splits, benchmarked
  against a per-drug-mean baseline.

*Code: private repository (work in progress).*
