# Quantitative Research Portfolio

A curated collection of independent quantitative research exploring financial markets, portfolio analytics, statistical validation, and decision-making under uncertainty.

This repository serves as the public entry point to my research portfolio. It highlights selected projects that demonstrate quantitative reasoning, software development, and rigorous research methodology. Each featured project emphasizes reproducibility, transparent assumptions, and careful validation over attractive conclusions.

> **Research Philosophy**
>
> I build research to challenge ideas rather than confirm them. Well-documented negative results are valuable when they meaningfully reduce uncertainty.

---

# Featured Research

## 📈 V&D Cloud

**Volatility & Dispersion Cloud** is a market-state diagnostic research project inspired by Ichimoku-style regime mapping.

Instead of applying cloud analysis directly to price, the project investigates whether a synthetic market opportunity signal constructed from volatility and dispersion can provide useful descriptive information about market environments.

The research emphasizes:

- hypothesis-driven quantitative research
- statistical validation using multiple robustness checks
- transparent reporting of limitations
- reproducible analysis using public market data

The project intentionally documents both successful findings and hypotheses that did **not** survive validation: of 13 rigorously tested candidate regimes (HAC/Newey-West inference, random-label permutation testing, simple-baseline challenges, and a chronological out-of-sample holdout), only one cleared both robustness bars — a result consistent with pure chance under multiple-comparison correction.

**[View the repository →](https://github.com/Telos-in-the-Void/vd-cloud)**

**Technologies**

- Python
- Pandas
- NumPy
- Statsmodels
- Plotly
- Jupyter Notebook

---

## 🌍 Atlas Observatory

Atlas Observatory extends the V&D research into an interactive visualization environment.

It provides a visual framework for exploring market-state diagnostics through dashboards that combine volatility, dispersion, and derived market-state classifications.

The project focuses on making quantitative research easier to interpret while preserving methodological transparency. Zone labels are explicitly provisional and rule-based — a monitoring instrument, not a trading signal.

**[Open the live dashboard →](https://telos-in-the-void.github.io/vd-cloud/atlas/)** · **[View the notebook →](https://github.com/Telos-in-the-Void/vd-cloud/tree/main/atlas)**

---

## 🎯 Options Positioning Research

A clean-room study of longitudinal option-chain structure: a documented schema, wide-to-long contract normalization, eight engineered positioning/liquidity features, cumulative open-interest terrain, and gap-aware longitudinal charting — validated with a 12-check suite covering both data integrity and the synthetic generator's own shape rules.

Deliberately stops before machine learning. The contribution is engineering, representation, and validation — not prediction, sentiment inference, or trading claims. All option-chain values are synthetic except the underlying's real daily price path.

**[View the repository →](https://github.com/Telos-in-the-Void/options-positioning-research)**

**Technologies**

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Research Interests

Current areas of focus include:

- Market-state diagnostics
- Portfolio analytics
- Statistical validation
- Options analytics
- Quantitative finance
- Risk modeling
- Machine learning for finance
- Research engineering

---

# Technical Stack

### Languages

- Python
- R
- SQL
- VBA

### Libraries

- Pandas
- NumPy
- Statsmodels
- Plotly
- Matplotlib

### Tools

- Git
- Jupyter
- Obsidian
- Notion

---

# Repository Roadmap

The portfolio will continue to expand as projects complete governance review and become suitable for public release.

Planned additions include:

- Statistical validation utilities
- Macro liquidity forecasting
- Portfolio analytics
- Research engineering tools

Projects remain private until they meet documentation, reproducibility, and data-governance standards.

---

# Research Standards

Every published project aims to demonstrate:

- Clear research questions
- Transparent methodology
- Reproducible implementation
- Honest discussion of limitations
- Appropriate validation
- Separation of public and private research artifacts

---

# Contact

If you'd like to discuss quantitative research, portfolio analytics, or financial technology, feel free to connect through GitHub or LinkedIn.
