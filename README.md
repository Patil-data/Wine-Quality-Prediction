# 🍷 Wine Quality Prediction

A complete machine learning project that predicts whether a wine is of high quality based on its chemical properties. Built using Python, Scikit-learn, and Seaborn with extensive EDA and model comparisons.

---

## 📘 Project Summary

This notebook uses the [Red and White Wine Quality Dataset](https://www.kaggle.com/datasets/saigeethac/red-and-white-wine-quality-datasets) to:
- Perform exploratory data analysis (EDA)
- Engineer features for binary classification
- Train 3 models: Random Forest, SVM, SGD
- Evaluate models using accuracy, confusion matrix & classification reports
- Visualize important features and comparisons

---

## 🧪 Features Used
- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

---

## 📊 Visualizations
- 📈 Feature distributions with hue by wine quality
- 🔥 Heatmap showing correlations
- 📦 Boxplots comparing high- vs low-quality wines
- 🎯 Confusion matrices for each model
- 🪄 Feature importance chart (Random Forest)

---

## 📈 Models Used

| Model                | Accuracy |
|---------------------|----------|
| Random Forest        | ~0.88    |
| Support Vector Machine | ~0.85 |
| SGD Classifier       | ~0.83    |

Random Forest performed the best overall, especially on alcohol and sulphate content.

---

## 🧠 Key Takeaways

- Alcohol and Volatile Acidity are the top predictors of high-quality wine.
- Red wine tends to have a more balanced quality distribution than white.
- The dataset with 6,497 samples is sufficient for strong model training.

---

## 🛠 Tech Stack

- Python 3
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Google Colab

---

## 📂 Dataset

- 📥 [Kaggle Dataset – Red and White Wine Quality](https://www.kaggle.com/datasets/saigeethac/red-and-white-wine-quality-datasets)

---

## ✅ How to Run

1. Clone the repository or open the notebook in Google Colab
2. Upload the dataset (`winequality-red.csv` and `winequality-white.csv`)
3. Run the notebook step-by-step
4. Check model accuracy, visualizations, and final predictions

---

## ✨ Author

**Shyamal Narayan Patil**  
[GitHub](https://github.com/Patil-data) | [LinkedIn](https://linkedin.com/in/patil-shyamal-narayan)

