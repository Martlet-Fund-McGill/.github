# Martlet Fund — Quant Team

**Overview**

The Martlet Fund at McGill is a student-run investment fund that blends rigorous financial research with applied quantitative techniques. This README focuses on the Quant Team — the group responsible for research, data engineering, strategy development, and systematic execution that supports the Fund's investment decision-making.

**Mission**

- **Research:** Develop and validate quantitative investment strategies using robust, reproducible research practices.
- **Infrastructure:** Build reliable data pipelines, backtests, and tooling that enable systematic investing.
- **Education:** Train members in data science, applied finance, and software engineering best practices.

**What the Quant Team Does**

- **Strategy Research:** Explore factor models, alpha signals, and portfolio construction techniques across equities and alternative asset classes.
- **Backtesting & Validation:** Implement realistic backtests with transaction costs, slippage, and risk controls; run walk-forward and out-of-sample validation.
- **Data Engineering:** Acquire, clean, and maintain price, fundamentals, and alternative datasets. Produce documented, versioned datasets for research use.
- **Execution & Risk Tools:** Prototype execution algorithms, simulate market impact, and build risk analytics (exposures, drawdowns, turnover).
- **Productionization:** Move validated strategies from notebooks into repeatable, automated pipelines for live monitoring and reporting.

**Typical Projects & Research Areas**

- Equity factor research (value, momentum, quality, low-volatility, etc.)
- Event-driven and earnings-quality signals
- Pairs trading and statistical arbitrage
- Portfolio optimization and risk parity implementations
- Alternative data (sentiment, web trends) for alpha augmentation

**Tech Stack & Tools**

- **Languages:** `Python` (primary), `R` (analytics), `SQL` (data queries)
- **Libraries:** `pandas`, `numpy`, `scipy`, `statsmodels`, `scikit-learn`, `cvxpy`, `zipline`/`bt`/`backtrader` (for backtests)
- **Data & Storage:** CSV/Parquet datasets, SQL databases, cloud buckets for large data
- **Infrastructure:** `Airflow`/cron for pipelines, `Docker` for reproducible environments, GitHub for version control
- **Collaboration:** Notebooks (`Jupyter`/`Colab`), GitHub Issues & PRs, Slack/Discord for communication

**How We Work**

- Research typically begins as a small hypothesis documented in a notebook with data sources, expected tests, and performance metrics.
- Backtests are built with clear assumptions and realistic cost modelling; results are reproducible and versioned.
- Code reviews and PRs ensure research is production-ready before being scheduled for automated runs.
- Weekly syncs and regular brown-bag talks help spread knowledge and review new ideas.

**Getting Involved / How to Join**

- Roles: Quant Researcher, Data Engineer, Backtester, Quant Developer, Risk Analyst.
- Typical onboarding: coding assessment (Python + data exercise), interview on quantitative concepts, small starter project or pairing exercise.
- To apply: reach out to the Fund's recruitment contact (see Contact below) or submit a short research idea / resume via the Fund's application channel.

**Contribution Guidelines**

- Use feature branches and open PRs for all changes. Target small, focused PRs.
- Document datasets, data transformations, and assumptions in code and notebooks.
- Include unit or integration tests for key data transforms and strategy logic where possible.
- Use clear commit messages and reference issues or research notes in PR descriptions.

**Code of Conduct**

- Maintain a collaborative, respectful environment. Academic integrity and proper citation of external research are required.

**Quick Start (for new contributors)**

1. Clone the repository: `git clone https://github.com/Martlet-Fund-McGill/.github.git`
2. Create a branch: `git checkout -b feat/your-name-idea`
3. Set up a Python environment (recommended):

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

4. Run tests (if present): `pytest`
5. Open a draft PR describing your research or engineering change.

**Data & Compliance Notes**

- Use licensed or publicly-available datasets only. Keep proprietary provider credentials out of the repository (use environment variables or secret stores).
- Ensure research and trading simulations comply with the Fund's risk and compliance policies.

**Contact & Next Steps**

- **General inquiries / recruitment:** contact the Martlet Fund officers via the official website: `https://www.martletfundmcgill.ca/`.
- **Quant Team lead / email:** (add team lead contact here or link to the Fund’s contact form)

If you'd like, I can convert a specific quant project on the site into a starter repo template (data + notebook + backtest harness). Want me to scaffold that now?
