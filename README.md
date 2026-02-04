# 🌍 Global Pollution Analysis and Energy Recovery

## 📌 Project Description
This project focuses on analyzing global pollution data and applying machine learning
techniques to understand pollution patterns and predict energy recovery from pollution-related factors.

The work is carried out strictly as per the given academic assignment guidelines and
demonstrates an end-to-end machine learning workflow.

---

## 🎯 Objective
The main objectives of this project are:
- To analyze global pollution indicators using data analysis techniques
- To study the relationship between pollution levels and energy recovery
- To build predictive models for energy recovery
- To classify countries based on pollution severity levels

---

## 📂 Dataset
- **File name:** `Global_Pollution_Analysis.csv`
- The dataset contains pollution indicators such as:
  - Air Pollution Index
  - Water Pollution Index
  - Soil Pollution Index
  - CO₂ Emissions
  - Industrial Waste
  - Energy Consumption
  - Energy Recovery

---

## ⚙️ Project Workflow

### 🔹 Phase 1: Data Collection & Preprocessing
- Loading the dataset
- Handling missing values
- Scaling pollution indices (Air, Water, Soil)
- Encoding categorical variables such as Country and Year

### 🔹 Phase 2: Exploratory Data Analysis (EDA)
- Descriptive statistical analysis
- Correlation analysis using heatmaps
- Visualizations (box plots and distributions)
- Pollution trend analysis across countries and years

### 🔹 Phase 3: Feature Engineering
- Year-based trend analysis
- Energy consumption per capita calculation

### 🔹 Phase 4: Predictive Modeling

#### Linear Regression
- Predicts **Energy Recovery (GWh)**
- Evaluation Metrics:
  - R² Score
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)

#### Logistic Regression
- Classifies pollution severity into:
  - Low
  - Medium
  - High
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

### 🔹 Phase 5: Insights & Recommendations
- Analysis of how pollution levels affect energy recovery
- Identification of high-risk pollution regions
- Recommendations for pollution reduction and energy recovery strategies

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Structure
