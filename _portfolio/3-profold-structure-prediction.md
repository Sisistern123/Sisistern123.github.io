---
title: "ProFold — End-to-End Protein Structure Prediction"
excerpt: "An end-to-end differentiable framework predicting 3D protein structure directly from sequence, ~100× faster than ESMFold. Master's practical (Masterpraktikum) team project, 2025."
collection: portfolio
link: https://github.com/BetelgeuseBugFixer/MaPra2025
---

A team project from our **Master's practical (Masterpraktikum), 2025**: an
end-to-end, fully differentiable framework that predicts 3D atomic coordinates
directly from an amino acid sequence — no MSAs and no non-differentiable
quantization step.

- Pretrained protein language models (ProtT5 / ProstT5), fine-tuned with LoRA, feed
  a residual 1D-CNN projection head and the Bio2Token structure decoder.
- Trained on ~75,000 proteins (Cα resolution) with a combined smooth-lDDT, FAPE,
  and MSE loss.
- **~100× faster than ESMFold** (95 CASP15 proteins in ~2 s on an H100), with an
  average lDDT of ~0.64 on CASP15 free-modeling targets.

**Code:** [github.com/BetelgeuseBugFixer/MaPra2025](https://github.com/BetelgeuseBugFixer/MaPra2025)
