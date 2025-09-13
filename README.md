# Régression Logistique Multiclasse : OvR vs Softmax

Ce projet compare deux approches de la régression logistique multiclasse :
- OVR (One-vs-Rest) : un modèle binaire par classe
- Softmax (Multinomial) : un seul modèle qui apprend toutes les classes en même temps

## Contenu du dépôt

### 1. 'OVR.ipynb'
- Dataset : Iris
  - Chargement des données avec pandas
  - Exploration des données et visualisation
  - Détection et suppression des valeurs aberrantes (outliers)
  - Entraînement d’un modèle de régression logistique en mode OvR avec Scikit-learn
  - Évaluation par :
    - Accuracy globale
    - Matrice de confusion

### 2. `softmax.ipynb`
  - Dataset: Digits
  - Chargement du dataset avec sklearn.datasets.load_digits
  - Visualisation des chiffres en images
  - Évaluation par :
    - Accuracy globale
    - Matrice de confusion
    - Analyse des probabilités

## Comparaison OvR vs Softmax
- OvR : simple à comprendre, utile quand le dataset est petit ou déséquilibré  
- Softmax : mieux adapté aux datasets avec beaucoup de classes 
