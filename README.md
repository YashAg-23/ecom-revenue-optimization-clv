# Customer Lifetime Value (CLV) & Revenue Optimization Project

## Overview
This project focuses on analyzing and predicting **Customer Lifetime Value (CLV)** for an e-commerce business. Using **Python, RFM segmentation, and probabilistic models (BG/NBD + Gamma-Gamma)**, we identify valuable customers, forecast revenue potential, and generate actionable insights for business growth.

---

## Dataset
- **Source:** [Kaggle – Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **About:** Real-world data from a large Brazilian marketplace containing detailed information on orders, payments, customers, reviews, and products.
- **Note:**  
  - Due to GitHub’s 25 MB file size limit, large raw and processed data files (e.g., `orders.csv`) have been excluded.  
  - A **placeholder `data/` folder structure** has been provided to maintain reproducibility.  
  - The dataset can be downloaded from the Kaggle link above to reproduce the complete analysis locally.

---

## Objectives
- Derive customer behavior insights through **RFM segmentation**
- Predict future purchase frequency using the **BG/NBD model**
- Estimate expected average profit using the **Gamma-Gamma model**
- Calculate **6-month CLV** for each customer
- Recommend strategies for **retention, reactivation, and growth**

---

## Key Highlights
| Aspect | Tools / Methods Used |
|:-------|:---------------------|
| **Data Analysis & Cleaning** | Python (pandas, numpy) |
| **Segmentation** | RFM Analysis |
| **Predictive Modeling** | BG/NBD & Gamma-Gamma models (Lifetimes library) |
| **Visualization** | matplotlib, seaborn |
| **CLV Calculation** | 6-month forecasted value |
| **Insights Dashboard** | (Excel dashboard planned — in progress) |

---

## Strategic Recommendations
| Area | Action | Expected Impact |
|:------|:--------|:----------------|
| **Retention** | Focus on “Champions” and “Loyal” segments | Sustainable revenue growth |
| **Reactivation** | Win-back campaigns for “At-Risk” customers | Recover dormant value |
| **Upsell / Cross-sell** | Target “Potential Loyalists” with personalized offers | Increase profitability |
| **Marketing Spend** | Redirect towards high CLV customers | Improved ROI |

---

## Key Models Summary
| Model | Description | Key Parameters |
|:-------|:-------------|:----------------|
| **BG/NBD** | Predicts future transactions | r=0.23, a=1.04, b=1.28 |
| **Gamma-Gamma** | Estimates average monetary value | p=11.21, q=1.18, v=10.91 |

---

## Folder Structure
```
Ecom_Revenue_Optimization_CLV/
│
├── README.md
├── executive_summary.md
│
├── notebooks/
│   └── Revenue_Optimization_Dashboard.ipynb
│
├── outputs/
│   ├── clv_results.csv
│   ├── rfm_df.csv
│   └── segment_summary.csv
│
└── data/
    ├── raw/
    │   └── README.txt  ← placeholder (raw data excluded)
    └── processed/
        └── README.txt  ← placeholder (processed data excluded due to size limits)
```

---

## Tech Stack
- Python  
- pandas, numpy, matplotlib, seaborn  
- lifetimes (BG/NBD + Gamma-Gamma models)  
- Excel (for planned dashboard)  

---

## Executive Summary
Customer Lifetime Value analysis is not just about prediction — it’s about **strategic foresight**.  
This project demonstrates how businesses can **use data to understand customers deeply, retain them smartly, and grow sustainably**.

> “The companies that win long-term are those that understand their customers better than anyone else.”
```


