# PRODIGY_ML_02 — Customer Segmentation using K-Means Clustering

## Task
Cluster mall customers into distinct segments based on Annual Income and Spending Score using K-Means clustering.

## Dataset
[Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) (Kaggle)

## Approach
- Features used: Annual Income (k$), Spending Score (1-100)
- Data scaled using StandardScaler
- Optimal cluster count (K=5) determined via the Elbow Method
- K-Means applied and clusters visualized

## Results
Five customer segments identified:
1. Premium Targets — high income, high spending
2. Impulsive Spenders — low income, high spending
3. Average Customers — mid income, mid spending
4. Budget-Conscious — low income, low spending
5. High-Income Savers — high income, low spending

## Tools
Python, scikit-learn, pandas, matplotlib, Google Colab

## Author
Rahul Sohan Singh — ML Intern, Prodigy InfoTech
