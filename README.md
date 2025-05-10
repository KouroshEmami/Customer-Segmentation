# E-commerce Customer Segmentation using RFM and K-Means

This project segments customers of an e-commerce store using the RFM (Recency, Frequency, Monetary) model and unsupervised learning with K-Means clustering.

## Project Structure

- **Data Source**: Brazilian E-Commerce Public Dataset by Olist (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Analysis**:
  - Merged orders, customer, item, and payment datasets.
  - Computed RFM metrics for each customer.
  - Normalized data using `StandardScaler`.
  - Applied K-Means clustering (optimal clusters found using Elbow Method).
  - Visualized cluster characteristics.

## Getting Started

1. Download the Olist dataset from Kaggle and place the CSV files in the same folder as the notebook.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook to reproduce the analysis and visualizations.

## Insights

- **Cluster 0**: Loyal high-spending customers – reward them.
- **Cluster 1**: New one-time customers – engage with onboarding.
- **Cluster 2**: Inactive customers – re-engage with targeted offers.
- **Cluster 3**: Frequent low-spenders – consider upselling.

