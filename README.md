# 🎥 Movie Scoring Prediction and Recommendation Project

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/6/69/Netflix_logo.svg)

This project explores the factors influencing movie scores and popularity using Data Science and Machine Learning techniques. The goal is to predict movie scores and develop a personalized recommendation system based on content similarity.

---

## 🚀 Objectives

- **Exploratory Data Analysis (EDA)**: Understand trends in movies based on their genres, languages, and popularity over time.
- **Score Prediction**: Use Machine Learning models to predict movie scores.
- **Personalized Recommendation**: Build a recommendation system based on the similarity of descriptions and genres.

---

## 🛠️ Tools and Technologies

- **Languages**: Python
- **Main Libraries**:
  - Visualization: `Matplotlib`, `Seaborn`, `Plotly`
  - Machine Learning: `Scikit-learn`, `XGBoost`, `LightGBM`, `RandomForest`
  - Text Processing: `TfidfVectorizer`, `CountVectorizer`
- **Models Used**:
  - Linear Regression, Ridge, Lasso
  - Random Forest
  - Gradient Boosting (GBM)
  - LightGBM
  - XGBoost

---

## 📊 Exploratory Data Analysis (EDA)

1. **Score Distribution**: Analyze average scores by genre.
2. **Popularity and Trends**:
   - Evolution of movie count over the decades.
   - Impact of popularity and vote count on movie scores.
3. **Genre Analysis**:
   - Distribution of movies by genre and language.
   - Correlations between variables (popularity, scores, etc.).
4. **Word Clouds**:
   - Main genres.
   - Movie descriptions.

---

## 🤖 Modeling

### Models Tested:
- **Linear Regression**: A baseline model to capture linear relationships.
- **Ridge and Lasso**: Regularization techniques to avoid overfitting.
- **Random Forest**: A powerful model for capturing complex non-linear relationships.
- **Gradient Boosting (GBM)**: Captures non-linear relationships effectively.
- **XGBoost & LightGBM**: Advanced models for better accuracy and speed.

### Model Results (Best Score):
- **LightGBM**:
  - Mean Squared Error (MSE): 0.2574
  - R²: 0.5619
- **XGBoost**:
  - MSE: 0.2755
  - R²: 0.5311

---

## 🎯 Recommendation System

The system uses content similarity based on:
- Movie descriptions (`TfidfVectorizer`).
- Associated genres (`CountVectorizer`).

Example recommendations for the movie _"The Godfather"_:
1. The Godfather
2. The Godfather: Part II
3. Blood Ties
4. Joker
5. Bomb City

---

## 📌 Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-project.git
   cd your-project

---

## 💬 Thank you for visiting!

I hope you enjoyed exploring this project! If you have any questions, suggestions, or just want to chat, feel free to reach out. Let's keep exploring the fascinating world of data and machine learning together!

---

### 🚀 See you soon for more projects!
