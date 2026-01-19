# 📊 Customer Segmentation for SBI Life Insurance (Market Segmentation)

## 📌 Project Overview
Customer segmentation is a crucial strategy in the insurance and financial services sector to better understand customer behavior and deliver personalized products. This project focuses on **market segmentation for SBI Life Insurance customers** using **unsupervised machine learning techniques**.

By analyzing customer transaction and behavioral data, we group customers into meaningful segments that can help businesses design targeted marketing strategies, improve customer retention, and enhance cross-selling opportunities such as insurance plans, loans, and wealth management services.

---

## 🎯 Objectives
- Identify distinct customer groups based on behavioral and financial attributes  
- Apply clustering algorithms to uncover hidden patterns in customer data  
- Assist marketing and business teams in targeting the right customer segments  
- Improve decision-making through data-driven insights  

---

## 🗂️ Dataset Description
- The dataset contains **credit card and customer transaction-related attributes**
- Each row represents a unique customer
- Features include spending behavior, balance information, payment history, and credit usage patterns
- The dataset is loaded from a CSV file (`credit_card_dataset.csv`)

> ⚠️ Note: The dataset should be present in the project directory before running the notebook.

---

## 🛠️ Tech Stack & Tools
- **Programming Language:** Python  
- **Libraries Used:**
  - pandas – data manipulation
  - numpy – numerical computations
  - matplotlib & seaborn – data visualization
  - scikit-learn – machine learning models
- **Environment:** Jupyter Notebook  

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
- Imported the dataset using pandas
- Performed initial inspection to understand data shape and structure

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed data distributions and summary statistics
- Checked for missing values and inconsistent data
- Gained insights into customer spending and payment behavior

### 3️⃣ Data Preprocessing
- Handled missing values appropriately
- Removed irrelevant columns (if any)
- Standardized features using **StandardScaler**
- Reduced dimensionality using **Principal Component Analysis (PCA)**

### 4️⃣ Clustering Techniques Applied

#### 🔹 K-Means Clustering
- Used the **Elbow Method** to determine the optimal number of clusters
- Evaluated cluster quality using the **Silhouette Score**

#### 🔹 Agglomerative Hierarchical Clustering
- Applied to analyze hierarchical relationships among customers
- Visualized clusters using dendrograms

#### 🔹 DBSCAN (Density-Based Clustering)
- Identified dense regions and outliers in customer data
- Useful for detecting noise and irregular patterns

---

## 📈 Results & Insights
- Successfully segmented customers into **distinct behavioral groups**
- Identified:
  - High-value customers with high spending and credit usage
  - Low-engagement customers with minimal transactions
  - Customers with irregular or risky financial behavior
- These insights can help SBI Life Insurance:
  - Personalize insurance offerings
  - Improve customer engagement
  - Reduce churn and financial risk

---

## ▶️ How to Run the Project

### Prerequisites
Install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
