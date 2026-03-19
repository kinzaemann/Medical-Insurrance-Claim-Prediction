# 🏥 Medical Insurance Claim Prediction

## 📌 Objective
Estimate medical insurance claim amounts based on personal and lifestyle data using regression modeling and interactive data analysis.

**Final project for DevelopersHub Corporation.**

---

## 📊 Dataset
- **Medical Cost Personal Dataset** ([Kaggle link](https://www.kaggle.com/datasets/mirichoi0218/insurance))
- 1,300+ records, 7 features
- Target: `charges` (medical insurance claim amount in USD)

---

## 🔧 Approach

1. **Data Cleaning:** Checked for missing values and encoded categorical variables.
2. **Feature Engineering:** One-hot encoded regions, mapped gender and smoking status.
3. **Exploratory Data Analysis (EDA):** Interactive Plotly visualizations for BMI, age, smoking, children, and region.
4. **Feature Scaling:** Standardized numerical features for regression.
5. **Model Training:** Linear Regression to predict insurance charges.
6. **Evaluation:** Used MAE and RMSE, and visualized predictions, residuals, and feature importance.
7. **Interpretation:** Identified key drivers of insurance costs.

---

## 📈 Results

- **MAE:** Typically between \$3,000–\$4,000 (average absolute error)
- **RMSE:** Typically between \$6,000–\$7,000 (root mean squared error)
- **Key Predictors:** Smoking status, age, and BMI have the largest impact on charges.

---

## 💡 Key Insights

- **Smokers** and those with higher BMI or older age have much higher predicted charges.
- **Number of children** and **region** have smaller effects.
- **Linear Regression** provides a solid baseline, but more complex models could further improve accuracy.

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Plotly (interactive EDA & model evaluation)
- Scikit-learn

---

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/kinzaemann/insurance-claim-prediction.git
    cd insurance-claim-prediction
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and run the notebook:
    - `insurance_claim_prediction.ipynb` (recommended: Jupyter or Kaggle)

---

## 📂 Project Structure

```
├── README.md
├── requirements.txt
├── insurance_claim_prediction.ipynb   # Main notebook
└── data/
    └── insurance.csv                  # Dataset (add or download from Kaggle)
```

---

## 📬 Contact

For questions or feedback, please [open an issue](https://github.com/kinzaemann/insurance-claim-prediction/issues) or connect on
[LinkedIn](www.linkedin.com/in/kinza-eman-747059361).

---

*Final project for DevelopersHub Corporation.*
