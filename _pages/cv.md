---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.Sc. in Bioinformatics**, Technical University of Munich (TUM) &amp; Ludwig
  Maximilian University of Munich (LMU) — joint program, April 2025 – present
* **B.Sc. in Bioinformatics**, TUM &amp; LMU — joint program, November 2020 – March 2025
  * Final grade: 2.4 (German scale, 1.0 = best)
  * Bachelor's thesis: *Prediction of Animal Toxin Protein Families* — grade 1.0
  * Key areas: genomics, transcriptomics, proteomics, machine learning, deep
    learning, statistical and high-throughput data analysis

Research experience
======
* **Mar 2026 – Aug 2026 · Visiting Researcher**, Tsunoda Lab, University of Tokyo (Todai)
  * Predicting anti-cancer drug efficacy scores using machine learning
* **Mar 2024 – May 2025 · Research Assistant**, RostLab, TUM (Munich)
  * Continued the toxin protein family prediction project after graduation;
    reworked the data handling pipeline
* **Jan 2023 – Jun 2023 · Research Assistant**, Zielinski Lab, Leibniz HKI (Jena)
  * Human T-cell immunology with high-dimensional scRNA-seq data analysis (Seurat, Scanpy)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
* **OncoTox — Predicting Anti-Cancer Drug Efficacy** (Tsunoda Lab, Univ. of Tokyo, 2026)
  — multi-task model predicting per-drug cancer cell viability from single-cell
  RNA-seq (CTRPv2 drug response, scGPT embeddings)
* **ToxFam — Predicting Animal Toxin Protein Families** — toxin protein-family
  classifier reaching ~98% accuracy using ProtT5 protein language model embeddings
  and optional taxonomy features (supervised by Prof. Burkhard Rost &amp;
  Dr. Ivan Koludarov) · [github.com/Sisistern123/ToxFam](https://github.com/Sisistern123/ToxFam)
* **ProFold — End-to-End Protein Structure Prediction** (Master's practical, 2025)
  — differentiable sequence-to-structure framework (pLM + CNN + Bio2Token),
  ~100× faster than ESMFold · [github.com/BetelgeuseBugFixer/MaPra2025](https://github.com/BetelgeuseBugFixer/MaPra2025)
* **InsDelGLM — Variant Effect Prediction** — predicting the effect of insertion
  and deletion variants with genomic language models · [github.com/LegoCreation/InsDelGLM](https://github.com/LegoCreation/InsDelGLM)
* **ProtFrag — Protein Fragment Prediction** — multi-task model classifying whether
  a sequence is complete vs. a fragment and the fragment type, from ProtT5 embeddings
* **Signal Peptide Prediction** — machine-learning model for signal peptide
  classification (supervised by Prof. Burkhard Rost &amp; Dr. Konstantin Weißenow)

Conferences
======
* AI for Health Symposium 2025, Helmholtz Munich

Skills
======
* **Programming:** Python, Java, Bash, SQL, R
* **ML &amp; data science:** PyTorch, scikit-learn, CNNs, NumPy, Pandas, SciPy
* **Bioinformatics:** BLAST, MMseqs2, UniProt, GenBank, Scanpy, Seurat, DESeq2
* **Tools:** Git, Jupyter, LaTeX, Markdown
* **Languages:** German (native), English (C1), French (B1), Japanese (A1)

Service and leadership
======
* **Bioinformatics Student Representative** — represented student interests and organized student events
* **Student Senator, LMU** — contributed to university-wide decision-making and student welfare, and managed student body finances
