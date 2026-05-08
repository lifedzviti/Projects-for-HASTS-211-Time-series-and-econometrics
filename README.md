# 📊 Financial Econometrics —  Projects

**Author:** Life Dzviti
**Course:** Financial Econometrics (HASTS 211)

---

## Projects

### Project 1 · Best-Practices Handbook

**Dataset:** AAPL daily prices (2018–2025)

A Jupyter notebook serving as a best-practices handbook for quants on a derivatives desk. The notebook addresses four key challenges in time series modeling:

| Challenge | Focus |
|-----------|-------|
| **Multicollinearity** | Detection and mitigation strategies |
| **Skewness** | Impact on return distributions and model assumptions |
| **Sensitivity to Outliers** | Diagnosis and robust estimation approaches |
| **Overfitting** | Cross-validation and model selection techniques |

Each challenge follows a structured **7-D framework**:

```
Definition → Description → Demonstration → Diagram → Diagnosis → Damage → Directions
```

**Data Source:** Apple Inc. (AAPL) via Yahoo Finance · `yfinance` API · No local files required

---

### Project 3 · Time Series Modeling — Regime Changes

**Datasets:** AAPL via Yahoo Finance · `yfinance` API · No local files required

---

## Getting Started

All notebooks download data automatically at runtime — no CSV files need to be uploaded or manually prepared.

```bash
# Install dependencies
pip install yfinance pandas numpy matplotlib seaborn statsmodels scipy arch

# Launch Jupyter
jupyter notebook
```

> **Note:** Run cells sequentially from top to bottom. The data download cell in each notebook must execute before any modelling or visualisation cells.

---

