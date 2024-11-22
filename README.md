# 🎥 Projet de Prédiction de Scoring et Recommandation de Films

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/6/69/Netflix_logo.svg)

Ce projet explore les facteurs influençant les scores et la popularité des films grâce à des techniques de Data Science et Machine Learning. L'objectif est de prédire les scores des films et de développer un système de recommandation personnalisé basé sur la similarité de contenu.

---

## 🚀 Objectifs

- **Analyse exploratoire des données (EDA)** : Comprendre les tendances des films selon leurs genres, langues et popularité au fil du temps.
- **Prédiction des scores** : Utiliser des modèles de Machine Learning pour estimer les scores des films.
- **Recommandation personnalisée** : Construire un système de recommandation basé sur la similarité des descriptions et des genres.

---

## 🛠️ Outils et Technologies

- **Langages** : Python
- **Bibliothèques principales** :
  - Visualisation : `Matplotlib`, `Seaborn`, `Plotly`
  - Machine Learning : `Scikit-learn`, `XGBoost`, `LightGBM`, `RandomForest`
  - Traitement de texte : `TfidfVectorizer`, `CountVectorizer`
- **Modèles utilisés** :
  - Régression Linéaire, Ridge, Lasso
  - Random Forest
  - Gradient Boosting (GBM)
  - LightGBM
  - XGBoost

---

## 📊 Analyse Exploratoire des Données

1. **Distribution des notes** : Analyse des scores moyens par genre.
2. **Popularité et tendances** :
   - Évolution du nombre de films au fil des décennies.
   - Impact de la popularité et du nombre de votes sur les scores.
3. **Analyse des genres** :
   - Distribution des films par genre et langue.
   - Corrélation entre les variables (popularité, scores, etc.).
4. **Nuages de mots** :
   - Genres principaux.
   - Descriptions des films.

---

## 🤖 Modélisation

### Modèles testés :
- **Régression Linéaire** : Modèle de base pour capturer les relations linéaires.
- **Ridge et Lasso** : Régularisation pour éviter le sur-apprentissage.
- **Forêt Aléatoire** : Modèle non linéaire performant pour des relations complexes.
- **Gradient Boosting (GBM)** : Capture des relations non linéaires.
- **XGBoost & LightGBM** : Modèles avancés pour une meilleure précision et rapidité.

### Résultats des modèles (meilleur score) :
- **LightGBM** :
  - Mean Squared Error (MSE) : 0.2574
  - Coefficient de Détermination (R²) : 0.5619
- **XGBoost** :
  - MSE : 0.2755
  - R² : 0.5311

---

## 🎯 Système de Recommandation

Le système utilise la similarité de contenu basée sur :
- Les descriptions (`TfidfVectorizer`).
- Les genres associés aux films (`CountVectorizer`).

Exemple de recommandation pour le film _"The Godfather"_ :
1. The Godfather
2. The Godfather: Part II
3. Blood Ties
4. Joker
5. Bomb City

---

## 📂 Structure du Projet

Voici l'arborescence du projet :

