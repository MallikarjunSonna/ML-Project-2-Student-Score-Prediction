# 📘 Student Performance Prediction - ML Project

This project aims to predict student academic performance based on various socio-demographic features like gender, parental education, test preparation, etc.

We experimented with multiple regression models and evaluation metrics to understand model performance and data limitations.

---

## 📂 Project Structure

- `StudentScorePrediction_Basic.ipynb`: Initial version using Linear Regression.
- `StudentScorePrediction_Improved.ipynb`: Advanced version with feature engineering and Random Forest.
- `StudentsPerformance.csv`: Dataset used (UCI-style student performance).
- `README.md`: Project summary and documentation.

---

## 📊 Dataset Description

The dataset includes the following columns:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

created an additional column: `average_score = mean(math, reading, writing)`

---

## 🧠 ML Models Used

- Linear Regression
- Random Forest Regressor (with Hyperparameter Tuning)

---

## ✅ Results

| Model                 | MSE    | R² Score |
|----------------------|--------|----------|
| Linear Regression     | 187.45 | 0.13     |
| Random Forest (Tuned) | 245.71 | -0.01    |
| Predicting Avg Score  | 219.59 | -0.02    |

> 📌 Note: Despite tuning, models showed limited predictive power due to the dataset's lack of strong predictive features.

---

## 📚 Learnings

- Performed full EDA and feature encoding.
- Implemented and evaluated ML regression models.
- Understood the importance of meaningful features in predictive modeling.

---

## 🚀 Future Improvements

- Use datasets with more predictive features.
- Try classification problems (e.g., pass/fail, grade bands).
- Explore XGBoost, LightGBM, or neural networks.

---

## 🧑‍💻 Author

**Mallikarjun Sonna**  
[GitHub Profile](https://github.com/MallikarjunSonna)

---

## 🏷️ Tags

`Machine Learning` `Regression` `Random Forest` `EDA` `Student Performance`
