# Le voyageur de commerce

## Description

![caption](https://raw.githubusercontent.com/diego-vicente/som-tsp/master/diagrams/uruguay.gif)

Étant donné un ensemble de villes et les distances séparant chaque paire de villes, le Problème duVoyageur de Commerce (PVC) consiste à trouver le circuit de distance minimale visitant toutes lesvilles exactement une fois et revenant à la ville de départ.Ci-dessous la formulation du problème basée sur la programmation linéaire en nombres entiers.

![caption](https://i0.wp.com/ecmiindmath.org/wp-content/uploads/2015/04/rest2.png?ssl=1)

Le but est de trouver une solution réalisable pour ce problème.

## Prérequis

- `Python `
- `gurobipy `
- `Pandas`
- `numpy `

## Contenu

Ce dépôt contient:
* **Data** :contient l'ensemble des données utilisées dans ce projet.
* **Model.py** :est la résolution du modèle ci_dessus avec l'aide du solver GUROBI.
* **Enum.py** :est l'implementation de l'algorithme d'énumération.
* **B&B.py** :est l'implementation de l'algorithme de Branch and bound.
* **Main.py** :est l'environnement d'exécution principale.

Ce code est sous licence MIT, n’hésitez donc pas à le modifier et/ou à l’utiliser dans vos projets. Si vous avez des doutes, n’hésitez pas à me contacter ou à contribuer à ce dépôt en créant un problème.

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com) 
