Voici une proposition de fichier `README.md` pour votre projet de régression logistique :

---

# Implémentation de Régression Logistique : Analyse de Survie du Titanic

## Description du Projet

Ce projet consiste en l'implémentation complète d'un modèle de régression logistique binaire appliqué au célèbre jeu de données du Titanic. L'objectif principal est de prédire la probabilité de survie des passagers en fonction de leur âge, tout en comparant différentes méthodes d'optimisation numérique pour l'estimation des paramètres.

## Objectifs Pédagogiques

* Préparation et nettoyage de données réelles (gestion des valeurs manquantes).
* Implémentation "from scratch" d'algorithmes d'optimisation.
* Analyse statistique des coefficients et interprétation des résultats.
* Validation du modèle via des outils standards (Scikit-learn) et des métriques de performance.

## Méthodologie et Algorithmes

Le projet compare deux approches principales pour la maximisation de la log-vraisemblance :

1. **Descente de Gradient** : Implémentation avec ajustement du signe pour la maximisation.
2. **Méthode de Newton** : Utilisation de la matrice Hessienne avec une preuve mathématique rigoureuse de la concavité de la fonction cible pour garantir la convergence.

## Résultats Clés

* **Performance des Algorithmes** : La méthode de Newton s'est révélée environ 100 fois plus rapide que la descente de gradient pour atteindre la convergence.
* **Interprétation Statistique** : L'analyse montre un effet négatif de l'âge sur la probabilité de survie (coefficient β1 ≈ -0.015), confirmant que les passagers plus jeunes avaient statistiquement plus de chances de survivre.
* **Évaluation** : Le modèle obtient une aire sous la courbe (AUC) de 0.62.

## Technologies Utilisées

* **Langage** : Python 3
* **Bibliothèques** :
* Numpy et Pandas (Manipulation de données)
* Matplotlib et Seaborn (Visualisation et graphiques)
* Scikit-learn (Validation croisée et comparaison)



## Auteur et Cadre

* **Réalisé par** : Ouertani Mariem (RT3)
* **Enseignante** : Mme. S. Toumi
* **Institution** : Institut National des Sciences Appliquées et de Technologie (INSAT)

---

Ce fichier résume les points essentiels de votre notebook.
