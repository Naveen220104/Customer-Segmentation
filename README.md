# 👥 Customer Segmentation using Machine Learning

This project segments customers into distinct groups using unsupervised learning techniques like KMeans and DBSCAN. It's aimed at helping businesses understand customer behaviors and target them effectively.

---

## 📌 Problem Statement

To identify meaningful customer segments based on attributes like age, income, gender, and spending habits using clustering techniques.

---

## 📊 Dataset Description

| Column Name            | Description                        |
|------------------------|------------------------------------|
| CustomerID             | Unique ID for each customer        |
| Gender                 | Male or Female                     |
| Age                    | Customer's age                     |
| Profession             | Job title of the customer          |
| Annual Income ($)      | Yearly income of the customer      |
| Spending Score (1-100) | Score based on spending behavior   |

---

## 🧠 ML Techniques Used

- 📍 **KMeans Clustering**
- 🧩 **DBSCAN (Density-Based Clustering)**
- 🔄 **PCA** for dimensionality reduction
- 📈 **Silhouette Score** for cluster quality evaluation

---

## 🛠️ Tech Stack

- Python 3.11
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📂 Project Structure
Customer-Segmentation/
├── Customers.csv
├── Customer_Segmentation.ipynb
├── main.pkl # (optional) saved clustering model
├── requirements.txt
├── README.md
