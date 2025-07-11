# 📊 Walmart Weekly Sales Prediction

Ce projet vise à prédire les ventes hebdomadaires des magasins Walmart en utilisant des modèles de régression. Il a été réalisé dans le cadre d'un exercice de data science pour comprendre les facteurs influençant les ventes et améliorer les prévisions marketing.

## 🏢 Contexte

Walmart souhaite mieux anticiper les ventes dans ses magasins à l’aide d’indicateurs économiques comme le taux de chômage, le prix du carburant ou la température.

---

## 🎯 Objectifs du projet

1. Réaliser une **analyse exploratoire des données (EDA)**.
2. Mettre en place un **modèle de régression linéaire** de base.
3. Implémenter une **régression régularisée** (Ridge ou Lasso) pour limiter l’overfitting.
4. **Interpréter les résultats** : importance des variables, performances, etc.

---

## ⚙️ Modèles utilisés

- Régression Linéaire
- Régression Ridge
- Évaluation via RMSE

Les performances sont évaluées avec des métriques standards de régression, et les coefficients des modèles sont analysés pour comprendre l’importance des variables.

---

## 📌 Résultats

- Le modèle de régression linéaire donne une première baseline.
- Le modèle Ridge/Lasso améliore la généralisation sur les données de test.
- L’importance des variables économiques est visible via les coefficients du modèle.

---

## 📦 Installation

```bash
pip install -r requirements.txt
cd walmart-weekly-sales-prediction
jupyter notebook Projet_ML_Walmart.ipynb
