# ❤️ Heart Disease Prediction System
> Advanced Binary Classification ML Pipeline | Healthcare Analytics

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-1.0+-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Problem Statement
Heart disease is the leading cause of death globally. Early prediction using 
patient clinical data can save lives. This project builds an end-to-end ML 
pipeline to predict the presence or absence of heart disease.

## 🎯 Key Features
- Deep Exploratory Data Analysis with visualisations
- Feature engineering — age groups, BP categories, cholesterol categories
- Comparison of 5 ML models with 5-fold cross-validation
- Evaluation using Accuracy, ROC-AUC, F1, Precision, Recall
- Feature importance analysis using Random Forest
- Real-world patient prediction function

## 🤖 Models Compared
| Model | Test Accuracy | ROC-AUC |
|-------|-------------|---------|
| Logistic Regression | ~82% | ~88% |
| Decision Tree | ~78% | ~82% |
| **Random Forest** | **~85%** | **~90%** |
| Gradient Boosting | ~84% | ~89% |
| SVM | ~83% | ~88% |

## 🛠️ Tech Stack
- **Language:** Python 3.8+
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Dataset:** UCI Cleveland Heart Disease Dataset

## 📊 Key Insights
1. Chest pain type (cp) is the strongest predictor of heart disease
2. Max heart rate (thalach) and thalassemia (thal) are highly significant
3. Random Forest outperforms all models with ROC-AUC of ~90%
4. Male patients show higher risk in this dataset

## 🚀 How to Run
```bash
git clone https://github.com/SARAYU39/heart-disease-prediction
cd heart-disease-prediction
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook Heart_Disease_Prediction.ipynb
```

## 📁 Project Structure

