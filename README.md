# Comparative Analysis of Fraud & Anomaly Patterns in Financial Transactions

Data-driven Analysis of RBI Fraud Data and Anomaly Detection in Financial Transactions

## Overview

This project applies machine learning and data analytics techniques to analyze fraud patterns in Indian financial institutions. It combines exploratory data analysis with unsupervised learning methods to detect anomalous patterns in transaction data and identify fraudulent behavior.

The project demonstrates end-to-end data analysis — from raw data preprocessing to insight-driven visualization — using Python in a Jupyter Notebook environment.

## Business Problem

Financial institutions process millions of transactions daily, but identifying fraudulent patterns in large datasets is challenging. Banks need to:

* Understand trends in fraud occurrence across institutions
* Detect anomalous transactions deviating from normal behavior
* Identify periods and patterns of high financial risk
* Implement data-driven fraud detection and prevention strategies

This project addresses these challenges using practical, industry-relevant machine learning techniques.

## Key Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Machine Learning (Unsupervised Learning)
* Anomaly Detection Algorithms
* Deep Learning (Autoencoders)
* Data Visualization & Interpretation
* Python-based Analytics Workflow

## Datasets Used

**RBI Fraud Data (2020-2026)**

* Source: Reserve Bank of India
* Type: Bank-wise fraud statistics and recovery data
* Features: 17 hierarchical columns including fraud counts, financial loss, recovery amounts
* Usage: Fraud trend analysis and baseline establishment
* Coverage: 15+ Indian financial institutions

**Digital Payments Dataset (June 2020 - April 2026)**

* Source: Publicly available e-commerce and payments data
* Type: Monthly transaction volumes (UPI)
* Usage: Correlation analysis with fraud patterns
* Granularity: Daily and yearly aggregations

## Methodology

1. Loaded and cleaned hierarchical RBI fraud and digital payments datasets
2. Performed data transformation using pandas melt operations for time-series format
3. Conducted comprehensive exploratory data analysis with 15+ visualizations
4. Calculated anomaly scores using statistical approaches
5. Implemented Isolation Forest algorithm for unsupervised anomaly detection
6. Developed Autoencoder deep learning model for pattern recognition
7. Compared detection results and identified complementary algorithmic strengths
8. Generated insights through comparative analysis and visualization

All findings shown are data-driven and based on actual financial transaction patterns.

## Key Insights

* Identified anomalous patterns in financial fraud data that deviate from normal banking behavior
* Revealed correlations between UPI transaction volumes and fraud occurrence trends
* Isolation Forest effectively identified point anomalies in multi-dimensional data
* Autoencoder captured complex non-linear patterns in fraud behavior
* Both algorithms demonstrated complementary strengths for comprehensive anomaly detection
* Visual analytics enabled clear identification of high-risk periods and institutions

## Tools & Technologies

* Python
* Jupyter Notebook
* pandas, NumPy
* Scikit-learn (Isolation Forest)
* TensorFlow/Keras (Autoencoder)
* Matplotlib, Seaborn

## Repository Structure
```
├── fraud-analysis-project/
│   ├── README.md 
│   ├── requirements.txt 
│   ├── notebooks/
│   │   └── (Untitled_major.ipynb here)
│   ├── data/
│   │   ├── rbi_fraud_data.xlsx
│   │   └── digital_payments.xlsx
│   └── results/
│       └── visualizations/
```

## Why This Project Matters

This project reflects real-world analytics tasks commonly performed in:

* Financial Services & Banking
* Fraud Detection & Prevention
* Risk Management & Compliance
* Data Science & Analytics roles

It demonstrates the ability to convert raw financial data into actionable insights that support risk mitigation and strategic decision-making.

## Key Features

### Exploratory Data Analysis
- 15+ visualizations covering trends, correlations, and distributions
- Time-series analysis of fraud patterns over 6+ years
- Multi-dimensional relationship exploration

### Isolation Forest Algorithm
- Unsupervised anomaly detection with 5% contamination threshold
- Effective for identifying point anomalies in financial data
- Fast computation suitable for large datasets

### Autoencoder Deep Learning Model
- Neural network architecture with 3-neuron bottleneck layer
- 50 epochs training with 20% validation split
- 95th percentile reconstruction error threshold for anomaly classification

### Comparative Analysis
- Side-by-side evaluation of both algorithms
- Performance metrics on multi-dimensional data
- Identification of complementary strengths

## Results

### Isolation Forest Results
- Identifies point anomalies effectively
- Fast computation on large datasets
- Suitable for real-time fraud detection

### Autoencoder Results
- Captures complex non-linear patterns
- Better for detecting collective anomalies
- Effective for pattern recognition

## Visualizations Generated

- Total frauds over time by institution
- Financial loss and recovery trends
- Recency and frequency patterns
- UPI transaction growth analysis
- Anomaly detection overlays
- Correlation heatmaps between variables

**Last Updated:** May 2026
