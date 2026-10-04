# Hi, I'm Andreas 👋

**AI / ML Engineer** · Athens, Greece

I build ML systems end to end, from data ingestion and leak-safe feature pipelines to served models and the product around them. I care more about honest evaluation than impressive-looking numbers.

## Featured project

### [NBA Predictor](https://github.com/achron23/nba-predictor): walk-forward ML model benchmarked against the betting market
- Solo-built pipeline: 286k odds snapshots, 216k box scores, 17 scheduled jobs
- Walk-forward validated model (ROC-AUC 0.765 on the 2025 holdout), **benchmarked against the betting market itself**
- Found and fixed an odds-timing flaw that had inflated an earlier backtest, then retired the inflated result
- FastAPI serving; shipped a Stripe → Telegram subscription flow (product now retired)

## What I work with

**ML / data:** Python, pandas, scikit-learn, walk-forward validation, calibration, feature engineering
**Backend:** FastAPI, SQLite, REST / webhooks, Stripe, Telegram Bot API
**Tooling:** uv, pytest, git

**Next:** an LLM "pick analyst" agent with LangGraph, LangChain and LlamaIndex. The LLM will only narrate tool outputs, enforced by a numeric guard and an eval harness.

## Contact
[LinkedIn](https://www.linkedin.com/in/andreas-chroneas-7838b7341) · andreasxroneas@gmail.com
