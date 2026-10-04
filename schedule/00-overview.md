# 📖 Syllabus & How to Use This Repository

> Full curriculum origin: 96 weeks, five parallel tracks, two years. This file is the entry point — read this first.

## Structure at a Glance

| Year | Weeks | Focus |
|---|---|---|
| Year 1 | 1–48 | Foundations → solid intermediate competence, all five tracks |
| Year 2 | 49–96 | Graduate theory → research-level specialization → final integrated capstone |

Each year is split into four 12-week quarters. Every quarter's last week is a **capstone week**: no new material, just consolidation of the preceding 11 weeks into one project per track.

## The Five Tracks

| Code | Track | Folder |
|---|---|---|
| A | Econometrics | [`/econometrics`](../econometrics) |
| B | Quantitative Finance | [`/quant-finance`](../quant-finance) |
| C | DSGE Models | [`/dsge-models`](../dsge-models) |
| D | Machine Learning | [`/machine-learning`](../machine-learning) |
| E | Deep Learning | [`/deep-learning`](../deep-learning) |

## Pacing

Designed for ~8–12 focused hours per week per track (40–60 hrs/week total) alongside other commitments such as doctoral coursework or research. To slow the pace without changing structure, treat every **two calendar weeks** as one program week.

## A Note on DSGE

No major published book teaches DSGE with native R or Python labs the way the time-series or ML tracks have. The canonical texts (Galí; DeJong & Dave) ship MATLAB/Dynare code. This track keeps the theory from those books but executes every model in R (`gEcon`, `dsge` packages) or Python (`gEconpy`) instead. Dynare/MATLAB is used exactly once (Week 59) as a deliberate, documented exception — reading a published large-scale model file, not writing new code in it.

## Quarter Index

- [Q1 — Foundations (Weeks 1–12)](year-1/q1-foundations.md)
- [Q2 — Core Methods Deepen (Weeks 13–24)](year-1/q2-core-methods.md)
- [Q3 — Breadth (Weeks 25–36)](year-1/q3-breadth.md)
- [Q4 — Integration (Weeks 37–48)](year-1/q4-integration.md)
- [Q5 — Advanced Theory (Weeks 49–60)](year-2/q5-advanced-theory.md)
- [Q6 — Algo Trading & State-Space Macro (Weeks 61–72)](year-2/q6-algo-trading-macro.md)
- [Q7 — Research Specialization (Weeks 73–84)](year-2/q7-specialization.md)
- [Q8 — Final Capstone (Weeks 85–96)](year-2/q8-capstone.md)

## Source of Truth

[`curriculum.json`](curriculum.json) holds the machine-readable version of every week, topic, book, and task — the markdown quarter files are generated from it. If you script anything against this repo (progress dashboards, a personal fork, etc.), read from the JSON.
