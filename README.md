<div align="center">

<a href="https://github.com/wenje-ma">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=2800&pause=1000&color=00875F&center=true&vCenter=true&width=800&height=90&lines=%3E+Hi%2C+I%27m+Wenje+Ma+%F0%9F%91%8B;%3E+Mathematics+%26+Statistics+%40+BIT;%3E+Design+of+Experiments;%3E+Space-filling+Designs;%3E+Multi-fidelity+Bayesian+Optimization;%3E+Daydream+%C2%B7+Sunsets+%C2%B7+Stargazing" alt="Typing SVG" />
</a>

<span style="color:#00875F;font-weight:bold">✦ Daydream · Sunsets · Stargazing ✦</span>

</div>

### ⚡ About Me

🎓 Undergraduate at **Beijing Institute of Technology**

> Qiang-Ji Program in Mathematics & Applied Mathematics · School of Mathematics and Statistics · Teli Academy

🔬 I hunt for **maximum information from minimum experiments** — statistics meets computation:

- 🎯 Design of Experiments (DoE)
- 🧊 Space-filling designs for computer experiments (MaxPro, maximin, LHD, uniform)
- 🧠 Bayesian optimization
- 🔒 Constrained black-box optimization
- 🔁 Multi-fidelity optimization (high- & low-fidelity surrogates, Co-Kriging / KOH)
- 🧭 Feasible-boundary & level-set learning under expensive constraints
- 🧪 Gaussian process regression, EBLUP & conjugate Bayesian inference

<div align="center">

<img src="https://img.shields.io/badge/Design_of_Experiments-00C896?style=for-the-badge&logo=target&logoColor=white" alt="DoE"/>
<img src="https://img.shields.io/badge/Space--filling_Designs-00A878?style=for-the-badge&logo=diagramsdotnet&logoColor=white" alt="space-filling"/>
<img src="https://img.shields.io/badge/Bayesian_Optimization-00875F?style=for-the-badge&logo=pytorch&logoColor=white" alt="bayesopt"/>
<img src="https://img.shields.io/badge/Multi--fidelity_Optimization-008F6B?style=for-the-badge&logo=pytorch&logoColor=white" alt="multifidelity"/>
<img src="https://img.shields.io/badge/Constrained_Black--box-006E4C?style=for-the-badge&logo=target&logoColor=white" alt="constrained"/>

</div>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wenje-ma/wenje-ma/output/github-contribution-grid-snake-dark.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/wenje-ma/wenje-ma/output/github-contribution-grid-snake.svg" />
</picture>

</div>

### 🚀 Research & Featured Projects

<div align="center">

<a href="https://github.com/wenje-ma/singapore">
  <img src="https://img.shields.io/badge/singapore-00C896?style=for-the-badge&logo=bookstack&logoColor=white" alt="singapore"/>
  <img src="https://img.shields.io/badge/Status-Research_Project-00A878?style=for-the-badge&logo=verified&logoColor=white" alt="Research Project"/>
</a>

