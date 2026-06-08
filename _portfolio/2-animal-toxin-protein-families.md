---
title: "ToxFam — Predicting Animal Toxin Protein Families"
excerpt: "A toxin protein-family classifier reaching ~98% accuracy using ProtT5 protein language model embeddings. Bachelor's thesis (graded 1.0), continued at RostLab, TUM."
collection: portfolio
link: https://github.com/Sisistern123/ToxFam
---

My bachelor's thesis at **TUM &amp; LMU** (graded 1.0), later continued as a
research assistant at the **RostLab, TUM** (supervised by Prof. Burkhard Rost and
Dr. Ivan Koludarov).

- Classifies animal toxin sequences into families using MLP networks on **ProtT5**
  embeddings, with optional NCBI taxonomy features.
- Reduces sequence redundancy with MMseqs2 clustering and harmonizes labels;
  reaches **~98% accuracy**.
- Runnable in Google Colab on your own FASTA sequences.

**Code:** [github.com/Sisistern123/ToxFam](https://github.com/Sisistern123/ToxFam)

This work also fed into a co-authored publication on venom database metrics (see
[Publications](/publications/)); the underlying ToxProt analysis lives in
[tsenoner/toxprot25](https://github.com/tsenoner/toxprot25).
