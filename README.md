# Projet Machine Learning – Prédiction & Classification sur le cancer du sein
https://github.com/Mael-Bonnet/Projet_machine_learning/blob/main/README.md
Ce projet a pour but de développer et d’évaluer des modèles de **machine learning** pour :

- 🔬 **Prédire** l'expression d'une **protéine spécifique** (problème de régression),
- ❤️ **Classer** le **pronostic vital** de patients atteints de cancer du sein (problème de classification).

Les données sont issues de **Kaggle**, disponibles ici :  
👉 [Breast Cancer Survival Dataset](https://www.kaggle.com/datasets/kreeshrajani/breast-cancer-survival-dataset?resource=download)

---

## 📁 Structure du projet

├── data/ # Contient les données brutes téléchargées

├── notebooks/ # Jupyter Notebooks pour l'exploration, modélisation et visualisation

├── src/ # Scripts Python (prétraitement, modèles, évaluation)
│ ├── preprocessing.py
│ ├── models.py
│ └── evaluation.py

├── results/ # Graphiques, métriques, figures exportées

├── requirements.txt # Librairies nécessaires

├── README.md # Ce fichier

└── main.py # Script principal pour lancer le projet


## ⚙️ Installation & Lancement

### 1. 🔽 Cloner le dépôt

```bash
git clone https://github.com/Mael-Bonnet/Projet_machine_learning.git
cd Projet_machine_learning ```
 ```
### 🐍 Créer un environnement virtuel
```
python -m venv env
source env/bin/activate  # Sur Windows : env\Scripts\activate
```

### 4. 📂 Télécharger les données
Rendez-vous sur Kaggle, téléchargez le dataset et placez-le dans le dossier data/.

### 5. 🚀 Lancer le script principal
```
bash
Copy
Edit
python 1_Classification.ipynb
python 2_Régression.ipynb
```

Le script effectue automatiquement :

Le prétraitement des données

L'entraînement de modèles de régression et de classification

L'évaluation croisée et la génération de visualisations


## 📊 Objectifs du projet
### 🎯 Régression – Prédiction du taux de protéine
Modèles utilisés : Linear Regression, Random Forest Regressor, Gradient Boosting

Métriques : RMSE, R², MAE

Visualisations : courbes de prédiction, importance des variables

### ❤️ Classification – Prédiction du statut vital
Modèles utilisés : Logistic Regression, Random Forest, XGBoost

Métriques : Accuracy, Recall, F1-score, ROC AUC

Visualisations : matrices de confusion, courbes ROC, importance des features

### 📌 Détails techniques
Langage : Python 3.10+

Librairies principales :

pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn

Validation croisée : KFold, cross_val_score

Optimisation : GridSearchCV pour recherche d’hyperparamètres

### 🙋‍♂️ Auteur
👤 Maël Bonnet
### 📧 Contact : via GitHub

### 📜 Licence
Ce projet est libre de droits pour un usage éducatif ou de recherche. N'hésitez pas à le forker ou à contribuer.
