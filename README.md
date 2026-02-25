# 🏥 Karnataka

<p>
 <img src="https://img.rolandberger.com/content_assets/content_images/captions/Roland_Berger_WEB_24_2694_Regenerative_agriculture_IT_image_caption_w768.jpg?v=1687234">
</p>

---

## 📌 Project Overview

This project focuses on  **Agricultural data - Exploratory Data Analysis (EDA)** using agricultural karnataka region dataset.
The dataset includes agricultural statistics from the Indian state of Karnataka, primarily focused on crop production, environmental conditions, and farming practices. It integrates multiple agronomic and economic variables for agricultural research, machine learning modeling, and exploratory data analysis.

---

## 🎯 Objectives

- Perform **Exploratory Data Analysis (EDA)**
- Visualize relationships between features and insurance charges
- Handle missing values and outliers
- Encode categorical variables
- Apply feature scaling and transformations
- Train and compare multiple **regression models**
- Evaluate models using standard regression metrics

---

## 📊 Dataset Description

- **Source:** Kaggle – Agriculture dataset | Karnataka
- **Type:** Tabular
- **Authors:** Rajesh Naik
- **Target Variable:**
  - `charges` – Medical insurance cost
  - ` premium` – Insurance premium charged

### Features Description

| Feature | Description |
|-------|-------------|
| Year |Crop production year (e.g., 2004–2019) |
| Location | Specific geographic unit within Karnataka (e.g., district/taluk). |
| Area | Land area under cultivation (units not always stated, typically hectares) |
| Rainfall | Rainfall amount recorded in millimetres (mm). |
| Temperature | Average temperature in celsius and farhenheit |
| Humidity | Relative humidity (in percentage) |
| Soil type | Type of soil (e.g., Alluvial, Black, Red Soil |
| Irrigation | Irrigation method used |
| Yield |  The amount of crop produced per unit area of land |
| Crops | Crop grown on that land (e.g., Coconut, Rice) |
| Price | Market price of the crop |
| Season |Agricultural season (e.g., Kharif, Rabi, Zaid). |

📎 **Dataset Link:**  
https://www.kaggle.com/datasets/imtkaggleteam/agriculture-dataset-karnataka/data

---

## 🔍 Exploratory Data Analysis (EDA)

EDA includes:

- Statistical summary of numerical features
- Distribution analysis (histograms, KDE plots)
- Correlation analysis
- Impact of categorical variables on insurance charges
- Outlier detection and skewness analysis

Visualizations were created using **Matplotlib** and **Seaborn**.

---

## 🛠️ Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Encoding categorical variables:
  - One-Hot Encoding
  - Label Encoding (when applicable)
- Feature scaling:
  - StandardScaler
  - MinMaxScaler
- Log transformation for skewed target variable (if required)

---

## 🤖 Machine Learning Models

The following regression models were implemented and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Gradient Boosting Regressor

Each model was evaluated to identify the best-performing approach.

---

## 📈 Model Evaluation

Models were evaluated using:

- **R² Score**
- **RMSE (Root Mean Squared Error)**

Model comparison highlights the effectiveness of ensemble methods over linear models.

---

## 🧪 Results & Insights

- Discount eligibility (smoking-related) has a **significant impact** on insurance charges
- Age and BMI show a positive correlation with medical costs
- Tree-based ensemble models outperform linear regression models

---

## 📚 References

- **Kaggle Dataset**  
  Health Insurance Dataset – IMT Team  
  https://www.kaggle.com/datasets/imtkaggleteam/health-insurance-dataset

- **IMT ChallengeHub Guidelines**  
  https://github.com/MrezaMomeni/IMT

---

📌 **Challenge Link:**  
https://github.com/MrezaMomeni/IMT/tree/main/ChallengeHub/2-%20Medical_Insurance


---

## 🔱 Fork Information

This project has been **forked and customized** from the following repository:

https://github.com/MrezaMomeni/IMT

---

## 👤 Author

**Hossein Heydari**  
Computer Engineering Student | Junior Data Scientist and Machine Learning Engineer  

GitHub: https://github.com/HosseinHeydari2004 <br>
Kaggle: 

---

## ❤️ Support

If you find this project helpful, please ⭐ the repository and share your feedback.

Happy Learning 🌱✨

