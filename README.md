# The Credit Dilemma: Evaluating Token-Based Freemium Models in Platforms like Upwork

## Business Problem

Freemium platforms like **Upwork** offer limited usage through free credits or tokens (called "Connects") that users must spend to apply for projects. While this model helps monetize high-intent users, it may unintentionally push away users in emerging markets due to:

- Token exhaustion without results
- Low affordability of paid plans
- Drop in daily active users (DAU)
- Frustration among early users who never convert

This raises a critical question:
> Does the token-based freemium model drive sustainable global user growth, or does it lead to silent user churn?

---

## Project Objective

To perform an end-to-end, data-driven evaluation of token-based freemium models — with **Upwork, Lovable, and Figma** as references — using real-world pricing and simulated behavioral data.

We will simulate user behavior, measure churn, analyze affordability across five countries, and offer business recommendations.

---

## Key Questions We Will Answer

1. How does token usage affect user churn and upgrade behavior?
2. Are users from different countries equally likely to upgrade, or are some priced out?
3. Does limiting user activity through tokens lower DAU over time?
4. Is the pricing model globally affordable compared to local incomes?
5. What strategies can improve retention and conversions without hurting access?

---

## Target Users of This Research

- Product managers of freemium apps
- Startup founders launching credit-based services
- Data analysts studying growth vs. monetization tradeoffs
- Anyone trying to make access fair across geographies

---

## Project Lifecycle Approach

This project follows a full data lifecycle:

| Phase | Step |
|-------|------|
| 1️⃣ Business Understanding | Define the user and business problem clearly |
| 2️⃣ Data Collection | Real pricing + incomes + simulated behavior |
| 3️⃣ Data Cleaning | Format, merge, enrich |
| 4️⃣ EDA | Explore user journeys, churn triggers, DAU trends |
| 5️⃣ Modeling | Predict churn/upgrade likelihood |
| 6️⃣ Strategy | Recommend pricing or credit changes |
| 7️⃣ Reporting | Visual insights, GitHub, PDF, Notion, LinkedIn post |

---

## Project Structure (Planned)

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

## 🛠 Tools We Will Use

- **Python** (pandas, matplotlib, seaborn, sklearn)
- **Excel or Google Sheets** (pricing & income matrix)
- **Notion** (to plan and document reasoning)
- **GitHub** (to publish code + report)
- **LinkedIn** (for final case study post)

---

## 🧾 Data Ethics & Assumptions

- This project uses dummy user behavior data to simulate patterns.
- Income data and pricing are sourced from official/statistical sources where possible.
- We assume Upwork's model as a base example and do not claim insider access or proprietary metrics.

---

## 📣 Why This Project Matters

Millions of users from developing countries sign up for global platforms — but are they being retained?  
This project goes beyond basic dashboards. It digs into **real economic friction**, shows **data-backed user behavior**, and offers **business recommendations** that are globally conscious.

---

