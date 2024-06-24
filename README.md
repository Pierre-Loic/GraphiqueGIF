# 🛠️ Création de graphiques animés sous forme de GIF

💻 Lien vers le notebook (pas d'installation nécessaire, le notebook tourne dans votre navigateur, c'est un [Jupyter Lite](https://jupyterlite.readthedocs.io/en/stable/)) : https://pierre-loic.github.io/GraphiqueGIF/

Ce notebook explique comment créer simplement des graphiques animés sous forme de GIF. Seulement **3 bibliothèques Python externes** sont utilisées :

- [numpy](https://numpy.org/doc/stable/) : pour **travailler avec les données** et **stocker temporairement** les images des graphiques

- [matplotlib](https://matplotlib.org) : pour **générer les graphiques** (pour créer plus simplement des graphiques complexes, on peut aussi utiliser [seaborn](https://seaborn.pydata.org))

- [imageio](https://imageio.readthedocs.io/en/stable/) : pour **générer le GIF** final à partir des images des graphiques

Le code est découpé en **deux fonctions** : `create_chart()` pour créer les graphiques individuellement et `create_GIF()` pour créer le GIF.