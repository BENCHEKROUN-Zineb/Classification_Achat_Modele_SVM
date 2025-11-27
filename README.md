# Social Purchase Prediction using SVM

Ce projet utilise un **Support Vector Machine (SVM)** pour prédire si un utilisateur effectuera un achat en fonction de caractéristiques sociales et démographiques.

## 🧠 Objectif du projet

Développer un modèle de Machine Learning capable de prédire le comportement d'achat d'un individu en utilisant :

* L'âge
* Le revenu estimé
* Le résultat d'achat (0 ou 1)

## 📂 Contenu du repository

* `Social_Purchase_SVM.ipynb` : Notebook contenant toutes les étapes du projet :

  * Importation des données
  * Nettoyage et préparation
  * Visualisation
  * Division des données
  * Entraînement du modèle SVM
  * Évaluation des performances

## 📊 Techniques et outils utilisés

* **Python**
* **Pandas**, **NumPy** pour le traitement des données
* **Matplotlib**, **Seaborn** pour la visualisation
* **Scikit-learn** pour:

  * Preprocessing
  * Division train/test
  * SVM Classifier
  * Matrices de confusion & métriques

## 🚀 Résultats

Le modèle SVM permet de classifier efficacement les utilisateurs en fonction de leur probabilité d'achat. Les performances sont évaluées à l’aide :

* de la matrice de confusion
* de la précision / rappel / f1-score

## 🗂️ Comment exécuter le projet

1. Cloner le repository :

   ```bash
   git clone https://github.com/BENCHEKROUN-Zineb/Classification_social_purchase_SVM.git
   ```
2. Ouvrir le notebook :

   ```bash
   jupyter notebook Social_Purchase_SVM.ipynb
   ```
3. Exécuter les cellules une par une.
