# Distance Metrics for Customer Segmentation
Comparing Euclidean, Manhattan, and Cosine distance metrics to measure customer similarity for retail marketing, plus a custom weighted hybrid metric.

## Contents
- `distance_metrics_lab.ipynb` — full notebook: preprocessing, distance matrix calculations, similarity comparison, and hybrid metric evaluation.
- `retail_customers.csv` — dataset used by the notebook (100 customers).

## Approach
1. Identify binary vs. categorical features
2. Preprocess: MinMax scale numerical features, one-hot encode categorical/binary features
3. Compute Euclidean, Manhattan, and Cosine distance/similarity matrices
4. Build a `find_similar_customers` function and compare results across metrics
5. Create a weighted hybrid distance metric (0.4 Euclidean + 0.4 Manhattan + 0.2 Cosine)
6. Evaluate the hybrid metric on a reference customer

## Tech
Python, scikit-learn, pandas, matplotlib, seaborn
EOF