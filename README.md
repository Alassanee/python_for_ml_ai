 # Veille Python pour ML et IA — NumPy, Pandas, Matplotlib

Documentation et notebook réalisés dans le cadre du module de certification **Orange Digital
Center (ODC)** portant sur l'environnement Python pour le Machine Learning et l'Intelligence
Artificielle.

## Description

Ce projet regroupe une veille technologique complète sur les trois bibliothèques fondamentales
de l'écosystème Data Science en Python :

- **NumPy** — calcul numérique et manipulation de tableaux
- **Pandas** — manipulation et analyse de données tabulaires
- **Matplotlib** — visualisation de données

L'objectif n'est pas seulement de présenter la syntaxe de chaque bibliothèque, mais surtout de
comprendre **dans quel contexte** elles sont utilisées, **quel problème** chacune résout, et
**comment interpréter** les résultats qu'elles produisent — une démarche appliquée notamment à
travers une étude sur l'analyse exploratoire de données (EDA).

## Objectifs pédagogiques

- Comprendre pourquoi Python nécessite des bibliothèques dédiées au calcul scientifique
- Maîtriser la création, la manipulation et le calcul vectorisé avec NumPy
- Savoir importer, nettoyer, explorer et agréger des données avec Pandas
- Savoir produire et interpréter des visualisations avec Matplotlib
- Appliquer une démarche d'analyse exploratoire de données (EDA) sur un jeu de données réel

 
## Prérequis

- Python 3.9 ou supérieur
- pip
- (Optionnel) VS Code avec l'extension Jupyter, ou JupyterLab

## Installation

```bash
# 1. Cloner le dépôt
git clone git@github.com:ton-utilisateur/nom-du-repo.git
cd nom-du-repo

# 2. Créer et activer un environnement virtuel
python3 -m venv env
source env/bin/activate        # Linux / macOS
env\Scripts\activate           # Windows

# 3. Installer les dépendances
pip install -r requirements.txt
```

## Utilisation

Ouvrir le notebook avec JupyterLab :

```bash
jupyter lab
```

ou directement dans VS Code en sélectionnant le kernel correspondant à l'environnement virtuel
`env` (Select Kernel → Python Environments → env).

## Contenu du notebook

| Section | Contenu |
|---|---|
| Environnement Python | venv, pip, Jupyter/JupyterLab |
| NumPy | création, manipulation, indexation, calcul scientifique, vectorisation |
| Pandas | Series, DataFrame, import/export, exploration, filtrage, groupby, fusion, valeurs manquantes |
| Matplotlib | line plot, bar chart, histogramme, scatter plot, pie chart, personnalisation |
| Analyse exploratoire (EDA) | démarche, statistiques descriptives, détection d'outliers, corrélation, interprétation |

## Jeu de données

Le fichier `data.csv` est un jeu de données fictif (noms, âges, villes, salaires)
utilisé à des fins pédagogiques pour illustrer l'import, le nettoyage et l'analyse avec Pandas.

 

## Ressources complémentaires

- [Documentation officielle NumPy](https://numpy.org/doc/)
- [Documentation officielle Pandas](https://pandas.pydata.org/docs/)
- [Documentation officielle Matplotlib](https://matplotlib.org/stable/)

## Auteur

**Alassane Mbengue (bl4ckcyph3er)** — Étudiant en Master 2 Sécurité des Systèmes Embarqués (UCAD),
Formation IA — Orange Digital Center
