# IPT-K-Means

Vous trouverez ici touts les exemples que j'ai pu utiliser lors de mon exposé.
Il sont présentés sous forme d'un notebook Python.
Si vous ne savez pas ce qu'est un notebook, il s'agit d'un outil bien pratique
qui permet d'écrire des cases de code avec des cases de texte. Ici les cases de
code contiennent du code Python et les cases de texte permettent d'écrire en
Markdown. Il est aussi possible d'y écrire des formules simples en Latex !
Ceci en fait un super outil pour les projets qui ne sont pas trop ambitieux et
qui n'ont pas trop de dépendences tels que les TP's.

Nous allons voir en détail comment installer les différents outils dont nous
avons besoin pour les expériences.
Dans la suite je vais détailler comment installer et utiliser les outils que nous allons utiliser.
Quand je parle de Linux, je parle des systèmes Ubuntu-like. De toute manière si vous utilises autre-chose vous êtes sûrement capables d'installer
les packages vous-même ;)

## Le Langage de programmation

Tout d'abord le langage Python 3 ! Vous pouvez le trouver
[ici](https://www.python.org/downloads/). Faites bien attention à l'installer
de manière compatible avec votre système d'exploitation.

Si vous utilisez Mac, je vous recommende d'installer Python en utilisant
Homebrew. Qu'est-ce que Homebrew ? Il s'agit d'un gertionnaire de paquets pour
Mac car Apple n'en fournit pas nativement.
[Ce site](http://docs.python-guide.org/en/latest/starting/install3/osx/)
détaille toute la procédure.

Sur linux vous avez simplement à taper dans le terminal
```
sudo apt-get update
sudo apt-get install python3.6
```
Pour la version 3.6 par exemple.

## Le gestionnaire de paquets pip3

Python possède un gertionnaire de paquets qui permet d'installer les différentes
bibliothèques que nous allons utiliser et de les mettre à jour. Il s'agit de
pip.

Sur mac, le [lien d'installation](http://docs.python-guide.org/en/latest/starting/install3/osx/)
de Python explique aussi comment installer pip3.

Enfin sur linux, tapez la commande suivante
```
sudo apt-get -y install python3-pip
```

## IPython Notebook

Pour installer les outils ipython vous pouvez maintenant taper la commande suivante
```
pip3 install ipython
```
Pour lancer ipython, tapez ensuite
```
ipython notebook
```
Ceci devrait ouvrir l'application dans votre navigateur ou vous donner l'url
en locahost pour vous y connecter.

## Numpy

Numpy est un bibliothèque qui propose des calculs sur des tableaux à n dimensions
(ndarray). Cette bibliothèque est écrite en C++ et est extrèmement optimisées.
Elle permet de réaliser des calculs beaucoup plus rapidement qu'avec les listes
Python.
```
pip3 install numpy
```

## Matplotlib

Matplotlib est une bibliothèque qui permet de réaliser des graphiques. Elle
marche très bien en complément de Numpy.
```
sudo apt-get install libfreetype6-dev libxft-dev
pip3 install matplotlib
```

## Scipy

Scipy est une bibliothèque qui permet de faire du calcul scientifique.
```
python -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose
```

## Sklearn

SKlearn est une bibliothèque qui regroupe des algorithmes classiques d'apprentissage.
```
pip3 install -U scikit-learn
```
