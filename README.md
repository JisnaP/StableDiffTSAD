Stable Diffusion for Anomaly Detection in Multivariate Time Series

This project implements a Stable Diffusion Model for anomaly detection in multivariate time series data. The model leverages anomaly scores computed using the MTAD-GAT model as a conditioning input in the reverse diffusion process to improve anomaly detection accuracy.

Objective
The model predicts whether a given timestamp is anomalous or normal, making it suitable for real-world anomaly detection tasks in time series data.

Key Features
✅ Stable Diffusion Model for anomaly detection

✅ Anomaly scores from MTAD-GAT used as conditioning input

✅ Reverse diffusion process incorporates anomaly scores

✅ Best F1-score optimization achieved 0.96 F1-score

✅ Requires a GPU for Training on a New Dataset


Performance
F1-Score: 0.96 (using best F1-score search method)

Usage
This model can be applied to various time-series anomaly detection tasks, including:

This model can be applied to various time-series anomaly detection tasks, including:

🏦 Fraud Detection

🏭 Industrial Equipment Monitoring

🌐 Network Intrusion Detection

🏥 Healthcare Anomaly Detection


