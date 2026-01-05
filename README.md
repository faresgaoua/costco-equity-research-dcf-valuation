# Equity Research: Costco Wholesale Corp (COST) Valuation

## Project Overview
This project presents a comprehensive fundamental valuation of **Costco Wholesale Corp (COST)**. [cite_start]It utilizes a **3-stage Discounted Free Cash Flow to Firm (FCFF)** model to determine the company's intrinsic value, complemented by a statistical price forecasting analysis[cite: 42, 43].

## Financial Valuation & Model Inputs
The valuation is built on detailed adjustments to financial statements and industry-specific risk metrics:
* [cite_start]**Intrinsic Value:** The model identifies a **28.1% intrinsic undervaluation** compared to the market price[cite: 43].
* [cite_start]**Adjusted WACC:** Calculated at **6.07%**, specifically adjusted by capitalizing operating leases to reflect Costco's true leverage[cite: 44].
* [cite_start]**Bottom-up Beta:** Derived from industry peer samples to isolate the pure-play risk of the retail and warehouse club sector[cite: 44].
* **Terminal Growth Rate ($g$):** Set at **5.07%** based on stable industry expectations.

## Quantitative Analysis & Sensitivity
Beyond the base case DCF, this project incorporates advanced financial techniques to stress-test the valuation:
* [cite_start]**Geometric Brownian Motion (GBM):** Implemented a statistical stock price forecast to compare fundamental value with market volatility[cite: 45].
    * **Annual Drift ($\mu$):** 18.5%.
    * **Annual Volatility ($\sigma$):** 22.9%.
* [cite_start]**Sensitivity Analysis:** A comprehensive matrix evaluating the impact of varying **WACC vs. Terminal Growth** rates on the final share price[cite: 45].
* **Operating Leverage:** Analysis of fixed vs. variable cost structures and their impact on profitability margins.

## Repository Structure
* **📂 models/**: Detailed Excel DCF model including FCFF projections, WACC adjustments, and Beta calculations.
* **📂 reports/**: Full Investment Decisions Project written report (PDF).
* **📂 data/**: Supporting datasets including industry ROE, market concentration, and membership sample data.

---
[cite_start]*Project conducted at the John Molson School of Business (JMSB)[cite: 11, 42].*
