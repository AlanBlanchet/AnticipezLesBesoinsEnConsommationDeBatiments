Projet disponible sur [github](https://github.com/AlanBlanchet/AnticipezLesBesoinsEnConsommationDeBatiments)

# Introduction

- Auteur                : Alan Blanchet
- Ecole                 : OpenClassrooms
- Mentor Ecole          : Chemseddine Nabti
- Tuteur entreprise     : Nicolas Grosjean

# Installation

Récupérer le fichier de données [ici](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Data_Scientist_P4/2016_Building_Energy_Benchmarking.csv) et le mettre dans le `root` du projet

Lancer la commande (nécessite [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html))

```bash
conda env create --file environment.yml --force
conda activate oc
```

Il faudra installer jupyter notebook

```bash
conda install -c anaconda jupyter
```

# Execution

```bash
jupyter notebook
```

Il faut lancer le fichier `"analyse.ipynb"` en premier, puis `"prediction.ipynb"`.

- Le fichier d'`analyse` va générer un fichier `cleaned.csv` qui sera par la suite utilisé dans `prediction.ipynb`
- Il y aura des temps d'attentes différents suivant le notebook
    - ~2 mins pour `analyse.ipynb`
    - ~5 mins pour `prediction.ipynb`