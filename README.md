# Wenje Ma

Undergraduate at **Beijing Institute of Technology (BIT)**, School of Mathematics and Statistics & Teli Academy — **Mathematics and Applied Mathematics, Qiang-Ji (Strong Foundation) Program**.

My research objective is to extract the maximum information from a minimum number of experiments, at the intersection of statistics and computation.

## Research Interests

- Design of Experiments (DoE)
- Space-filling designs for computer experiments (MaxPro, maximin, Latin hypercube, and uniform designs)
- Bayesian optimization
- Constrained black-box optimization
- Multi-fidelity optimization (low/high-fidelity surrogates, Co-Kriging / KOH)
- Feasible-region boundary and level-set learning under expensive constraints
- Gaussian process regression, EBLUP, and conjugate Bayesian inference

<div align="center">

![](https://img.shields.io/badge/Design_of_Experiments-006E4C?style=flat-square) ![](https://img.shields.io/badge/Space_filling_Designs-00875F?style=flat-square) ![](https://img.shields.io/badge/Bayesian_Optimization-00A86B?style=flat-square) ![](https://img.shields.io/badge/Multi_fidelity_Optimization-00C896?style=flat-square) ![](https://img.shields.io/badge/Constrained_Black_box-00E5A0?style=flat-square)

</div>

---

## Featured Projects

### [singapore](https://github.com/wenje-ma/singapore) — Multi-Fidelity Bayesian Optimization `Research Project`

*Bayesian Optimization Based on Multi-Fidelity Data* (advisor: [Dianpeng Wang](https://github.com/wdp708), BIT, 2024). An ablatable R pipeline — MaxPro design, sequential design, nested (multi-fidelity) design, and expected improvement — for optimizing expensive black-box functions under a 15-evaluation high-fidelity-equivalent budget, with KOH fusion and M0/S1/S2 ablation controls. The key finding is that **fusion is the decisive component**: screening never helped, and a few fused high-fidelity points outperform many unfused ones.

### [ed4dse](https://github.com/wenje-ma/ed4dse) — Experimental Design for Data Science and Engineering `Completed`

A complete computational reproduction of **V. Roshan Joseph's** textbook (Chapman & Hall/CRC, 2026): 79 runnable R scripts covering all 11 chapters (kriging, space-filling designs, support points, screening, sequential design, calibration, data subsampling), every figure in PDF + SVG, cached results, and three locally maintained companion packages (SFDesign, mined, support).

### [dace](https://github.com/wenje-ma/dace) — The Design and Analysis of Computer Experiments `Core Reading`

Close-reading notes with full derivations for **Santner–Williams–Notz** (Springer, 2nd ed.): GP models (§2.2), BLUP/EBLUP (§3.2–3.3), and expected improvement (§6.3.4) — the theory my thesis builds on.

---

## All Public Repositories

### University course notes — pure mathematics

Bilingual (Chinese/English) lecture notes with fully worked weekly homework, written in Markdown + LaTeX. All follow the same format: a single `notes.md` of bold-tagged definitions and theorems, plus `homework/weekN.md` with problems and complete solutions.

| Repository | Subject | Scale |
|---|---|---|
| [mathematical-analysis](https://github.com/wenje-ma/mathematical-analysis) | Mathematical analysis (real numbers → Fourier series) | 55 sections · 36 weeks |
| [advenced-algebra](https://github.com/wenje-ma/advenced-algebra) | Advanced (linear) algebra, following Qiu Weisheng | 8 chapters · 42 weeks |
| [abstract-algebra](https://github.com/wenje-ma/abstract-algebra) | Abstract algebra, following Deng & Zhu | 10 chapters · 26 weeks |
| [complex-analysis](https://github.com/wenje-ma/complex-analysis) | Complex analysis (Cauchy → Picard) | 22 sections · 25 weeks |
| [real-analysis](https://github.com/wenje-ma/real-analysis) | Measure theory, following Zhang Xicheng & Folland | 11 chapters · 12 weeks |
| [topology](https://github.com/wenje-ma/topology) | Point-set topology, following McMullen (Harvard 131) | §2–§7, §11 · 22 weeks |
| [ordinary-differential-equations](https://github.com/wenje-ma/ordinary-differential-equations) | ODEs, textbook-numbered sections | 30 sections · 30 weeks |
| [differential-geometry](https://github.com/wenje-ma/differential-geometry) | Differential geometry | notes + readings |
| [functional-analysis](https://github.com/wenje-ma/functional-analysis) | Functional analysis | reading notes |
| [partial-differential-equations](https://github.com/wenje-ma/partial-differential-equations) | Partial differential equations | notes + readings |

### University course notes — statistics & computing

| Repository | Subject | Scale |
|---|---|---|
| [probability](https://github.com/wenje-ma/probability) | Measure-theoretic probability, following Durrett | 10 chapters · 14 weeks |
| [mathematical-statistics](https://github.com/wenje-ma/mathematical-statistics) | Estimation & hypothesis testing (BIT textbook) | 8 chapters · 18 weeks |
| [numerical-calculation-methods](https://github.com/wenje-ma/numerical-calculation-methods) | Numerical analysis (direct/iterative methods, interpolation, quadrature) | 8 chapters · 8 weeks |

### K-12 mathematics — the full PEP curriculum

Every week of China's People's Education Press mathematics curriculum, formalized into definition-first notes with fully solved exercises, R-generated SVG/PDF figures, and complete English translations.

| Repository | Curriculum | Scale |
|---|---|---|
| [primary-mathematics](https://github.com/wenje-ma/primary-mathematics) | Elementary, grades 1–6 (12 volumes) | 105 weeks · 22 figures |
| [junior-mathematics](https://github.com/wenje-ma/junior-mathematics) | Junior-high, grades 7–9 (6 volumes) | 175 weeks · 205 figures |
| [senior-mathematics](https://github.com/wenje-ma/senior-mathematics) | Senior-high, PEP A 2019 (5 volumes) | 95 weeks · 340 figures |

### Tools & misc

| Repository | What it is |
|---|---|
| [wenje-codes](https://github.com/wenje-ma/wenje-codes) | Tkinter-driven Python utilities for Markdown/PDF: `\left\right` fixing, merging, OCR, PDF splitting, text extraction, md→pdf |
| [wenjemaths](https://github.com/wenje-ma/wenjemaths) | Math tutorials & walkthroughs (work in progress) |
| [metropolis](https://github.com/wenje-ma/metropolis) | Customized fork of the Metropolis Beamer theme — Quarto demo + CJK support |

---

## Tech Stack

<div align="center">

![](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) ![](https://img.shields.io/badge/Rcpp-00427D?style=flat-square&logo=cplusplus&logoColor=white) ![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black) ![](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white) ![](https://img.shields.io/badge/Quarto-39729E?style=flat-square&logo=quarto&logoColor=white) ![](https://img.shields.io/badge/R_Markdown-75AADB?style=flat-square&logo=rstudioide&logoColor=white) ![](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

</div>

**R** is my research language — designs, GP/KOH surrogates, BO pipelines, with Rcpp C++ where performance matters. **Python** handles scripting and tooling. **LaTeX/Beamer/Markdown** carries the notes and decks.

---

<p align="center"><sub>© 2026 Wenje Ma</sub></p>
