# 📊 Customer Segmentation & Spending Prediction

A comprehensive data science project that performs **customer segmentation**, explores **consumer behavior patterns**, and builds a **predictive model** to estimate individual customer spending using machine learning.

![Python](https://img.shields.io/badge/Made%20With-Python-blue?style=flat-square)  
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-0.24+-orange?style=flat-square)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

---

## 🔍 Overview

This project analyzes customer data to:
- Segment customers based on demographics and behavior.
- Identify key factors influencing customer spending.
- Predict individual customer spending based on input features.
- Visualize insights using charts and heatmaps.
- Deploy a real-time **Gradio-based interface** for predictions.

---

## 🛠️ Technologies Used

- **Python (Pandas, NumPy, Matplotlib, Seaborn)**
- **Scikit-learn** (KMeans, Random Forest, Decision Tree, LabelEncoder, StandardScaler)
- **Gradio** (for interactive UI)
- Google Colab (for experimentation)

---

## 📁 Dataset

The dataset (`customer_data.csv`) includes the following fields:
- `name`, `age`, `gender`, `education`, `income`, `country`, `purchase_frequency`, `spending`

> The dataset is cleaned for missing values and duplicates during preprocessing.

---

## 📊 Key Features

### 1. **Data Cleaning & Preprocessing**
- Handled missing values and duplicate records.
- Encoded categorical variables using `LabelEncoder`.
- Standardized features for clustering.

### 2. **Exploratory Data Analysis (EDA)**
- Age group and gender distribution via pie charts.
- Spending behavior by education level.
- Country-wise average spending.
- Income vs. spending and purchase frequency vs. spending correlation.

### 3. **Customer Segmentation (K-Means Clustering)**
- Used the **Elbow Method** to determine optimal clusters.
- Visualized clusters by income vs. spending.
- Inverse transformed cluster centers for interpretation.

### 4. **Feature Importance Analysis (Random Forest)**
- Ranked features influencing customer spending.
- Visualized correlation and importance using a heatmap.

### 5. **Spending Prediction (Decision Tree Regressor)**
- Built a model to predict customer spending based on:
  - Age, gender, education, income, country, and purchase frequency.
- Achieved real-time prediction through **Gradio web interface**.

---

## 📷 Screenshots

| Cluster Visualization | Gradio App |
|-----------------------|-------------|
| *(Add cluster plot here)* | *(Add Gradio interface screenshot here)* |

---
## 🚀 Running the Project
## pip install -r requirements.txt


Step 3: Run Jupyter or Colab Notebook

    Open Customer_Segmentation_Analysis.ipynb in Jupyter Notebook or Google Colab.

Step 4: Launch Gradio UI

Run the below code cell from the notebook:

interface.launch()

🎯 Use Cases

    Business Intelligence

    Targeted Marketing

    Personalized Customer Experience

    Revenue Optimization

## 🤝 Contributions

Contributions are welcome! Feel free to fork this project, submit issues, or create pull requests.
📄 License

This project is licensed under the MIT License.
🙋‍♀️ Author

Vandana Kumari
📧 vandanapriyadarshi2222@gmail.com
🔗 LinkedIn


### Step 1: Clone the repository
```bash
git clone https://github.com/yourusername/customer-segmentation-analysis.git
cd customer-segmentation-analysis 
---
