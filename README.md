# Quantitative Asset Pricing - Project Portfolio

Welcome to my Quantitative Asset Pricing repository! This portfolio showcases my empirical and academic projects focusing on asset pricing theories, financial time-series analysis, and derivative pricing models.

The primary objective of these projects is to bridge the gap between theoretical financial models and real-world market data through rigorous econometric testing and algorithmic implementation.

## Technical Stack & Core Competencies

* **Programming & Databases**: Python (Pandas, NumPy, Statsmodels, SciPy, Matplotlib), R, SQL
* **Financial Econometrics**: Cross-Sectional Regressions (Fama-MacBeth), Time-Series Analysis (GARCH, Rolling Beta), Robust Hypothesis Testing (GRS Test, Newey-West HAC adjustments)
* **Quantitative Models**: Capital Asset Pricing Model (CAPM) Evaluation, Black-Scholes Model, Binomial Tree Pricing
* **Data Engineering**: Efficient processing and cleaning of large-scale financial panel data (Parquet format)

---

## Table of Contents

Click the links below to explore individual project modules:

### [Chapter 1: Empirical Evaluation of CAPM & Fama-MacBeth Regressions](./Empirical-Failure-of-CAPM)

* **Core Content**: Investigated the validity and temporal stability of the unconditional CAPM using historical US equity market data (1983-2015). Implemented the Fama-MacBeth two-pass regression and GRS test to demonstrate the empirical failure of CAPM and the existence of unexplained market Alphas.
* **Main File**: `src/Empirical-Failure-of-CAPM.ipynb`

---

## General Setup & Execution

To explore the codebase locally, you can clone the entire repository and navigate to the specific project directory of interest:

```bash
# 1. Clone the master repository
git clone https://github.com/2002dangquan/Asset-Pricing.git

# 2. Navigate to a specific project (e.g., Chapter 1)
cd Asset-Pricing/Empirical-Failure-of-CAPM

# 3. Install dependencies
pip install -r requirements.txt
