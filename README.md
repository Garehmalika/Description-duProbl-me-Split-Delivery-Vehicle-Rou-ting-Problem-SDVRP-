Split Delivery Vehicle Routing Problem (SD-VRP)

Description du Projet

Dans le cadre du cours Optimisation combinatoire, ce projet vise à résoudre le problème du Split Delivery Vehicle Routing Problem (SD-VRP). Le SD-VRP est une extension du problème classique de tournée de véhicules à capacité limitée (CVRP), qui permet de répartir les livraisons d’un client entre plusieurs véhicules tout en satisfaisant pleinement sa demande.

Ce projet comporte trois étapes principales :

Modélisation mathématique du SD-VRP

Résolution du problème via un solveur

Utilisation d’une (méta)heuristique pour améliorer la performance

Méthodologie

1. Modélisation mathématique

Le problème a été formulé avec des variables de décision binaires (xi,j,k) et continues (yi,k).

Les contraintes incluent :

Capacité des véhicules

Satisfaction des demandes clients

Équilibre des flux

2. Implémentation du Solveur

Le modèle a été implémenté en Python avec la bibliothèque PuLP.

Le solveur utilisé est CBC (Coin-or Branch and Cut), qui permet d'obtenir une solution optimale.

Le fichier du modèle mathématique est disponible au format .lp.

Détails du code : voir Code_Solveur.ipynb.

3. Métaheuristique (Algorithme Tabou)

Une approche basée sur l'algorithme tabou a été développée pour résoudre des instances plus complexes.

Cette méthode a été appliquée à différentes instances pour comparer ses performances avec le solveur exact.

Détails du code : voir Code_(méta)heuristique.ipynb.

4. Heuristique Solomon

Une heuristique Solomon a été implémentée pour fournir une borne supérieure et tester les performances.

Détails du code disponibles dans les fichiers du projet.
