# Prédiction des Maladies Cardiovasculaires avec R

Ce projet propose une analyse complète des facteurs de risques cardiaques et la mise en place d'un modèle prédictif. Le dataset utilisé est le **Heart Disease Data Set** de l'UCI Machine Learning Repository (données de Cleveland).

## 📊 Objectifs du projet
* Nettoyer et prétraiter des données médicales brutes.
* Réaliser une analyse exploratoire (Statistiques descriptives & Visualisation).
* Effectuer des tests statistiques (Khi-deux, Shapiro-Wilk, Wilcoxon/Student) pour valider les corrélations.
* Développer un modèle de Machine Learning (Régression Logistique) pour prédire la présence d'une maladie.

## 🛠️ Stack Technique
* **Langage :** R
* **Librairies :** * `dplyr` & `caTools` (Manipulation et split)
  * `caret` (Matrice de confusion et évaluation)
  * `performance` (Test de Hosmer-Lemeshow)
  * `pROC` (Courbe ROC)

## 📈 Résultats clés
* **Nettoyage :** Traitement des valeurs manquantes et recodage complet des variables qualitatives (sexe, douleurs thoraciques, etc.).
* **Analyse :** Identification des variables les plus significatives (ex: type de douleur `cp`, nombre de vaisseaux `ca`).
* **Modèle :** La régression logistique optimisée (critère AIC) permet d'obtenir une prédiction robuste de l'état de santé des patients.
* **Performance :** Évaluation via Courbe ROC et Matrice de Confusion.

## 🚀 Comment utiliser ce projet
1. Clonez le dépôt.
2. Ouvrez le fichier `Projet.R` dans RStudio.
3. Le script télécharge automatiquement les données depuis l'URL de l'UCI.