**Bayesian Optimization Based on Multi-Fidelity Data** · *Wenje Ma, advisor [Dianpeng Wang](https://github.com/wdp708)* · BIT · 2024

</div>

A complete, ablated pipeline for **multi-fidelity Bayesian optimization** — optimizing an expensive black-box when a cheap low-fidelity simulator (systematic bias) and an accurate but costly high-fidelity simulator are both available, under an extremely small budget of **15 high-fidelity equivalents**.

- **Pipeline M1:** `Maximum projection design → Sequential design → Nested design → Expected improvement`, with three control ablations **M0 / S1 / S2** to attribute each component's contribution.
- **Key findings** (1/2/4/8-D test suite: Joseph 1-D, Branin, additive 4-factor, borehole):
  - **Fusion (nested design) is the decisive component** — in 1-D it turns failure into feasibility and reaches the global optimum; in 2-D it approaches the Branin optimum; its value decays with dimension and it fails in 8-D (curse of dimensionality inside the multi-fidelity framework).
  - **Screening never contributes** — the low↔high fidelity bias makes factor-importance ranking unreliable.
  - Under the same budget, a few high-fidelity points **with** fusion far outperform many high-fidelity points alone.
- Fully reproducible: R implementation (`maxpro_design.R`, `nested_design.R`, `fit_KOH.R` / `predict_KOH.R`, `EI.R`, `project.R`, calibration & ablation runners), cached `.RData`, SVG/PDF figures, LaTeX report, and bilingual reports (`report_en.md` / `report_cn.md`).

---

### 📚 Learning & Reading

<div align="center">

<a href="https://github.com/wenje-ma/ED4DSE">
  <img src="https://img.shields.io/badge/ED4DSE-00C896?style=for-the-badge&logo=bookstack&logoColor=white" alt="ED4DSE"/>
  <img src="https://img.shields.io/badge/Status-Completed-00A878?style=for-the-badge&logo=verified&logoColor=white" alt="Completed"/>
</a>

**Experimental Design for Data Science and Engineering** · *V. Roshan Joseph (Georgia Tech)* · Chapman & Hall/CRC · 2026 · ✅ Finished

</div>

Read the whole book cover to cover. The repo holds **memory-indexed notes**, one set of **runnable R scripts per chapter** (section-level, e.g. `4.1.R`–`4.27.R`), **figures** (PDF + SVG for every worked example), **three companion CRAN packages** (`mined`, `support`, `SFDesign`), and a **compiled `ED4DSE.pdf`** — all in [wenje-ma/ED4DSE](https://github.com/wenje-ma/ED4DSE).

| # | Chapter | What I took away |
|---|---|---|
| 1 | Experiments | response surfaces, simulation vs. physical experiments |
| 2 | Modeling Techniques | Kriging & Gaussian process regression |
| 3 | Model-based Designs | prediction-based, maximum entropy designs |
| 4 | Space-filling Designs | MaxPro, minimum energy, LHD |
| 5 | Representative Points | uniform designs, support points, uncertainty propagation |
| 6 | Screening Designs | sensitivity analysis, Morris, MOFAT |
| 7 | Sequential Designs | emulation, Bayesian optimization, inverse designs |
| 8 | Fractional Factorial Designs | two-level & Bayesian-inspired designs |
| 9 | Model Calibration | nonlinear optimal designs, robust design |
| 10 | Data Subsampling | support-point subsampling, data twins |
| 11 | Data Analysis | factor selection, twin Gaussian processes |

---

<div align="center">

<a href="https://github.com/wenje-ma/DACE">
  <img src="https://img.shields.io/badge/DACE-006E4C?style=for-the-badge&logo=bookstack&logoColor=white" alt="DACE"/>
  <img src="https://img.shields.io/badge/Status-Core_Reading-00A878?style=for-the-badge&logo=verified&logoColor=white" alt="Core Reading"/>
</a>

**The Design and Analysis of Computer Experiments** · *T. J. Santner, B. J. Williams, W. I. Notz* · Springer · 2nd ed. · 🔬 Reading the must-have core

</div>

Reading exactly what my thesis must have — GP posterior derivation, Bayesian inference, and the three pillars of my direction (constrained BO, feasible-boundary learning, multi-fidelity). Current notes (in `notes.md`, compiled to `DACE.pdf`) cover the GP foundation:

| Chapter | What I'm reading it for |
|---|---|
| Ch. 2 §2.2 · GP Models | definition & correlation functions — surrogate foundation |
| Ch. 3 §3.2–3.3 · EBLUP | posterior mean/variance derivation — the core skill |
| Ch. 6 §6.3.4 · EI | expected improvement |

---

### 🧰 Utilities & Tools

<div align="center">

<a href="https://github.com/wenje-ma/codes">
  <img src="https://img.shields.io/badge/codes-008F6B?style=for-the-badge&logo=python&logoColor=white" alt="codes"/>
  <img src="https://img.shields.io/badge/Python_3-00875F?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
</a>

**Markdown & PDF utility scripts** · Python 3 + `tkinter` file dialogs

</div>

A small collection of daily-life scripts for processing Markdown and PDF files (each opens a native dialog to pick files or a whole folder, and recursively processes matches):

| Script | What it does |
|---|---|
| `leftright.py` | auto-adds `\left`/`\right` to bare brackets/braces/pipes in `$…$` math |
| `md_merge.py` | concatenates selected Markdown files into one `document.md` |
| `pdf_OCR.py` | OCRs scanned PDFs into a searchable text layer (`_ocr.pdf`) |
| `pdf_to_svg.py` | converts every PDF page to SVG via `pdf2svg` |
| `pdf_to_txt.py` | extracts text from PDF pages into sibling `.txt` files |
| `md_to_pdf.exe` | bundled Markdown→PDF converter |

### 🛠 Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/R-00C896?style=for-the-badge&logo=r&logoColor=white" alt="R"/>
<img src="https://img.shields.io/badge/Rcpp-00A878?style=for-the-badge&logo=r&logoColor=white" alt="Rcpp"/>
<img src="https://img.shields.io/badge/Python-00875F?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Tkinter-007A55?style=for-the-badge&logo=python&logoColor=white" alt="Tkinter"/>
<img src="https://img.shields.io/badge/LaTeX-00A878?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX"/>
<img src="https://img.shields.io/badge/Beamer_(Metropolis)-008F6B?style=for-the-badge&logo=latex&logoColor=white" alt="Beamer"/>
<img src="https://img.shields.io/badge/Quarto-008F6B?style=for-the-badge&logo=quarto&logoColor=white" alt="Quarto"/>
<img src="https://img.shields.io/badge/R_Markdown-00875F?style=for-the-badge&logo=r&logoColor=white" alt="R Markdown"/>
<img src="https://img.shields.io/badge/Jupyter-007A55?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
<img src="https://img.shields.io/badge/Git-006E4C?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/Markdown-00875F?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown"/>

</div>

<sub>R is my research language (designs, GP/KOH surrogates, BO pipelines, with `Rcpp` C++ where speed matters); Python covers scripting & utilities; LaTeX/Beamer/Markdown handle all notes and talks — including a personal copy of the **Metropolis** Beamer theme (see [wenje-ma/mtheme](https://github.com/wenje-ma/mtheme)).</sub>

### 📫 Let's Connect

<div align="center">

<a href="mailto:wenjema6@gmail.com">
  <img src="https://img.shields.io/badge/Email-wenjema6%40gmail.com-00C896?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

<a href="./WenjeMaths.png">
  <img src="https://img.shields.io/badge/WeChat_%E5%85%AC%E4%BC%97%E5%8F%B7-00A878?style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat"/>
</a>

</div>

<div align="center">

<sub>© 2026 Wenje Ma · Built with a little ☕ and a lot of 🧪</sub>

</div>
