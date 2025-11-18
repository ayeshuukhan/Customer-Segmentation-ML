
## Project Overview

Customers are grouped into clusters based on features like **Age, Education, Income, Years Employed, Debts, and Debt-Income Ratio**.

The goal:

* Identify distinct customer groups.
* Predict which group a new customer belongs to based on their details.
* Visualize customer segments clearly for business insights.

---

## Features

* **Data Preprocessing**: Clean and prepare customer data for clustering.
* **Customer Segmentation**: Group customers using clustering (e.g., KMeans).
* **Prediction Module**: Take user inputs via a questionnaire to assign them to a segment.
* **Visualization**: Scatter plots & charts to analyze clusters visually.

---

## Dataset

* **Customer Id**: Unique ID for each customer
* **Age, Education, Income**: Demographic and financial details
* **Years Employed**: Work experience
* **Card Debt, Other Debt, DebtIncomeRatio**: Debt information
* **Defaulted**: Loan default indicator

---

## Tech Stack

* **Python**
* **Pandas, NumPy** → Data handling
* **Matplotlib, Seaborn** → Visualizations
* **Scikit-learn** → Clustering & prediction

---

## Workflow

1. **Load & preprocess data**
2. **Apply clustering algorithm** (KMeans)
3. **Assign cluster labels to each customer**
4. **Visualize clusters** using Age, Income, Education, etc.
5. **Build prediction input form** to classify new customers into clusters.

---

## Visualizations

* **Scatter Plot**: Customers distributed by Age & Income
* **Cluster Comparison**: Mean income, education, and other features per cluster
