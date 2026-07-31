
# 🔒 Anomaly Detection in Cyber Security

A machine learning-based cybersecurity project that detects malicious system behavior by comparing multiple anomaly detection algorithms. The project evaluates Isolation Forest, Random Forest, and Local Outlier Factor (LOF) using system event logs to identify suspicious activities and improve threat detection accuracy.

---

## 📖 Project Overview

This project focuses on detecting cyber threats using machine learning techniques on labeled system activity datasets. Various preprocessing techniques, feature engineering, and model evaluation methods were applied to compare the performance of different anomaly detection algorithms.

The objective was to determine the most effective algorithm for identifying malicious activities while minimizing false positives.

---

## 🎯 Objectives

- Detect malicious system activities using Machine Learning.
- Compare the performance of multiple anomaly detection algorithms.
- Analyze system logs and process behavior.
- Perform feature engineering and preprocessing.
- Evaluate models using standard classification metrics.

---

## 🤖 Machine Learning Models

The project compares the following algorithms:

- Random Forest Classifier
- Isolation Forest
- Local Outlier Factor (LOF)

---

## 🗂 Dataset

The project uses a cybersecurity dataset containing system event logs.

### Important Features

- Process ID
- Parent Process ID
- User ID
- Mount Namespace
- Process Name
- Event ID
- Event Name
- Number of Arguments
- Return Value

Target Variable

- Evil (0 = Normal)
- Evil (1 = Malicious)

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed irrelevant features
- Label Encoding
- Feature Selection
- Correlation Analysis
- Data Cleaning
- Train / Validation / Test Split

---

## ⚙️ Technologies Used

Programming Language

- Python

Libraries

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Machine Learning

- Random Forest
- Isolation Forest
- Local Outlier Factor

Development Environment

- Jupyter Notebook

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- AUROC

---

## 📊 Results

| Model | Performance |
|--------|-------------|
| Random Forest | Best Overall Performance |
| Local Outlier Factor | Good Performance |
| Isolation Forest | Moderate Performance |

Random Forest achieved the highest overall performance among all evaluated models, demonstrating excellent capability in identifying malicious system activities.

---

## Project Workflow

Dataset Collection

↓

Data Preprocessing

↓

Feature Engineering

↓

Label Encoding

↓

Train Machine Learning Models

↓

Model Evaluation

↓

Performance Comparison

↓

Anomaly Detection

---

## Key Features

- Machine Learning based anomaly detection
- Multiple model comparison
- Cybersecurity event analysis
- Feature engineering
- Classification report generation
- Confusion matrix visualization
- Correlation heatmap analysis

---

## 🚀 Future Improvements

- Deep Learning based anomaly detection
- Autoencoder implementation
- Real-time intrusion detection
- Explainable AI (XAI)
- Web dashboard using Streamlit
- Cloud deployment

---

## Conference Recognition

This project was presented as:

**Anomaly Detection in Cybersecurity: Evaluating Machine Learning Models on the BETH Dataset**

**Conference:** IEEE International Conference on Consumer Electronics (ICCE 2025)

The project received a Certificate of Participation from IEEE.

---

# 👨‍💻 Author

**Vineeth S R**

🎓 B.Tech in Computer Science & Engineering

💻 Python Developer | Machine Learning | Deep Learning | AWS | Data Analytics

📍 Bengaluru, Karnataka, India

📧 vineethsr137@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/vineeth-sr

---

⭐ If you found this project useful, consider giving it a star!
