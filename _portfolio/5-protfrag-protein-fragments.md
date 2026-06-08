---
title: "ProtFrag — Protein Fragment Prediction"
excerpt: "Multi-task deep learning that detects whether a protein sequence is complete or a fragment, and which fragment type, from ProtT5 embeddings."
collection: portfolio
---

A multi-task deep-learning model that predicts protein fragments from **ProtT5**
embeddings:

- **Binary:** complete vs. fragment.
- **Multilabel:** fragment type (N-terminal, C-terminal, internal gaps).

The pipeline covers UniProt parsing, MMseqs2 clustering and leakage-free splits,
embedding preparation, training, hyperparameter tuning, and evaluation.

*Code: private repository.*
