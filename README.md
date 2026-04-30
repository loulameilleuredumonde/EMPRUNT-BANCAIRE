# EMPRUNT-BANCAIRE
 Compte rendu – Simulation de crédit en C++


Dans le cadre de ce projet, nous avons développé un programme en langage C++ permettant de simuler un crédit immobilier. L’objectif principal était de comparer différentes offres bancaires en fonction d’un capital emprunté, de plusieurs durées et de taux d’intérêt, afin d’identifier la meilleure solution pour l’utilisateur.

Ce projet nous a également permis de mettre en pratique les concepts fondamentaux de la programmation orientée objet (POO), ainsi que la gestion des entrées/sorties et l’organisation d’un programme structuré. Enfin, nous avons utilisé GitHub pour gérer les versions du projet et faciliter le travail collaboratif.


1. Analyse du besoin

Avant de commencer le codage, nous avons défini les fonctionnalités attendues :

* Saisir les informations de l’utilisateur (nom, prénom, capital, banque, taux).
* Proposer plusieurs banques avec des taux fixes.
* Permettre l’ajout d’une banque personnelle.
* Calculer les mensualités pour différentes durées (10, 15 et 20 ans).
* Comparer les offres et déterminer la meilleure.



2. Conception du programme

Nous avons structuré le programme en plusieurs classes afin de respecter les principes de la programmation orientée objet :

 classe *emprunt*
Cette classe gère les calculs liés au crédit :

* Calcul de la mensualité
* Calcul du coût total du prêt

Elle utilise une formule mathématique basée sur les intérêts composés.

Classe *Utilisateur*

Elle permet de :

* Stocker les informations de l’utilisateur
* Saisir les données via le clavier
* Ajouter une banque personnalisée

Classe *simulation crédit*

Cette classe est responsable de :

* Stocker les banques disponibles
* Générer un tableau comparatif des offres
* Identifier la meilleure offre selon les résultats



 3. Implémentation

Le programme a été développé en C++ en utilisant :

* Les bibliothèques standard (`iostream`, `iomanip`, `string`)
* Des tableaux pour stocker les banques
* Des boucles pour générer les simulations
* Des fonctions pour organiser le code

Nous avons également amélioré le programme en :

* Sécurisant l’ajout de banques pour éviter les dépassements de tableau
* Utilisant la fonction `pow()` pour un calcul plus précis
* Améliorant l’affichage des résultats sous forme de tableau



4. Utilisation de GitHub

Nous avons utilisé GitHub pour :

* Sauvegarder régulièrement notre code
* Gérer les différentes versions du projet
* Suivre les modifications apportées
* Faciliter la collaboration

Cela nous a permis de travailler de manière plus organisée et de revenir facilement à une version précédente en cas d’erreur.



5. Résultats obtenus

Le programme permet :

* D’afficher un tableau comparatif clair des différentes offres
* De visualiser les mensualités pour chaque banque et chaque durée
* D’identifier automatiquement la meilleure offre
* De calculer :

  * La mensualité minimale
  * Le coût total du crédit
  * Les intérêts payés

L’utilisateur peut ainsi prendre une décision éclairée en fonction des différentes propositions.



 Conclusion

Ce projet nous a permis de consolider nos compétences en C++, notamment en programmation orientée objet et en structuration du code. Nous avons également appris à corriger des erreurs, optimiser les calculs et améliorer la lisibilité du programme.

L’utilisation de GitHub a été un véritable atout pour la gestion du projet, en apportant rigueur et organisation.

Enfin, ce travail nous a permis de mieux comprendre le fonctionnement des crédits et des taux d’intérêt, tout en développant un outil pratique et fonctionnel.
