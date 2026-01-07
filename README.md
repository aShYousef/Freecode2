# Cloud-Based Distributed Data Processing Service ☁️🚀

A comprehensive cloud-native application for distributed data analysis and machine learning using **Apache Spark** and **Streamlit** on Google Colab.

## 📌 Project Overview
This project demonstrates the principles of distributed computing by simulating a cluster environment. It allows users to:
- Upload datasets (CSV/JSON).
- Perform statistical analysis.
- Train Machine Learning models (Linear Regression, Decision Trees, etc.) using **PySpark MLlib**.
- **Simulate Scalability:** Test performance across 1, 2, 4, and 8 nodes to measure Speedup and Efficiency using Amdahl's Law.

## 🛠️ Technologies Used
- **Language:** Python
- **Processing Engine:** Apache Spark (PySpark)
- **Web Framework:** Streamlit
- **Tunneling:** Ngrok (PyNgrok)
- **Environment:** Google Colab

## 🚀 How to Run
1. Open the [Google Colab Notebook](https://colab.research.google.com/drive/1RleYIag60k_dI-S8p_kwqi1I33xQq006?usp=sharing).
2. Go to **Runtime** > **Run all**.
3. Wait for the installation to finish.
4. Click the generated `ngrok-free.app` link to access the dashboard.

## 📊 Features
- **Data Ingestion:** Automatic schema detection for JSON/CSV.
- **Visual Analytics:** Real-time charts and statistics.
- **Scalability Testing:** Compare execution time between Single-Node and Multi-Node clusters.
