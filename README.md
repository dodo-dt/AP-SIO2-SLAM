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
-La page d'accueil (index.php) qui est la page par défaut du site
-La page d'inscription (inscription.php) qui permet de créer un compte sur le site
-La page de connexion(connexion.php) qui permet de se connecter à son compte
-La page de déconnexion (deconnexion.php) qui permet de se déconnecter de son compte
-La page de la liste des produits (commander.php) qui permet de choisir ses produits
- Lotissement Trello des tâches


---
*Les autres lots seront réalisés ultérieurement.*

---

## Auteurs et Contact

- **Étudiants** : Dutertre Dorian, Tesnim Benama, Selim Nouira  
- **Encadrants** : Christophe PUEL, Jean-François RAMIARA  
- **Établissement** : Institut LIMAYRAC  
- **Formation** : BTS SIO 2ème année – Option SLAM  
- **Année scolaire** : 2025/2026  
