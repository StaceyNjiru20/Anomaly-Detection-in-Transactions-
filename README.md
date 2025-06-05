# Anomaly-Detection-in-Transactions-

This project demonstrates how to detect anomalous transactions using Python. It is particularly useful for identifying potentially fraudulent activities in financial datasets. By leveraging machine learning techniques and unsupervised learning, we aim to flag unusual patterns in transaction behavior.

📌 Overview
Anomaly detection is crucial in domains such as banking, fintech, and e-commerce where detecting unusual activities (e.g., fraud, abuse, or errors) is essential for security and compliance. This project walks through a practical example of detecting anomalies in transaction data using clustering and visualization techniques.

🚀 Features
Data preprocessing and exploration

Unsupervised anomaly detection using:

Isolation Forest

Local Outlier Factor (LOF)

Visualization of anomalies

Custom thresholding for fine-tuning anomaly sensitivity

Interactive plots with plotly and seaborn

📁 Dataset
The dataset used is a synthetic transaction dataset containing information like:

step – time step (hour)

type – transaction type (e.g., PAYMENT, CASH_OUT)

amount – transaction amount

oldbalanceOrg, newbalanceOrig – balance of sender before and after

oldbalanceDest, newbalanceDest – balance of recipient before and after

isFraud – whether the transaction is fraudulent (used only for validation)

📌 Note: This project assumes a context where labels (like isFraud) may not be available during actual detection. The models work in an unsupervised fashion.

🧠 Algorithms Used
🔹 Isolation Forest
An ensemble method that isolates anomalies instead of profiling normal data.

Efficient and scales well with high-dimensional data.

🔹 Local Outlier Factor (LOF)
Measures the local deviation of a data point with respect to its neighbors.

Suitable for datasets with clusters of similar density.
