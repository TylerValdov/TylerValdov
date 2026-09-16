# Hi, I'm Tyler 👋

I'm a junior in Computer Science at Virginia Tech. I build full-stack and data-driven projects — from
quantitative trading systems to ML pipelines to security tooling. I'm interested in general SWE, including
but not limited to Cloud Development, AI & Machine Learning, and Full-Stack Web Development.

---

## 🚀 Projects

### [Backtester](https://github.com/TylerValdov/backtester) [Live Link](https://www.strategytester.me)
A quantitative backtesting and live paper-trading platform. FastAPI (Python 3.13) backend + Node 22 frontend, running entirely offline on 16 years of deterministic synthetic OHLCV data until real market data is configured.
- Alpha signal library: momentum (SMA crossover, RSI, MACD, breakouts) and mean reversion (z-score, Bollinger Bands, pairs spreads), plus custom/ML signal hooks
- Event-driven backtest engine with weekly/monthly rebalancing, long-only/long-short/signal-weighted sizing, and FIFO trade matching
- Risk analytics: Sharpe, Sortino, max drawdown, CAGR, rolling Sharpe, alpha/beta vs. SPY
- Slippage modeling (fixed cost + bps + square-root market impact)
- Paper trading over WebSockets, with placeholders for real data providers, brokers, and OAuth

**Stack:** Python, FastAPI, JavaScript/Node

### [Quizinos](https://github.com/TylerValdov/quizinos)
A private, single-user flashcard app for personal studying.
- Create study sets by hand or import from a Quizlet export
- Flashcard drills plus an adaptive Learn mode that escalates from multiple-choice to written recall based on performance
- Firebase (Auth + Firestore) for sync across devices, with local caching for offline use
- Locked down by design — no page or data is reachable without signing in, and there's no public sign-up flow
- Runs entirely on Firebase's free Spark plan; deployed via Vercel

**Stack:** TypeScript, Firebase, Vercel

### [PhishBot](https://github.com/TylerValdov/PhishBot)
A full-stack phishing email analyzer powered by Google's Gemini AI.
- Submit email text and get a 0–100 risk score, a concise summary, and flagged red flags (e.g. suspicious calls to action)
- Stores analysis history in MongoDB, with a view of your last 10 checks
- Chrome extension front end (HTML/CSS/JS + Fetch API) talking to a FastAPI backend
- Containerized with Docker/Docker Compose, deployable to EC2 or any cloud VM

**Stack:** Python, FastAPI, Gemini AI, MongoDB, Docker

---

## 🛠️ Tech I work with
Python · TypeScript/JavaScript · FastAPI · React/Node · Firebase · MongoDB · Docker

<!-- Optional: add GitHub stats/streak cards, e.g.
![Tyler's GitHub stats](https://github-readme-stats.vercel.app/api?username=TylerValdov&show_icons=true&theme=default)
-->
