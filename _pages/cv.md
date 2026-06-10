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
* **Mar 2024 – Mar 2026 · Research Assistant**, [RostLab](https://www.cs.cit.tum.de/bio/home/), TUM (Munich)
  * Continued the toxin protein family prediction project after graduation;
    reworked the data handling pipeline
* **Jul 2025 – Dec 2025 · Research Assistant**, [Heinzinger Lab](https://www.helmholtz-munich.de/icb/research-groups/heinzinger-lab), Helmholtz Munich (Institute of Computational Biology, ICB)
* **Jan 2023 – Jun 2023 · Research Assistant**, Zielinski Lab, Leibniz HKI (Jena)
  * Human T-cell immunology with high-dimensional scRNA-seq data analysis (Seurat, Scanpy)
* **Sep 2021 – Dec 2022 · Working Student**, Bavarian State Office for Health and
  Food Safety (LGL), Munich

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
* **OncoTox — Predicting Anti-Cancer Drug Efficacy** · Research project, Tsunoda Lab, University of Tokyo, 2026 · *private repository*
  * Multi-task model predicting per-drug cancer cell viability from single-cell
    RNA-seq (CTRPv2 drug response, scGPT embeddings)
  * Supervised by Prof. Tsunoda &amp; Dr. Artem Lysenko
* **[ToxFam — Predicting Animal Toxin Protein Families](https://github.com/Sisistern123/ToxFam)** · Bachelor's thesis, RostLab, TUM, 2024–2025
  * Toxin protein-family classifier reaching ~98% accuracy from ProtT5 embeddings
    with optional NCBI taxonomy features; ongoing toward a publication
  * Supervised by Dr. Ivan Koludarov, Tobias Senoner &amp; Prof. Burkhard Rost
* **[ProFold — End-to-End Protein Structure Prediction](https://github.com/BetelgeuseBugFixer/MaPra2025)** · Master's practical, TUM, 2025
  * Differentiable sequence-to-structure framework (pLM + CNN + Bio2Token),
    ~100× faster than ESMFold
  * Supervised by Dr. Michael Heinzinger &amp; Prof. Burkhard Rost
* **[InsDelGLM — Variant Effect Prediction](https://github.com/LegoCreation/InsDelGLM)** · Course project (Computational Modeling for Systems Genetics), TUM, 2025–2026
  * Predicting the effect of insertion and deletion variants with genomic
    language models
  * Supervised by Pedro Tomaz da Silva &amp; Prof. Julien Gagneur
* **ProtFrag — Protein Fragment Prediction** · Course project (Protein Prediction II), TUM, 2025–2026 · *private repository*
  * Multi-task model classifying complete vs. fragment and the fragment type,
    from ProtT5 embeddings
  * Supervised by Tobias Senoner &amp; Prof. Burkhard Rost
* **Signal Peptide Prediction** · Research project, RostLab, TUM, 2021–2022 · *code coming soon*
  * Machine-learning model for signal peptide classification
  * Supervised by Prof. Burkhard Rost &amp; Dr. Konstantin Weißenow

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
