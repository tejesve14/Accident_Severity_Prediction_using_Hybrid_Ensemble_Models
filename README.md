# 🚗 Accident Severity Prediction Using Hybrid Ensemble Models

## 📌 Problem Statement

Road accidents are a major public safety concern worldwide. Predicting accident severity can help authorities improve emergency response times, optimize resource allocation, and design effective road safety measures.

## 🎯 Project Objective

Develop a machine learning system to predict accident severity using hybrid ensemble learning techniques and address class imbalance using SMOTE.

## 🔧 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* SMOTE
* SHAP
* Matplotlib
* Streamlit

## 🤖 Models Used

* Logistic Regression
* Random Forest
* XGBoost / Gradient Boosting
* Hybrid Stacking Ensemble (Final Model)

## 📊 Results

| Model                    | Accuracy |
| ------------------------ | -------- |
| Logistic Regression      | 71%      |
| Hybrid Stacking Ensemble | 87%      |

### Key Findings

* Applied SMOTE to handle class imbalance.
* Ensemble learning improved prediction performance over individual models.
* SHAP was used for model interpretability and feature importance analysis.
* Achieved improved recall for minority severity classes.

## 📁 Project Structure

```text
Accident_Severity_Prediction_using_Hybrid_Ensemble_Models
│
├── app.py
├── data/
│   └── accident_data.csv
├── notebook/
│   └── FINAL_YEAR_PROJECT.ipynb
├── images/
└── README.md
```

## 🚀 How to Run

1. Clone the repository
2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the application

```bash
streamlit run app.py
```

4. Open the notebook for model training and analysis

```bash
jupyter notebook notebook/FINAL_YEAR_PROJECT.ipynb
```

## 📈 Future Improvements

* Deploy the model to a cloud platform.
* Add real-time accident severity prediction.
* Enhance explainability with additional SHAP visualizations.

## 👩‍💻 Author

Tejesve Sivakumar
