# Projet AppResto

## Introduction

Le projet **AppResto** est une application web développée dans le cadre du module **Ateliers de Professionnalisation (AP.SLAM)** en **BTS SIO 2ème année** à l'Institut LIMAYRAC, durant l'année scolaire 2025/2026.

L'objectif final est de proposer une application permettant à un client de commander des produits auprès d’un restaurateur, avec un suivi de commande pour les deux parties.  
**Dans l’état actuel, le travail est exclusivement centré sur la phase de conception (Lot 1).**

---

## Description Générale du Besoin

* **Côté Client** : inscription, connexion, consultation des produits, choix des quantités, commande sur place ou à emporter, paiement fictif.
* **Côté Restaurateur** : gestion des commandes (accepter, refuser, préparer).
* **Notification** : alerte par e-mail lorsque la commande est prête pour retrait.

---

## Fonctionnalités Ciblées (Vision Globale du Projet)

Ces fonctionnalités ne sont pas encore développées mais représentent l’objectif final :

- Gestion des utilisateurs (inscription, connexion, déconnexion).
- Affichage et sélection de produits.
- Commande avec options (sur place / à emporter).
- Calcul automatique du total TTC (avec TVA à 5,5% ou 10% selon le type de commande).
- Paiement fictif par carte bancaire.
- Gestion des commandes côté restaurateur.
- Notification e-mail au client.
- Suivi et finalisation de commande.

---

## Gestion de la TVA

- **5,5%** : commande à emporter.  
- **10%** : consommation sur place.  
- Le taux est **uniforme par commande**.  
[Référence : economie.gouv.fr – TVA réduite restauration](https://www.economie.gouv.fr/cedef/tva-reduite-restauration)

---

## Lotissement du Projet

Le projet est prévu en plusieurs lots, mais **actuellement seul le Lot 1 est en cours de réalisation** :


### **Lot 1 : Conception Initiale (Phase Actuelle)**
  - Diagramme des cas d’utilisation.
  - Diagramme d’activités (processus de commande).
  - Modèle Conceptuel des Données (MCD).
  - Modèle Logique des Données (MLD).
  - Interface Homme-Machine (IHM).
  - Sitemap (enchaînement des pages).

### Lot 2 – Développement initial
- Modèle Physique de Données (MPD) au format SQL
- Pages HTML/CSS statiques
- Lotissement Trello des tâches
- Préparation des interfaces pour login et register

### Lot 3 – Développement initial
- La page d'accueil (`index.php`) qui est la page par défaut du site
- La page d'inscription (`inscription.php`) qui permet de créer un compte sur le site
- La page de connexion(`connexion.php`) qui permet de se connecter à son compte
- La page de déconnexion (`deconnexion.php`) qui permet de se déconnecter de son compte
- La page de la liste des produits (`commander.php`) qui permet de choisir ses produits
- Lotissement Trello des tâches

### Lot 4 – Développement du processus de commande
- La page de la liste des produits (`commander.php`) qui permet de commander ses produits.
- La page de paiement (`payer.php`) qui permet de payer sa commande.
- La page de confirmation (`confirmer.php`) qui permet de confirmer que la commande est prise en compte.
- Le lotissement sous Trello à jour avec un accès pour l'enseignant.

### Lot 5 – L'API est l'interface de "RestoWeb" avec "RestoSwing"

- L'application graphique Java utilisée en cuisine pour gérer les commandes.
- Liste des commandes en attente ('commandes_en_attente.php')
- Refuser une commande ('commande_refuser.php")
- Accepter une commande ('commande_accepter.php')
- Terminer une commande ('commande_terminer.php')
- Lotissement Trello des tâches

### Lot 6 - Documentation de l'application

- Le diagramme des cas d'utilisation
- Le modèle conceptuel des données (looping ou équivalent)
- Le modèle logique des données (PHPMyAdmin ou équivalent)
- Le modèle physique des données (script(s) SQL)
- Les états des commandes
- Les types de conso. (sur place/à emporter)
- Le sitemap (enchaînement des pages)
- Les maquettes de l'IHM (Balsamiq ou équivalent)
- La maquette JSON et si nécessaire les différents messages d'erreur si une réponse est notifiée
- Le manuel d'installation :
. Les releases ou la branche git à utiliser
. Copie de l'application dans le serveur web
. Exécution des scripts SQL pour installer la base, les triggers et les données
. Le paramétrage éventuel de l'application
- Le manuel du jeu de test
. Quel sont les user/password installés pour les tests
. Quels sont les données existantes pour les tests

### Lot 7 - Application Java RestoSwing

- Développer une application Java Swing permettant de gérer les commandes.
- Consommer l’API REST de RestoWeb.
- Manipuler des objets métiers à partir de réponses JSON.
- Organiser le travail via un lotissement Trello.
  

---
*Les autres lots seront réalisés ultérieurement.*

---

## Auteurs et Contact

- **Étudiants** : Dutertre Dorian, Tesnim Benama, Selim Nouira  
- **Encadrants** : Christophe PUEL, Jean-François RAMIARA  
- **Établissement** : Institut LIMAYRAC  
- **Formation** : BTS SIO 2ème année – Option SLAM  
- **Année scolaire** : 2025/2026  
