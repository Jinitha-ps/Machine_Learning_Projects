# 🛍️ Customer Segmentation using K-Means Clustering

![Customer Segmentation](Customer_Segmentation.jpg)
---

# 📌 Project Overview

Customer segmentation is one of the most valuable applications of **Unsupervised Machine Learning**. This project applies the **K-Means Clustering** algorithm to group mall customers based on their **Annual Income** and **Spending Score**, enabling businesses to understand customer purchasing behavior and create targeted marketing strategies.

---

# 🎯 Problem Statement

Every customer has unique purchasing habits and income levels. Treating all customers the same can reduce the effectiveness of marketing campaigns.

This project aims to:

✅ Identify meaningful customer groups

✅ Improve customer engagement

✅ Enable personalized marketing

✅ Support data-driven business decisions

---

# 📂 Dataset Information

**Dataset:** Mall Customers Dataset

| 📌 Feature | 📝 Description |
|------------|----------------|
| CustomerID | Unique customer identifier |
| Gender | Male / Female |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Spending behavior score |

📊 **Total Records:** **200**

---

# 🛠️ Tech Stack

🐍 Python | 🐼 Pandas | 🔢 NumPy | 📈 Matplotlib | 🎨 Seaborn | 🤖 Scikit-learn | 📓 Jupyter Notebook | 💻 VS Code 

---

# 🤖 Machine Learning

**Type:** Unsupervised Machine Learning

**Algorithm:** K-Means Clustering

---

# 🔄 Project Workflow

- 📥 Import Libraries
- 📂 Load Dataset
- 🔍 Data Understanding
- 🧹 Data Cleaning
- 📊 Exploratory Data Analysis (EDA)
- 🎯 Feature Selection
- ⚖️ Feature Scaling
- 📈 Elbow Method
- 🤖 Train K-Means Model
- 🎨 Customer Segmentation
- 📍 Cluster Analysis
- 💡 Business Insights
- 💾 Save Results

---

# 📊 Exploratory Data Analysis

The project includes the following visualizations:

📌 Age Distribution

📌 Gender Distribution

📌 Annual Income Distribution

📌 Spending Score Distribution

📌 Age vs Spending Score

📌 Annual Income vs Spending Score

📌 Box Plot

📌 Violin Plot

📌 Pair Plot

📌 Correlation Heatmap

📌 Age Group Distribution

---

# ⚙️ Model Building

### 🎯 Feature Selection

Selected Features:

- Annual Income (k$)
- Spending Score (1-100)

### ⚖️ Feature Scaling

Applied **StandardScaler** to normalize the selected features.

### 📈 Elbow Method

Determined the optimal number of clusters.

**Optimal Clusters:** **5️⃣**

### 🤖 K-Means Clustering

Customers were successfully grouped into **5 distinct customer segments**.

---

# 📊 Results

The clustering model identified five customer groups:

💎 High Income – High Spending

💰 High Income – Low Spending

🛍️ Low Income – High Spending

📉 Low Income – Low Spending

⭐ Average Income – Average Spending

---

# 💼 Business Insights

✔️ Premium customers can receive exclusive offers.

✔️ High-income customers with low spending are potential marketing targets.

✔️ Low-income but high-spending customers are ideal for loyalty programs.

✔️ Average customers can be nurtured through personalized recommendations.

---

# 📁 Project Structure

```text
Customer-Segmentation-Using-KMeans/
│
├── Customer_Segmentation.ipynb
├── Mall_Customers.csv
├── Customer_Segmentation.jpg
├── Customer_Segmentation_Results.csv
├── README.md
└── requirements.txt
```

---

# 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Customer-Segmentation-Using-KMeans.git
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Open the Notebook

```bash
jupyter notebook Customer_Segmentation.ipynb
```

or open it directly in **VS Code**.

---

# 🔮 Future Improvements

✨ Compare with Hierarchical Clustering

✨ Apply DBSCAN Clustering

✨ Deploy using Streamlit

✨ Create an interactive Power BI Dashboard

---

# 💡 Skills Demonstrated

🐍 Python Programming

📊 Data Analysis

📈 Exploratory Data Analysis (EDA)

🎨 Data Visualization

⚖️ Feature Scaling

🤖 Unsupervised Machine Learning

🎯 K-Means Clustering

👥 Customer Segmentation

💼 Business Intelligence

---

# 👩‍💻 Author

**Jinitha PS**

⭐ **If you found this project useful, please consider giving it a Star!**
