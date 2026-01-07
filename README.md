# Urbanization Prediction in Toulouse (2021)

Projet de Applied Statistical Learning portant sur la prédiction de l’urbanisation
à Toulouse en 2021 à partir de données satellitaires, géographiques et
socio-démographiques.

---

## Contenu du dépôt

### `exploration.ipynb`
Notebook dédié à l’**exploration des données** :
- analyse descriptive des variables,
- distributions des indices spectraux et variables de distance,
- matrice de corrélation,
- visualisation spatiale des observations,
- mise en évidence des relations entre urbanisation et variables explicatives.

Ce notebook sert à comprendre la structure du jeu de données et à motiver
les choix de modélisation.

---

### `modelisation.ipynb`
Notebook principal de **modélisation et d’évaluation** :
- séparation train / test,
- validation croisée et sélection d’hyperparamètres,
- comparaison de plusieurs modèles de classification binaire :
  - régression logistique,
  - arbre de décision,
  - Random Forest,
  - Gradient Boosting,
  - réseau de neurones (MLP),
- évaluation via Accuracy, Balanced Accuracy, F1-score, ROC-AUC et
  Precision–Recall,
- analyse des importances de variables (Random Forest),
- analyse spatiale des erreurs de prédiction.

---

## Jeu de données

Le jeu de données est construit à partir de Google Earth Engine
(Sentinel-2, ESA WorldCover, données géographiques et socio-démographiques).

Pour des raisons de taille et de bonnes pratiques, les fichiers `.csv`
ne sont pas versionnés dans ce dépôt.

La version corrigée du jeu de données est disponible ici :  https://drive.google.com/file/d/1ixBDyoz_e5tgHTi9VcHVR9UxZRSD7mq0/view?usp=sharing