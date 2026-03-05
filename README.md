# Event Studies in Finance & Economics

[![Deploy Jupyter Book](https://github.com/MatMou/Event_Studies/actions/workflows/deploy.yml/badge.svg)](https://github.com/MatMou/Event_Studies/actions/workflows/deploy.yml)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://matmou.github.io/Event_Studies)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Live site:** [https://matmou.github.io/Event_Studies](https://matmou.github.io/Event_Studies)

A graduate-level Jupyter Book course on event study methodology in finance and economics. Covers the full pipeline from theoretical foundations through Python implementation, parametric and non-parametric inference, long-horizon methods, and real-world case studies.

## Course Sessions

| # | Session | Topics |
|---|---------|--------|
| 1 | Foundations of Event Studies | Timeline, abnormal returns, EMH connection |
| 2 | Market Model & Normal Returns | OLS estimation, CAPM benchmark |
| 3 | Measuring Abnormal Returns | AR, CAR, CAAR aggregation |
| 4 | Parametric Inference | t-tests, Patell, BMP, cross-sectional dependence |
| 5 | Non-Parametric Inference | Rank, sign, generalized sign tests |
| 6 | Cross-Sectional Analysis | Determinants of abnormal returns, Fama-MacBeth |
| 7 | Long-Horizon Event Studies | BHAR vs. CAR, calendar-time portfolios, DGTW |
| 8 | Extensions & Special Topics | Intraday, HFT, crypto, M&A, earnings |
| 9 | Design & Implementation | Full study design walkthrough |
| 10 | Capstone Case Studies | End-to-end replications |

## Repository Structure

```
Event_Studies/
├── _config.yml              # Jupyter Book configuration
├── _toc.yml                 # Table of contents
├── intro.md                 # Landing page
├── requirements.txt         # Python dependencies
├── .github/
│   └── workflows/
│       └── deploy.yml       # GitHub Actions → GitHub Pages
└── sessions/
    ├── session_01_foundations_of_event_studies.ipynb
    ├── session_02_market_model_normal_returns.ipynb
    ├── ...
    └── session_10_capstone_case_studies.ipynb
```

## Local Build

```bash
git clone https://github.com/MatMou/Event_Studies.git
cd Event_Studies
pip install jupyter-book
jupyter-book build .
# Open _build/html/index.html in your browser
```

## GitHub Pages Setup (one-time)

1. Go to **Settings → Pages** in this repository
2. Under *Source*, select **GitHub Actions**
3. Push to `main` — the workflow builds and deploys automatically

## Part of OpenModules

This course is part of the [OpenModules](https://matmou.github.io/OpenModules) open courseware initiative at The Hague University of Applied Sciences.

## License

MIT © 2026 Mathis Mourey
