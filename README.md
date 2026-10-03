# Fraud Analytics Assignments

Both notebooks use `Fraud Detection Dataset.csv` (51,000 transactions, 12 columns).

| File | Topic |
|---|---|
| `FDCH1_solved.ipynb` | Sampling (random, stratified, cluster, equalized), data selection (missing/identical values, correlation, chi-square) and fraud-prediction models (Logistic Regression, Random Forest, Random Forest + SMOTE) |
| `FDCH_2_solved.ipynb` | Duplicate counts, payment method vs fraud, outliers, common/uncommon values, and DBSCAN anomaly detection |

Case study: `Cosmos_Bank_Cyber_Heist_Report.docx`

## Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
jupyter notebook
```
Open a notebook from this folder so it finds the CSV. Outputs are already saved in the notebooks.
