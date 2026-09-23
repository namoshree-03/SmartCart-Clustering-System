# 🛒 SmartCart — Customer Segmentation

## 📌 Project Overview

SmartCart is an **unsupervised machine learning project** that segments e-commerce customers based on their demographics, purchasing behaviour, and engagement patterns. The goal is to identify meaningful customer groups that can support personalized marketing and customer retention.

## ✨ Features

* Data cleaning and preprocessing
* Missing value handling
* Feature engineering
* Outlier detection and removal
* Categorical data encoding
* Feature scaling
* PCA dimensionality reduction
* Elbow Method and Silhouette Score for cluster evaluation
* Customer segmentation and visualization

## 🤖 Models Used

* **K-Means Clustering**
* **Agglomerative Clustering**
* **PCA** for dimensionality reduction

## 📊 Dataset Features

The dataset contains **2,240 customer records and 22 attributes**.

### Demographics

* Year_Birth
* Education
* Marital_Status
* Income
* Kidhome
* Teenhome
* Dt_Customer

### Purchase Behaviour

* MntWines
* MntFruits
* MntMeatProducts
* MntFishProducts
* MntSweetProducts
* MntGoldProds

### Purchase & Engagement

* NumDealsPurchases
* NumWebPurchases
* NumCatalogPurchases
* NumStorePurchases
* NumWebVisitsMonth
* Recency
* Complain

Additional features such as **Age, Customer Tenure, Total Spending, and Total Children** are derived during preprocessing.

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/SmartCart-Clustering-System.git
cd SmartCart-Clustering-System
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook
```

Open **`smartcart.ipynb`** and run the cells sequentially.
