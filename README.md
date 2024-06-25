# 🛠️ Création de graphiques animés sous forme de GIF

Vous avez plusieurs possibilités pour utiliser ce notebook :

- 💻 Directement dans votre navigateur sans installation (utilisation de [Jupyter Lite](https://jupyterlite.readthedocs.io/en/stable/)) : https://pierre-loic.github.io/GraphiqueGIF/

- 🌐 Avec Colaboratory (nécessite un compte Google) : <a href="https://colab.research.google.com/github/Pierre-Loic/GraphiqueGIF/blob/main/content/Notebook_GIF.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="25px"/>
</a>

- 🖥️ En local, dans un **environnement virtuel** en clonant ce dépôt GIT et utilisant le fichier `requirements.txt` pour installer les bibliothèques Python nécessaires

___

Ce notebook explique comment créer simplement des graphiques animés sous forme de GIF. Seulement **3 bibliothèques Python externes** sont utilisées :

- [numpy](https://numpy.org/doc/stable/) : pour **travailler avec les données** et **stocker temporairement** les images des graphiques

- [matplotlib](https://matplotlib.org) : pour **générer les graphiques** (pour créer plus simplement des graphiques complexes, on peut aussi utiliser [seaborn](https://seaborn.pydata.org))

- [imageio](https://imageio.readthedocs.io/en/stable/) : pour **générer le GIF** final à partir des images des graphiques

Le code est découpé en **deux fonctions** : `create_chart()` pour créer les graphiques individuellement et `create_GIF()` pour créer le GIF.