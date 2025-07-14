# Freemium Token Model Analysis: Are Global Platforms Affordable?

This project analyzes the effectiveness and fairness of token-based freemium models (like Upwork, Lovable, etc.) that give limited free credits to users.  
We evaluate whether these models encourage daily active usage or unintentionally cause drop-offs — especially for users from low-income regions.

---

## Problem Statement

Platforms like **Upwork** and **Lovable** use a **freemium + credit/token model**:

- New users get **limited free tokens** (e.g., connections or interactions)
- Once exhausted, users must **pay to continue** using core features

Many users, especially from developing countries, sign up but drop off after hitting these limits.

> **Key question:**  
Is this model *affordable* and *sustainable* across different income regions?

---

## Project Objectives

1. Analyze **token pricing & usage rules** of global platforms  
2. Collect **real-world income & cost-of-living data** per country  
3. Simulate **user behavior** (free use, upgrade, churn)  
4. Build an **Affordability Index**: can users afford to stay?  
5. Generate **recommendations** for global freemium pricing  

---

## Data Lifecycle

We follow a 7-step data science lifecycle:

1. **Business Understanding** – Define the problem and hypotheses  
2. **Data Collection** – Real-world token pricing + income stats  
3. **Data Preparation** – Clean, transform, and integrate datasets  
4. **EDA** – Visualize user flow, pricing pressure, and country-wise costs  
5. **Modeling** – Simulate churn and engagement patterns  
6. **Evaluation** – Check fairness and friction across regions  
7. **Deployment** – Generate PDF report + publish case study  

---

## Project Structure

```plaintext
freemium-token-analysis-upwork/
│
├── data/                # Real & simulated data (CSV)
│   ├── pricing.csv
│   ├── income.csv
│   └── user_behavior_simulated.csv
│
├── notebooks/           # Jupyter notebooks for EDA, modeling
│   ├── 01_eda.ipynb
│   ├── 02_churn_modeling.ipynb
│   └── 03_affordability_analysis.ipynb
│
├── strategy/            # Notes, UX suggestions, pricing models
│   ├── pricing_comparison.xlsx
│   └── recommendations.md
│
├── reports/             # Visualizations, graphs, PDF report
│   ├── charts/
│   └── freemium_model_analysis.pdf
│
└── README.md            # Project overview

---

## 🌍 Data Sources

| Dataset       | Description                               | Type       | Source/Status       |
|---------------|-------------------------------------------|------------|---------------------|
| `pricing.csv` | Token models and pricing from real apps   | Real       | Manually compiled   |
| `income.csv`  | Country-wise income and cost of living    | Real       | Numbeo, World Bank  |
| `user_behavior_simulated.csv` | Simulated free vs. paid user behavior | Simulated | Built in Python      |

---

## 🧰 Tools We Will Use

- **Python**: pandas, seaborn, matplotlib, sklearn  
- **Jupyter Notebook**: for EDA, modeling, and simulation  
- **Excel / Google Sheets**: for manual entry and pricing matrices  
- **GitHub**: to version control and publish our project  
- **Notion**: to document hypotheses and ideas  
- **LinkedIn**: to publish the final case study for professional exposure

---

## Data Ethics & Assumptions

- This project uses simulated and publicly available data.
- We do not represent or misuse any internal company data.
- Token models are inferred based on user experience and publicly visible pricing.
- Simulated behaviors are designed for analytical purposes only.

---

## Why This Project Matters

Freemium token-based pricing is common in SaaS, freelancer platforms, and AI tools.  
But many users in developing countries experience friction — they run out of credits quickly and can't afford subscriptions.  

> **We aim to answer:**  
> Are these platforms globally inclusive or accidentally exclusive?

By combining real-world income data, platform pricing, and simulated usage patterns, this project provides insights that go beyond dashboards.  
We recommend business strategies that balance monetization with accessibility.

---

## Status

-  **Phase 1: Project Setup** – Completed  
-  **Phase 2: Data Collection** – Ongoing  
-  **Phase 3: EDA & Affordability Analysis**  
-  **Phase 4: User Behavior Simulation & Churn Modeling**  
-  **Phase 5: Reporting, Recommendations, and LinkedIn Case Study**
