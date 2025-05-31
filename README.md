# Prédiction Prêt Bancaire – Classification & Régression

Ce projet a été réalisé dans le cadre du module de **Machine Learning** de notre formation en Data Science.  
L’objectif est d’appliquer des techniques de machine learning pour prédire :
- l’acceptation ou le refus d’une demande de prêt (classification)
- le montant du prêt accordé (régression)

## Démarche

Le projet suit une approche complète de data science :
- **Prétraitement et sélection des données** : nettoyage, transformation et choix des variables pertinentes
- **Modélisation** : test de plusieurs modèles de machine learning pour chaque tâche (classification et régression)
- **Évaluation** : sélection du meilleur modèle selon des métriques adaptées (accuracy, F1-score, RMSE, etc.)

## Données

Les données utilisées proviennent de Kaggle :  
[Lien vers le dataset](https://www.kaggle.com/...)  <!-- Remplace ce lien par le vrai ! -->

Pour exécuter les notebooks, télécharge le fichier de données depuis Kaggle et place-le dans le dossier `data/` du projet.

## Environnement

Un fichier `environment.yml` est fourni pour créer l’environnement virtuel nécessaire.  
Pour l’utiliser, exécutez ces commandes dans votre terminal :

<pre> ## Structure du projet ``` projet-pret-bancaire/ ├── classification_notebook.ipynb ├── regression_notebook.ipynb ├── README.md ├── environment.yml └── data/ └── base_de_donnees.csv # à placer ici après téléchargement ``` </pre>
