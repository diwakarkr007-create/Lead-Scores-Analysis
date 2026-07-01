# Lead-Scores-Analysis 🎯

## Overview
This repository contains a predictive modeling project designed to optimize the sales conversion process for **X Education**, an online education company selling courses to industry professionals. The primary goal is to build a machine learning model that assigns a "Lead Score" to prospective customers, helping the sales team identify and prioritize 'Hot Leads.'

## 📖 Problem Statement
On any given day, X Education attracts numerous professionals to its website through search engines, marketing campaigns, and past referrals. Visitors who interact with the site—such as browsing courses, watching videos, or filling out a contact form—are classified as **leads**. 

Once acquired, the sales team attempts to convert these leads into paying customers via calls and emails. However, the current typical lead-to-sale conversion rate is only about **30%**. This inefficiency means that for every 100 leads acquired, 70 are unlikely to convert, leading to wasted time and resources.

## 🎯 Business Objective
To make the sales process more efficient, X Education needs to identify the most promising leads ('Hot Leads'). The objective of this project is to build a classification model that assigns a lead score (between 0 and 100) to each prospect. 

By successfully identifying high-probability leads, the company can:
*   **Increase the overall conversion rate** by focusing efforts on leads most likely to convert.
*   **Optimize resource allocation** for the sales team.
*   **Streamline the lead conversion funnel.**

## 🛠️ Tech Stack & Tools
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
*   **Environment:** Jupyter Notebook
*   **Techniques Used:** Exploratory Data Analysis (EDA), Feature Engineering, Logistic Regression / Classification Models, Model Evaluation (ROC, AUC, Precision-Recall)

## 📂 Repository Structure
```text
diwakarkr007-create/Lead-Scores-Analysis
│
├── data/                   # Raw and processed datasets (if applicable)
├── notebooks/              # Jupyter notebooks containing EDA and model building
├── src/                    # Python scripts for data preprocessing and scoring
├── presentations/          # Final reports and presentation slides
├── README.md               # Project documentation
└── requirements.txt        # Required Python dependencies
