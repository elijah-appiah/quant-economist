<div align="center">

# 📈 The Quant Economist's Path

### A two-year, five-track journey from first principles to expert — in R and Python

*Econometrics · Quantitative Finance · DSGE Modeling · Machine Learning · Deep Learning*

<br/>

[![Progress](https://img.shields.io/badge/Progress-Week%201%20%2F%2096-blue?style=for-the-badge)](#-progress-tracker)
[![R](https://img.shields.io/badge/R-4.x-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-project.org/)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/YOUR-USERNAME/the-quant-economists-path?style=for-the-badge&color=gold)](../../stargazers)

<br/>

**[📖 Curriculum](#-the-curriculum)** ·
**[🗂️ Repo Structure](#️-repository-structure)** ·
**[📊 Progress](#-progress-tracker)** ·
**[📚 Books](#-book--resource-index)** ·
**[🚀 Getting Started](#-getting-started)** ·
**[🤝 Contributing](#-contributing)**

</div>

<br/>

> [!NOTE]
> This repository is my public, working record of a self-directed two-year program spanning **five quantitative disciplines**, executed weekly in both **R and Python**. Every notebook, script, and note here is real work product from that schedule — not a tutorial clone. Follow along, fork it, or use the structure for your own path.

---

## 🎯 Why This Exists

Most "learn quant finance" or "learn econometrics" resources teach one discipline in isolation. In practice — in a PhD program, in a research role, on a trading desk — these fields constantly borrow from each other: causal inference leans on machine learning, DSGE models are estimated with the same Kalman filter used in time-series econometrics, and deep learning increasingly shows up in macro forecasting and derivatives pricing.

**The Quant Economist's Path** treats all five as one connected discipline, studied in parallel, one topic per track per week, for 96 weeks — building toward a final capstone that integrates all five.

| | |
|---|---|
| 🧮 **Econometrics** | Cross-section, time series, panel data — micro and macro |
| 💹 **Quantitative Finance** | Stochastic calculus, derivatives pricing, risk, algorithmic trading |
| 🏛️ **DSGE Modeling** | RBC and New Keynesian dynamic stochastic general equilibrium models |
| 🤖 **Machine Learning** | Statistical learning theory, supervised & unsupervised methods |
| 🧠 **Deep Learning** | Neural networks, computer vision, NLP, generative models |

---

## 📖 The Curriculum

<table>
<tr>
<td width="50%" valign="top">

### 🟦 Year 1 — Foundations → Intermediate
**Weeks 1–48**

- **Q1** · Foundations across all five tracks
- **Q2** · Core methods deepen
- **Q3** · Breadth: micro/macro econometrics + finance/DL depth
- **Q4** · Integration and Year‑1 capstones

</td>
<td width="50%" valign="top">

### 🟪 Year 2 — Advanced → Expert
**Weeks 49–96**

- **Q5** · Graduate econometrics + advanced pricing theory
- **Q6** · Algorithmic trading, state-space macro, advanced DL
- **Q7** · Research-level specialization (paper replication)
- **Q8** · Final integrated five-track capstone project

</td>
</tr>
</table>

Each week follows the same rhythm:

```
📘 Book/Resource  →  🎯 One concept  →  💻 One R and/or Python implementation
```

The full week-by-week breakdown — every topic, every book, every coding task — lives in [`schedule/`](schedule/) and is generated from [`schedule/curriculum.json`](schedule/curriculum.json), so it's both human-readable and machine-parseable.

> [!TIP]
> Start at [`schedule/00-overview.md`](schedule/00-overview.md) for the full syllabus, or jump straight to the current week via the [Progress Tracker](#-progress-tracker) below.

---

## 🗂️ Repository Structure

```
the-quant-economists-path/
│
├── 📄 README.md                     ← you are here
├── 📄 LICENSE
├── 📄 CONTRIBUTING.md
│
├── 📁 schedule/                     ← the full 96-week curriculum
│   ├── 00-overview.md               ← syllabus, pacing notes, how to use this repo
│   ├── curriculum.json              ← machine-readable source of truth
│   ├── year-1/
│   │   ├── q1-foundations.md
│   │   ├── q2-core-methods.md
│   │   ├── q3-breadth.md
│   │   └── q4-integration.md
│   └── year-2/
│       ├── q5-advanced-theory.md
│       ├── q6-algo-trading-macro.md
│       ├── q7-specialization.md
│       └── q8-capstone.md
│
├── 📁 econometrics/                 ← Track A
│   ├── 01-cross-section/
│   ├── 02-time-series/
│   ├── 03-panel-data/
│   └── 04-causal-inference/
│
├── 📁 quant-finance/                ← Track B
│   ├── 01-stochastic-calculus/
│   ├── 02-derivatives-pricing/
│   ├── 03-risk-management/
│   └── 04-algorithmic-trading/
│
├── 📁 dsge-models/                  ← Track C
│   ├── 01-rbc-foundations/
│   ├── 02-new-keynesian/
│   ├── 03-estimation/
│   └── 04-policy-analysis/
│
├── 📁 machine-learning/             ← Track D
│   ├── 01-statistical-learning/
│   ├── 02-tree-ensembles/
│   ├── 03-unsupervised/
│   └── 04-causal-ml/
│
├── 📁 deep-learning/                ← Track E
│   ├── 01-neural-network-foundations/
│   ├── 02-computer-vision/
│   ├── 03-sequence-models/
│   └── 04-generative-models/
│
├── 📁 capstones/                    ← one folder per quarter-end + final project
│   ├── q1-capstones/
│   ├── q2-capstones/
│   ├── ⋮
│   └── final-integrated-capstone/   ← Week 96: all five tracks, one system
│
├── 📁 notes/                        ← derivations, reading notes, cheat sheets
│   ├── econometrics/
│   ├── quant-finance/
│   ├── dsge/
│   ├── machine-learning/
│   └── deep-learning/
│
└── 📁 assets/                       ← plots, diagrams, images used in READMEs
```

<details>
<summary><b>📁 Click to see what a typical track subfolder looks like inside</b></summary>
<br/>

Every leaf folder (e.g. `econometrics/02-time-series/`) follows the same convention:

```
02-time-series/
├── README.md              ← what this topic covers, key equations, key takeaways
├── week-13-characteristics.R
├── week-13-characteristics.py
├── week-14-stationarity.R
├── week-14-stationarity.py
├── ⋮
├── data/                   ← small datasets used (or a download script for large ones)
└── figures/                ← saved plots referenced in the README
```

Both an `.R` and a `.py` file exist side by side wherever the week calls for both languages, so the repo doubles as a living **R ↔ Python translation reference**.

</details>

---

## 📊 Progress Tracker

<div align="center">

| Track | Status | Weeks Complete | Progress |
|:---|:---:|:---:|:---|
| 🧮 Econometrics | 🟢 In Progress | 1 / 96 | ![](https://progress-bar.dev/1/?scale=96&width=200&color=babaca&suffix=%20wks) |
| 💹 Quant Finance | 🟢 In Progress | 1 / 96 | ![](https://progress-bar.dev/1/?scale=96&width=200&color=babaca&suffix=%20wks) |
| 🏛️ DSGE Models | 🟢 In Progress | 1 / 96 | ![](https://progress-bar.dev/1/?scale=96&width=200&color=babaca&suffix=%20wks) |
| 🤖 Machine Learning | 🟢 In Progress | 1 / 96 | ![](https://progress-bar.dev/1/?scale=96&width=200&color=babaca&suffix=%20wks) |
| 🧠 Deep Learning | 🟢 In Progress | 1 / 96 | ![](https://progress-bar.dev/1/?scale=96&width=200&color=babaca&suffix=%20wks) |

*Updated weekly. See [`schedule/curriculum.json`](schedule/curriculum.json) `"status"` fields for the machine-readable version.*

</div>

<details>
<summary><b>🏆 Capstone Milestones</b></summary>
<br/>

- [ ] **Week 12** — Q1 Capstones (5 tracks)
- [ ] **Week 24** — Q2 Capstones (5 tracks)
- [ ] **Week 36** — Q3 Capstones (5 tracks)
- [ ] **Week 48** — 🎓 Year 1 Complete
- [ ] **Week 60** — Q5 Capstones (5 tracks)
- [ ] **Week 72** — Q6 Capstones (5 tracks)
- [ ] **Week 84** — Q7 Research Portfolio (two papers × 5 tracks)
- [ ] **Week 96** — 🏆 **Final Integrated Capstone** — a macro-finance early-warning system spanning all five disciplines

</details>

---

## 📚 Book & Resource Index

<details>
<summary><b>🧮 Econometrics</b></summary>
<br/>

| Book | Author(s) | Language |
|---|---|---|
| *Using R / Using Python for Introductory Econometrics* | Florian Heiss | R & Python |
| *Applied Econometrics with R* | Kleiber & Zeileis | R |
| *Time Series Analysis and Its Applications* | Shumway & Stoffer | R |
| *Panel Data Econometrics with R* | Croissant & Millo | R |
| *Econometric Analysis of Cross Section and Panel Data* | Wooldridge | Theory |

</details>

<details>
<summary><b>💹 Quantitative Finance</b></summary>
<br/>

| Book | Author(s) | Language |
|---|---|---|
| *Options, Futures, and Other Derivatives* | John C. Hull | Theory |
| *Stochastic Calculus for Finance I & II* | Steven E. Shreve | Theory |
| *Python for Finance* | Yves Hilpisch | Python |
| *Derivatives Analytics with Python* | Yves Hilpisch | Python |
| *Python for Algorithmic Trading* | Yves Hilpisch | Python |

</details>

<details>
<summary><b>🏛️ DSGE Models</b></summary>
<br/>

| Book / Tool | Author(s) | Language |
|---|---|---|
| *Monetary Policy, Inflation, and the Business Cycle* | Jordi Galí | Theory (MATLAB in original) |
| *Structural Macroeconometrics* | DeJong & Dave | Theory (MATLAB in original) |
| **gEcon** package | Klima, Podemski, et al. | R |
| **dsge** package | CRAN | R |
| **gEconpy** | Jesse Grabowski | Python |

> No major published book teaches DSGE with native R/Python labs — this track pairs canonical MATLAB/Dynare-era theory with actively maintained R and Python solvers instead.

</details>

<details>
<summary><b>🤖 Machine Learning</b></summary>
<br/>

| Book | Author(s) | Language |
|---|---|---|
| *An Introduction to Statistical Learning* (ISLR / ISLP) | James, Witten, Hastie, Tibshirani | R & Python |
| *Hands-On Machine Learning* | Aurélien Géron | Python |
| *The Elements of Statistical Learning* | Hastie, Tibshirani, Friedman | Theory |

</details>

<details>
<summary><b>🧠 Deep Learning</b></summary>
<br/>

| Book | Author(s) | Language |
|---|---|---|
| *Deep Learning with Python* | François Chollet | Python |
| *Deep Learning with R* | Chollet, Kalinowski, Allaire | R |
| *Deep Learning* | Goodfellow, Bengio, Courville | Theory |

</details>

---

## 🚀 Getting Started

<details>
<summary><b>🔧 Environment setup</b></summary>
<br/>

**R**
```bash
# Recommended: renv for reproducible package versions
install.packages("renv")
renv::restore()
```

**Python**
```bash
python -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

**Repo-wide conventions**
- Every script is self-contained and runnable top to bottom
- Random seeds are fixed for reproducibility
- Large datasets are never committed — each `data/` folder has a `download.R` or `download.py` script instead

</details>

<details>
<summary><b>🧭 How to navigate this repo</b></summary>
<br/>

- New here? Start with [`schedule/00-overview.md`](schedule/00-overview.md)
- Want the theory behind a topic? Check `notes/<track>/`
- Want working code for a specific week? Go to `<track>/<topic-folder>/week-NN-*.R` or `.py`
- Want to see the big picture? Every quarter's capstones live in `capstones/`

</details>

---

## 🤝 Contributing

This is primarily a personal learning log, but corrections, alternative implementations, and discussion are genuinely welcome.

- 🐛 **Found an error** in code or an econometric/mathematical claim? Open an issue.
- 💡 **Have a cleaner R or Python implementation** of a given week's topic? PRs welcome — see [`CONTRIBUTING.md`](CONTRIBUTING.md).
- ⭐ **Following a similar path yourself?** Feel free to fork this structure for your own curriculum.

---

## 👤 About

**Elijah** — PhD Candidate in Economics, National Institute of Development Administration (NIDA), Bangkok.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](#)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=flat-square&logo=youtube&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](#)

---

<div align="center">

### ⭐ If this structure is useful to you, consider starring the repo — it helps others discover it too.

*Last updated: Week 1 of 96*

</div>
