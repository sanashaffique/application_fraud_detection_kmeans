# Fraud Detection in Internship Applications (K-Means)

This project was developed as part of the **Internne.pk Major Project** under mentor guidance.  
It focuses on detecting fraudulent or suspicious internship applications using **K-Means Clustering** — an unsupervised machine learning algorithm.

## 📘 Overview
The model analyzes application data (submission time and marks) to identify abnormal patterns that may indicate fake or inconsistent entries.  
Outliers are flagged as **suspicious**, helping prevent fraudulent applications.

## 🧠 Techniques Used
- Python (pandas, numpy, sklearn, matplotlib)
- K-Means Clustering for anomaly detection
- Data visualization for cluster interpretation

## 📊 Results
- Total applications: 50  
- Normal applications: 48  
- Suspicious applications: 2  
- Output: `suspicious_kmeans_report.csv` (flagged records)

## 🗂️ Files Included
- `fraud_detection_kmeans.ipynb` — main code file  
- `fraud_applications.csv` — input dataset  
- `suspicious_kmeans_report.csv` — generated output  
- `README.md` — project documentation  

## 🧾 Interpretation
Green points → Normal applications  
Red points → Suspicious (outliers)  
Blue X → Cluster centers  

## 🙌 Acknowledgment
Developed as part of **Internne.pk Major Project** under the valuable guidance of the assigned mentor.
