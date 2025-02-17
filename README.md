# Docker-

# Pizza Menu Application with Docker

Une application Flask pour afficher un menu de pizzas avec une interface web. Les informations des pizzas (nom, prix, image) sont récupérées depuis une base de données MySQL. Le projet est conteneurisé à l'aide de Docker et Docker Compose.

## Fonctionnalités

- Affichage d'un menu de pizzas avec image, nom et prix.
- Récupération des informations depuis une base de données MySQL.
- Ajout de nouvelles pizzas via une API REST.
- CORS activé pour permettre les requêtes depuis d'autres origines.
- Conteneurisation complète avec Docker pour l'API Flask et la base de données MySQL.

## Structure du projet

 **Docker/**
 - **api.py** : Fichier principal du serveur Flask avec les routes API.
 - **templates/index.html** : Fichier HTML pour afficher le menu des pizzas
 - **static/images/** : Dossier contenant les images des pizzas
 - **.env** : Variables d'environnement (DB_HOST, DB_USER, DB_PASSWORD, DB_NAME)
 - **pizza_db.sql** : Script SQL pour la création de la base de données et de la table pizza
 - **requirements.txt** : Dépendances Python nécessaires pour le projet
 - **Dockerfile** : Fichier pour construire l'image Docker pour l'application Flask
 - **docker-compose.yml** : Fichier Docker Compose pour définir les services (API et MySQL)
 - **README.md** : Documentation du projet



