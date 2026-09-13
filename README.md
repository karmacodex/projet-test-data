# Analyse supervisée du Titanic

Ce projet contient un notebook Jupyter qui met en œuvre un flux complet d’apprentissage supervisé pour prédire la survie des passagers du Titanic. Il couvre l’exploration des données, la préparation des variables, l’entraînement, l’optimisation des hyperparamètres et l’évaluation de plusieurs modèles.

## Contenu

- `Assignment2_supervised_learning_flow.ipynb` : analyse et modèles ;
- `titanic_train.csv` : données d’entraînement ;
- `titanic_test.csv` : données de test ;
- `requirements.txt` : dépendances Python ;
- `LICENSE` : licence MIT du projet d’origine.

## Installation

Python 3.10 ou une version ultérieure est recommandé.

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Exécution

Lancez Jupyter puis ouvrez le notebook :

```bash
jupyter notebook Assignment2_supervised_learning_flow.ipynb
```

Exécutez ensuite toutes les cellules dans l’ordre. Les deux fichiers CSV doivent rester dans le même dossier que le notebook.

## Modèles évalués

Le notebook compare notamment les k plus proches voisins, un arbre de décision et un classifieur naïf bayésien. Les performances sont mesurées avec l’exactitude, la précision, le rappel et le score F1.

## Provenance et licence

Le contenu a été importé depuis [ShalevAtsis/Machine-Learning-Flow](https://github.com/ShalevAtsis/Machine-Learning-Flow). Il est distribué sous licence MIT ; consultez `LICENSE` pour les conditions et l’attribution d’origine.
