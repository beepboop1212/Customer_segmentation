# 🛍️ Customer Segmentation with K-Means Clustering

This project performs **customer segmentation** using **K-Means Clustering** based on a dataset of mall customers. It helps uncover groups of customers with similar behaviors based on features like age, income, and spending score.

---

## 📊 Dataset Overview

- 📁 Source: `Mall_Customers.csv` (from Kaggle)
- 👥 Columns:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🎯 Project Goals

- Visualize and understand distributions of key attributes (age, gender, income, spending score)
- Apply K-Means clustering to segment customers into distinct groups
- Explore customer behavior based on:
  - `Age vs Spending Score`
  - `Annual Income vs Spending Score`

---

## 📌 Techniques Used

- 📈 Data Visualization:
  - `Matplotlib`, `Seaborn`, and `Plotly` for distribution plots, scatter plots, violin plots, etc.
- 🧠 Machine Learning:
  - `KMeans` clustering (from `sklearn`)
  - Elbow method for optimal cluster selection
- 🧪 Segmentation Analysis:
  - Two clustering strategies:
    - `Age vs Spending Score` (4 clusters)
    - `Annual Income vs Spending Score` (5 clusters)

---

## 📉 Sample Visualizations

- **Distribution plots** for Age, Income, and Spending
- **Gender-based scatter plots**
- **Violin + Swarm plots** to show gender effects
- **Clustered regions** with K-Means predictions and centroids

---

## 🚀 How to Run

This project was developed and run in a **Kaggle Notebook** environment.

To run locally:

1. Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn plotly

	2.	Load the dataset:

df = pd.read_csv('Mall_Customers.csv')

	3.	Run the clustering code and visualizations as shown in the notebook.

⸻

💡 Insights
	•	Certain age groups and income brackets show distinct spending behaviors.
	•	K-Means effectively clusters customers into behavior-based segments.
	•	Useful for targeted marketing strategies.

⸻

📁 Directory

Mall_Customers.csv       # Customer data for segmentation
customer_segmentation.ipynb  # Main notebook with clustering logic and plots



⸻

🙌 Credits
	•	Kaggle Dataset: Mall Customer Segmentation
	•	Inspired by real-world marketing and CRM use cases

---
