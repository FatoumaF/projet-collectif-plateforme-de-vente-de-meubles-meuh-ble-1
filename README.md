# projet-collectif-plateforme-de-vente-de-meubles-meuh-ble-1
# Nom du Projet - Site de Vente de Meubles

## Description

Ce projet est un site de vente de meubles qui offre une expérience utilisateur conviviale pour explorer et acheter une variété de meubles. Le frontend est construit avec React, le backend avec Node.js, et les données sont stockées dans une base de données MongoDB.

## Fonctionnalités

- **Catalogue de Meubles :** Affiche une liste de meubles avec des détails tels que les images, les descriptions et les prix.

- **Panier d'Achats :** Permet aux utilisateurs d'ajouter des meubles à leur panier et de passer une commande.

- **Authentification des Utilisateurs :** Les utilisateurs peuvent créer un compte, se connecter et suivre l'historique de leurs commandes.


## Technologies Utilisées

- **Frontend :** React.js, Redux (facultatif pour la gestion de l'état global).

- **Backend :** Node.js avec Express.js.

- **Base de Données :** MongoDB.

## Installation

1. Clonez ce dépôt sur votre machine locale.

2. Installez les dépendances du frontend en exécutant `npm install` dans le dossier `client`.

3. Installez les dépendances du backend en exécutant `npm install` dans le dossier `server`.

4. Configurez la connexion à la base de données MongoDB dans le fichier `server/config/db.js`.

5. Lancez le serveur backend avec la commande `npm start` dans le dossier `server`.

6. Lancez l'application frontend avec la commande `npm start` dans le dossier `client`.

## Configuration de la Base de Données

1. Assurez-vous que MongoDB est installé et en cours d'exécution sur votre machine ou configurez une instance MongoDB distante.

2. Mettez à jour les informations de connexion dans le fichier `server/config/db.js`.

3. Importez des exemples de données (facultatif) à l'aide des scripts fournis dans le dossier `server/scripts`.

## Structure du Projet

- **`client/` :** Contient le code source du frontend React.

- **`server/` :** Contient le code source du backend Node.js.

- **`server/models/` :** Modèles MongoDB pour les données des meubles, des utilisateurs, etc.

- **`server/controllers/` :** Contrôleurs backend pour gérer les requêtes liées aux meubles, aux utilisateurs, etc.

- **`server/routes/` :** Routes définissant les points d'API pour le frontend.


