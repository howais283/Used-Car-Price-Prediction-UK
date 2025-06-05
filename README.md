# Used-Car-Price-Prediction-UK

Supervised and unsupervised machine learning techniques applied to a synthetic UK second-hand car dataset for price prediction and customer segmentation. Achieved top-tier performance using models such as Polynomial Regression, Random Forest, and a tuned Artificial Neural Network.

---

## 🚗 Project Overview

This project explores price prediction for used cars in the UK using a variety of machine learning approaches. A cleaned mock dataset of 50,000 records was analyzed using both supervised learning (regression models) and unsupervised learning (clustering algorithms).

The goal was twofold:
- Predict used car prices using various features (manufacturer, engine size, mileage, etc.)
- Segment the car market into meaningful clusters for customer profiling

---

## 📊 Dataset

The dataset contains **50,000 entries** with the following features:
- **Manufacturer** (Categorical)
- **Model** (Categorical)
- **Engine Size** (Numerical)
- **Fuel Type** (Categorical)
- **Year of Manufacture** (Numerical)
- **Mileage** (Numerical)
- **Price** (Target Variable)

📁 File location: [Dataset/car_sales_data_24.csv](./Dataset/car_sales_data_24.csv)

---

## 🧠 Models & Techniques

### 🔧 Supervised Learning
- **Linear & Polynomial Regression** (using single and multiple numerical variables)
- **Decision Tree & Random Forest Regression**
- **Artificial Neural Network** (with hyperparameter tuning via Keras Tuner)

📈 **Best Performing Model**:  
- **Random Forest Regression**:  
  - **R² Score**: 0.9982  
  - **MAE**: 332.27 

- **Tuned ANN**:  
  - **R² Score**: 0.9921  
  - **MAE**: 899.51 

---

### 🔍 Unsupervised Learning
- **K-Means Clustering** (Optimal k via Elbow Method & Silhouette Score)
- **Gaussian Mixture Models**
  
📌 **Best Clustering Result**:  
- **K-Means on Year of Manufacture & Mileage**  
  - **Davies-Bouldin Index**: 0.658  
  - **Silhouette Coefficient**: 0.533 

---

## 📂 Contents

- `notebooks/`: Jupyter notebooks for training, analysis, and evaluation
- `dataset/`: Data file used for modeling (`car_sales_data_24.csv`)
- `reports/`: Final project report and evaluation

---

## 📌 Key Highlights

- Compared performance of **Linear**, **Polynomial**, **Tree-based**, and **Neural** models
- Tuned ANN using **Keras Tuner Random Search**
- Visualized actual vs. predicted price distribution and residual plots
- Identified clustering trends using **K-Means** and **GMM**
- Developed data-driven insights for car pricing and customer segmentation

---

## 📘 License

This project is for academic and educational purposes only. Dataset is synthetic and used for demonstration and modeling practice.

