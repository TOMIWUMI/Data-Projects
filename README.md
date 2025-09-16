# ✈️ Machine Learning Pipeline for Airfoil Noise Prediction  

This project builds a **machine learning pipeline** in **PySpark** to predict airfoil self-noise levels.  
The goal is to understand the factors affecting noise generation and evaluate the predictive performance of a regression model.  

---

## 🚀 Project Overview  
- 📂 Data preprocessing using Spark DataFrames  
- 🧩 Feature engineering with **VectorAssembler**  
- 🔗 Building a **Linear Regression pipeline**  
- 📊 Model evaluation with metrics (MSE, MAE, R²)  
- 🔍 Coefficient analysis for feature impact  
- 💡 Recommendations for model improvement  

---

## 🛠️ Tools & Technologies  
- **Python**  
- **PySpark (Spark MLlib)**  
- **Pandas**  
- **Matplotlib**  

---

## 📂 Repository Structure  

airfoil-noise-prediction/
│
├── notebooks/
│ └── Final_Project_Build_a_Machine_Learning_Pipeline_for_Airfoil_Noise_Prediction.ipynb
├── results/
│ └── charts/ (optional plots and visualizations)
├── requirements.txt
└── README.md



---

## 📊 Results & Insights  
- **R² Score:** The model explains a moderate portion of the variance in sound level.  
- **Key Findings:**  
  - Frequency, angle of attack, chord length, and suction side displacement reduce sound level.  
  - Free stream velocity increases sound level.  
  - Frequency has the strongest negative impact.  
- **Recommendations:**  
  - Add interaction and polynomial features  
  - Try advanced models (Random Forests, Gradient Boosting)  
  - Perform hyperparameter tuning  
  - Collect more data for robustness  

---

## 📖 How to Run  
1. Clone this repo:  
   ```bash
   git clone https://github.com/your-username/airfoil-noise-prediction.git
   cd airfoil-noise-prediction



pip install -r requirements.txt

Author

Tomilola Omotiba

LinkedIn: linkedin.com/in/tomilola-omotiba

GitHub: @tomilola-omotiba

