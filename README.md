# Analyse et Prédiction de la Survie aux Accidents de la Route

## Description

Ce projet a pour objectif d'analyser les données d'accidents de la route et de construire des modèles d'apprentissage automatique pour prédire la survie. Il couvre l'exploration et le prétraitement des données, ainsi que l'entraînement et l'évaluation de plusieurs modèles de classification.

## Installation

Pour exécuter ce notebook, vous aurez besoin des bibliothèques Python suivantes. Vous pouvez les installer avec pip :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Utilisation

1.  **Téléchargez le jeu de données** : Le fichier `accident.csv` est utilisé dans ce projet. Le notebook mentionne qu'il provient de Kaggle, potentiellement de "road-accident-survival-dataset". Assurez-vous d'avoir ce fichier dans le même répertoire que le notebook ou mettez à jour le chemin d'accès dans le code.

2.  **Ouvrez le notebook Jupyter** : Exécutez le fichier `Accident.ipynb` dans un environnement Jupyter Notebook ou JupyterLab.

    ```bash
    jupyter notebook Accident.ipynb
    ```

## Fichiers Principaux

  - `Accident.ipynb`: Le notebook Jupyter contenant l'ensemble de l'analyse, du prétraitement et de la modélisation.
  - `accident.csv`: Le jeu de données sur la survie aux accidents de la route.

## Modèles Utilisés

Les modèles de classification suivants ont été implémentés et évalués:

  - Régression Logistique (Logistic Regression)
  - Arbre de Décision (Decision Tree Classifier)
  - Forêt Aléatoire (Random Forest Classifier)

## Conclusion

Selon l'analyse:

  - La Régression Logistique a montré la meilleure performance globale.
  - L'Arbre de Décision est venu en deuxième position, mais manque de fiabilité.
  - La Forêt Aléatoire a été le modèle le moins efficace.

Je suggère d'ajuster les modèles ou d'explorer d'autres algorithmes pour améliorer la performance.