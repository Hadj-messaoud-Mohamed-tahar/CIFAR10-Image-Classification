# Classification d'Images CIFAR-10 avec CNN

## Description
Ce projet utilise un réseau de neurones convolutifs (CNN) pour classifier les images du dataset CIFAR-10 en utilisant TensorFlow et Keras.

Le dataset CIFAR-10 contient 60 000 images couleur de 32x32 réparties en 10 classes : 
- Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck.

## Fonctionnalités
- Visualisation aléatoire des images avec leurs étiquettes.
- Prétraitement des données (normalisation et catégorisation).
- Modélisation avec des couches convolutives, de pooling, de normalisation et dense.
- Entraînement avec un optimiseur SGD.
- Évaluation des performances à l'aide d'un rapport de classification et d'une matrice de confusion.
- Visualisation des prédictions sur des images tests.

## Technologies utilisées
- **Langage** : Python
- **Frameworks et bibliothèques** :
  - TensorFlow/Keras : Modélisation et entraînement du CNN.
  - NumPy : Manipulation des données.
  - Matplotlib : Visualisation des images.
  - Scikit-learn : Analyse des performances du modèle.

## Prérequis
1. Python (3.7 ou plus récent).
2. Installation des dépendances via `requirements.txt`.

## Installation
1. Clonez ce dépôt :
   ```bash
   git clone  https://github.com/Hadj-messaoud-Mohamed-tahar/CIFAR10-Image-Classification.git
   cd classification-cifar10
