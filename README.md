# Végétalisation Paris

Le but de ce projet est d'effectuer une analyse exploratoire à partir des données d'opendata.paris.fr portant sur les arbres de la ville de Paris dans le cadre du programme "Végétalisons la ville".

L'objectif est d'optimiser les tournées d'entretien des arbres en réduisant le nombre de déplacements, ce qui permettra de maintenir davantage d'arbres.


# Installation avec conda
## Création de l'environnement virtuel
```
conda env create -f environment.yml
```

### Ajouter l'environnement dans Jupyter Notebook

```
python -m ipykernel install --user --name=venv

```

### Lancer Jupyter Notebook

```
jupyter notebook
```