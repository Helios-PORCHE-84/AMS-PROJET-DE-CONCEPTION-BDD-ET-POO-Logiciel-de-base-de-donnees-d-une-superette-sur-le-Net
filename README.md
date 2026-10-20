# AMS PROJET DE CONCEPTION BDD ET POO Logiciel de base de données d'une supérette sur le Net.

Contexte & Objectif : 

Projet d'équipe (L1, AMS Conception BDD et POO). Conception et développement d'une application console de gestion des stocks et des ventes pour une supérette.


Détails Techniques & Concepts Clés :

• Modélisation : Passage d'un besoin métier à un Modèle Conceptuel de Données, puis normalisation jusqu'à la 4ème Forme Normale (4NF) pour éviter la redondance.

• Programmation Orientée Objet (Java) : Création de classes mères et filles correspondant aux tables de la base de données.

• SGBD et SQL : Interaction avec une base de données relationnelle via des requêtes SQL (CRUD : Create, Read, Update, Delete). 


Cheminement de réalisation (Synopsis) :

1. Analyse et Conception : Lecture du cahier des charges, listage des entités (Produits, Fournisseurs, Achats, Contacts) et dessin des schémas relationnels.

2. Architecture du code : Création des classes Java (mapping) les tables de la BDD avec leurs attributs et constructeurs.

3. Connexion et Initialisation : Développement d'une fonction vérifiant l'existence de la BDD et créant les tables si nécessaire.

4. Développement des fonctionnalités (CRUD) :

• Ajout : Saisie utilisateur dans le terminal et génération de requêtes INSERT INTO.

• Affichage : Requêtes SELECT avec jointures pour regrouper les données (ex: plusieurs contacts par entreprise).

• Modification/Suppression : Recherche par identifiant unique puis requêtes UPDATE ou DELETE.

5. Interface Utilisateur : Création d'un système de navigation par menus chiffrés (switch case) dans le terminal.


