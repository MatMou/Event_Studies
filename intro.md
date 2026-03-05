# Event Studies in Finance & Economics

**A graduate-level course on event study methodology**

*Mathis Mourey — The Hague University of Applied Sciences*

---

Event studies are one of the most widely used empirical tools in financial economics. From measuring the market impact of earnings announcements to evaluating the effects of regulatory changes, mergers, or macroeconomic news, the event study framework provides a rigorous statistical approach to isolating the causal effect of an event on asset prices.

This course covers the complete pipeline — from the foundational theory through advanced estimation and inference, all the way to replication-ready Python implementations.

## Course Structure

The course is organized into four parts across ten sessions:

**Part I — Foundations** introduces the event study timeline, the concept of abnormal returns, and the market model as the benchmark for normal returns.

**Part II — Statistical Inference** covers both parametric tests (t-tests, patell, BMP) and non-parametric alternatives (rank, sign, generalized sign), including corrections for cross-sectional dependence.

**Part III — Advanced Methods** extends the framework to cross-sectional determinants of abnormal returns, long-horizon methodologies (BHAR vs. CARs, calendar-time portfolios), and special topics including high-frequency data, intraday patterns, and crypto applications.

**Part IV — Capstone** consolidates the toolkit into a full study design walkthrough and real-world case studies.

## How to Use This Book

Each session is a self-contained Jupyter notebook. Code cells use Python with standard libraries (`numpy`, `pandas`, `statsmodels`, `yfinance`). You can:

- **Read** the rendered notebooks directly in this book
- **Run on Binder** — click the 🚀 launch button at the top of any page to open a live session
- **Open in Colab** — for GPU-backed execution where needed
- **Clone the repo** and run locally

```bash
git clone https://github.com/MatMou/Event_Studies.git
cd Event_Studies
pip install jupyter-book numpy pandas statsmodels yfinance matplotlib scipy
jupyter lab
```

## Key References

- MacKinlay, A.C. (1997). Event studies in economics and finance. *Journal of Economic Literature*, 35(1), 13–39.
- Campbell, J.Y., Lo, A.W., & MacKinlay, A.C. (1997). *The Econometrics of Financial Markets*. Princeton University Press.
- Kothari, S.P. & Warner, J.B. (2007). Econometrics of event studies. In *Handbook of Corporate Finance*, Vol. 1.
- Barber, B.M. & Lyon, J.D. (1997). Detecting long-run abnormal stock returns. *Journal of Financial Economics*, 43(3), 341–372.

---

```{note}
This material is part of the [OpenModules](https://matmou.github.io/OpenModules) open courseware project.
Source code and notebooks are available on [GitHub](https://github.com/MatMou/Event_Studies).
```
