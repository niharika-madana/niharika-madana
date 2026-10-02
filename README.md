### Niharika Madana

MS Quantitative Finance candidate at Fordham Gabelli (May 2027). I work on market and counterparty risk, derivatives pricing, and the data and engineering that keep those numbers trustworthy.

Before the MSQF I spent a year in supply chain analytics and operations at an e-commerce grocery business, where I ran production SQL/HDFS data pipelines and KPI monitoring. My undergrad was mechanical engineering with a computational mathematics minor.

**Looking for:** 2027 full-time roles in market risk, counterparty credit risk, quant development, and financial data engineering.

---

#### Projects

**[Agentic Portfolio Construction](https://github.com/niharika-madana/agentic-portfolio-construction)** · Python, Pydantic, WRDS/CRSP · *MSQF capstone, team project*

A five-agent system that sets a client's equity allocation *net of the equity risk they already carry through their career* (human capital). Language models extract and narrate; deterministic code computes and validates.
- **My part:** the Compliance Agent (13 check functions covering Reg BI, FINRA 2111, and SEC robo-adviser guidance; the LLM never decides pass/fail) and the Orchestrator that routes failures back to the responsible agent.
- Ran end to end on nine BLS occupation personas. Portfolio vol falls from 7.5% to 0% as career equity risk rises, and all nine cleared compliance.

**[Score-Driven Pairs Trading](https://github.com/niharika-madana/score-driven-pairs-trading)** · Python

A backtesting engine comparing four Ornstein-Uhlenbeck spread models on cointegrated equity pairs: static MLE, Kalman-filtered mean, and one- and two-factor GAS (score-driven, Student-t) models. Out-of-sample spreads use the training hedge ratio to avoid look-ahead.

**[qflib Pricing Engine](https://github.com/niharika-madana/qflib-pricing-engine)** · C++20, Python bindings · *Advanced C++ for Finance coursework*

A derivatives pricing library: closed-form Black-Scholes, Monte Carlo with antithetic variance reduction, Crank-Nicolson finite-difference PDE for American exercise, and Heston calibration via Levenberg-Marquardt.

---

#### Toolkit

1. **Languages:** Python, C++20, SQL
2. **Quant:** Stochastic calculus, derivatives pricing, time-series econometrics, fixed income, risk management, statistical modelling and machine learning
3. **Engineering:** pytest, Pydantic, CMake
4. **Data:** WRDS (CRSP), FRED, BLS, Fama-French

#### Contact

[LinkedIn](https://www.linkedin.com/in/niharika-madana/) · nm179@fordham.edu
