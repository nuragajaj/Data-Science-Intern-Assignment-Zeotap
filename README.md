# Data Science Assignment: eCommerce Transactions Dataset

## Overview
This repository contains the solution to the Data Science Internship assignment. The assignment involves analyzing an eCommerce transactions dataset to extract actionable insights, build predictive models, and perform customer segmentation. The goal is to demonstrate data analysis, machine learning, and business insight generation skills.

---

## Dataset Details
The dataset consists of three files:

1. **Customers.csv**
   - Details of customers including ID, name, region, and signup date.
2. **Products.csv**
   - Information about products such as ID, name, category, and price.
3. **Transactions.csv**
   - Records of customer transactions including transaction ID, product ID, quantity, and total value.

---

## Tasks Completed

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Performed exploratory data analysis on the dataset.
- Derived business insights, including:
  - Top-performing regions and products.
  - Seasonal trends in transactions.
  - Revenue contributions by region.
- Deliverables:
  - **EDA Notebook**: `FirstName_LastName_EDA.ipynb`
  - **Insights Report**: `FirstName_LastName_EDA.pdf`

### Task 2: Lookalike Model
- Built a lookalike model to recommend 3 similar customers for a given customer based on their profile and transaction history.
- Used both customer and product information to compute similarity scores.
- Deliverables:
  - **Lookalike Model Notebook**: `FirstName_LastName_Lookalike.ipynb`
  - **Lookalike Results CSV**: `FirstName_LastName_Lookalike.csv`

### Task 3: Customer Segmentation (Clustering)
- Performed customer segmentation using clustering techniques (K-Means).
- Determined the optimal number of clusters using the Davies-Bouldin Index.
- Grouped customers into high-value, moderate, and low-value segments.
- Deliverables:
  - **Clustering Notebook**: `FirstName_LastName_Clustering.ipynb`
  - **Clustering Report**: `FirstName_LastName_Clustering.pdf`

---

## File Structure
```
|-- FirstName_LastName_EDA.ipynb
|-- FirstName_LastName_EDA.pdf
|-- FirstName_LastName_Lookalike.ipynb
|-- FirstName_LastName_Lookalike.csv
|-- FirstName_LastName_Clustering.ipynb
|-- FirstName_LastName_Clustering.pdf
|-- README.md
```

---

## Tools and Technologies Used
- **Python**: Data analysis and machine learning.
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation.
  - `matplotlib`, `seaborn`: Data visualization.
  - `scikit-learn`: Machine learning models and clustering.
- **Jupyter Notebook**: For interactive coding and visualization.

## Key Learnings
- Applied data analysis techniques to derive business insights from raw data.
- Built a customer recommendation model using similarity scores.
- Performed customer segmentation with clustering to improve marketing strategies.
- Gained experience in presenting findings through reports and visualizations.

---

## Author
Arun

For any questions or feedback, feel free to contact me at [https://www.linkedin.com/in/arungajraj/].

