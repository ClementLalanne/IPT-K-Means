# IPT-K-Means

Vous trouverez ici tous les exemples que j'ai pu utiliser lors de mon exposé.
Ils sont présentés sous forme d'un notebook Python.
Si vous ne savez pas ce qu'est un notebook, il s'agit d'un outil bien pratique
qui permet d'écrire des cases de code avec des cases de texte. Ici les cases de
code contiennent du code Python et les cases de texte permettent d'écrire en
Markdown. Il est aussi possible d'y écrire des formules simples en Latex !
Ceci en fait un super outil pour un projet qui n'est pas trop ambitieux et
qui n'a pas trop de dépendances tels que les TP's.

Nous allons voir en détail comment installer les différents outils dont nous
avons besoin pour les expériences.
Quand je parlerai de Linux, je parlerai des systèmes Ubuntu-like.
De toute manière si vous utilisez autre-chose vous êtes sûrement capables d'installer
les packages vous-même ;)

## Le Langage de programmation

Tout d'abord le langage `Python 3` ! Vous pouvez le trouver
[ici](https://www.python.org/downloads/). Faites bien attention à l'installer
de manière compatible avec votre système d'exploitation.

Si vous utilisez Mac, je vous recommande d'installer Python en utilisant
Homebrew. Qu'est-ce que Homebrew ? Il s'agit d'un gestionnaire de paquets pour
Mac car Apple n'en fournit pas nativement.
[Ce site](http://docs.python-guide.org/en/latest/starting/install3/osx/)
détaille toute la procédure.

Sur Linux vous avez simplement à taper dans le terminal
```
sudo apt-get update
sudo apt-get install python3.6
```
Pour la version 3.6 par exemple.

## Le gestionnaire de paquets pip3

`Python` possède un gestionnaire de paquets qui permet d'installer les différentes
bibliothèques que nous allons utiliser et de les mettre à jour. Il s'agit de
`pip`.

Sur Mac, le [lien d'installation](http://docs.python-guide.org/en/latest/starting/install3/osx/)
de `Python` explique aussi comment installer `pip3`.

Enfin sur Linux, tapez la commande suivante
```
sudo apt-get -y install python3-pip
```

## Installation des bibliothèques

```
python3 -m pip install --user numpy scipy matplotlib ipython jupyter scikit-learn
```
- `Numpy`: Permet de faire des calculs sur des tableaux à n dimensions (`ndarray`).
La bibliothèques est écrite en C++ et est extrèmement optimisée. Elle permet de faire des calculs beaucoup
plus vite que les listes Python.
[Site officiel](http://www.numpy.org/)
- `Scipy`: Est une bibliothèque permettant de faire du calcul scientifique avec les tableaux `numpy`.
[Site officiel](https://www.scipy.org/)
-`Matplotlib`: Permet d'afficher des résultats (faire des graphiques en 2D ou 3D).
[Site officiel](https://matplotlib.org/)
-`Ipython`: Met à disposition un environement appelé "Notebook" permettant d'utiliser `Python`
de manière interractive.
[Site officiel](https://ipython.org/)
- `Jupyter`: Similaire à `ipython`. Vous pouvez trouver les détails techniques [ici](https://www.datacamp.com/community/blog/ipython-jupyter).
[Site officiel](http://jupyter.org/)
- `Scikit-learn`: Une bibliothèque d'algorithmes simples de machine learning.
[Site officiel](http://scikit-learn.org/stable/)

## Utilisation

- Téléchargez les différents fichiers: Sur la page `Git` du projet vous avec en haut à droite
la possibilité de télécharger une archive du projet. Vous pouvez aussi cloner le projet si vous êtes plus à l'aise
avec `Git` et ainsi vous pourrez mettre automatiquement à jour les fichiers.
- Dans un terminal, tapez la commande suivante à la racine du projet:
```
ipython notebook
```
Il y a deux possibilités: Soit votre navigateur s'ouvre automatiquement, soit votre terminal vous
donne une adresse à laquelle vous devez vous connecter en localhost depuis votre navigateur.
Voilà, vous venez d'ouvrir le projet !
- Maintenant vous vous trouvez dans un `Notebook`. Vous pouvez faire de l'exécution interractive de code.
Vous pouvez aussi écrire du texte selon des conventions `Markdown`.
Vous pouvez exécuter une célule en appuyant sur `MAJ + ENTER`.


Nous en avons donc fini avec ce tutoriel. Si vous avez des questions ou des remarques, n'hésitez pas à me contacter.
Vous trouverez mon adresse mail sur [ma page perso](https://clementlalanne.github.io/).
