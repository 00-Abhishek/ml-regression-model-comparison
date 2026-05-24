



```markdown
# 🏠 House Price Prediction — ML Model Comparison

Feature engineering, preprocessing, and regression model comparison on the **California Housing Dataset** using scikit-learn.

---

## 📌 Project Overview

This project demonstrates a complete Machine Learning workflow including data preprocessing, feature scaling, training multiple regression models, and selecting the best-performing model based on evaluation metrics.

Built as part of the **AI & ML Internship at Main Crafts Technology**.

---

## 📊 Models Compared

| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | 0.7456 | 0.5758 |
| Ridge Regression | 0.7455 | 0.5758 |
| **Decision Tree Regressor** | **0.7242** | **0.5997** |

✅ **Best Model: Decision Tree Regressor** (max_depth=5)

---

## 🔧 Tech Stack

- Python 3
- pandas, NumPy
- scikit-learn
- matplotlib
- Jupyter Notebook

---

## 🚀 How to Run

```bash
git clone https://github.com/00-Abhishek/house-price-prediction-ml.git
cd house-price-prediction-ml
pip install -r requirements.txt
jupyter notebook AI_ML_Task2_Model_Comparison.ipynb
```

---

## 📁 Project Structure

```
house-price-prediction-ml/
│
├── AI_ML_Task2_Model_Comparison.ipynb   # Main notebook
├── AI_ML_Task2_Report.pdf               # Methodology & results report
├── requirements.txt
└── README.md
```

---

## 📈 ML Pipeline

1. Load California Housing Dataset
2. Separate features (X) and target (y)
3. Apply StandardScaler for feature scaling
4. Train-Test Split (80/20)
5. Train Linear, Ridge, and Decision Tree models
6. Evaluate using RMSE and R² Score
7. Select best model with justification

---

## 💡 Key Learnings

- Feature scaling significantly impacts model stability
- Decision Tree outperforms linear models on non-linear housing data
- Ridge Regression adds minimal benefit when features are already well-scaled
- Comparing multiple models is essential before deployment

---

## 👤 Author

**Abhishek Pal**  
AI & ML Intern — Main Crafts Technology  
[LinkedIn](https://linkedin.com/in/abhishekpal-ai) · [GitHub](https://github.com/00-Abhishek)
```

---

**Also create a `requirements.txt`** with this:

```
pandas
numpy
matplotlib
scikit-learn
jupyter
```

