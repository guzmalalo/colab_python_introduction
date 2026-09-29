# Introduction à Python, NumPy et Matplotlib

Ce dépôt contient les notebooks du cours **ING1 — 2026–2027**, consacrés aux bases de Python, au calcul numérique et aux graphiques.

## Ouvrir dans Google Colab

Aucune installation locale n'est nécessaire. Ouvrez un notebook avec le lien correspondant, puis enregistrez une copie dans votre Google Drive pour conserver votre travail.

| Notebook | Google Colab |
|----------|--------------|
| [Introduction à Python](introduction.ipynb) | [Ouvrir dans Colab](https://colab.research.google.com/github/guzmalalo/colab_python_introduction/blob/main/introduction.ipynb) |
| [NumPy](numpy.ipynb) | [Ouvrir dans Colab](https://colab.research.google.com/github/guzmalalo/colab_python_introduction/blob/main/numpy.ipynb) |
| [Matplotlib](matplotlib.ipynb) | [Ouvrir dans Colab](https://colab.research.google.com/github/guzmalalo/colab_python_introduction/blob/main/matplotlib.ipynb) |


## Exécuter les cellules

- Lisez les cellules de texte et exécutez les cellules Code dans l'ordre avec **▶** ou **Maj + Entrée**.
- Lorsqu'une cellule utilise `input()`, saisissez la valeur demandée.
- Les résultats et les graphiques apparaissent à l'exécution des cellules.
- Les variables restent en mémoire dans le noyau (*kernel*). Après une modification, réexécutez les cellules qui en dépendent. Pour repartir de zéro, redémarrez le noyau et relancez les cellules dans l'ordre.

## Utiliser Jupyter en local

Avec **Python 3**, installez Jupyter et les bibliothèques du cours dans votre environnement :

```bash
python -m pip install notebook numpy matplotlib
```

Depuis le dossier de ce dépôt, lancez :

```bash
python -m notebook
```

Ouvrez ensuite le fichier `.ipynb` souhaité.

## Supports du cours

Les diapositives et les énoncés sont disponibles dans le [dépôt du cours](https://gitlab.com/ece-lyon/formation/ing1-python).

Fait avec :heart: par Eduardo Guzman Maldonado (2026)