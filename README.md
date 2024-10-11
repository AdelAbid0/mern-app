# Application MERN

## Vue d'Ensemble
Ce projet est une application full-stack qui consiste en un client React et un serveur Node.js utilisant MongoDB comme base de données. Docker est utilisé pour la conteneurisation, et Docker Compose est utilisé pour orchestrer les services.

## Table des Matières
- [Technologies Utilisées](#technologies-utilisées)
- [Variables d'Environnement](#variables-denvironnement)
- [Configuration de Docker](#configuration-de-docker)
- [Comment Exécuter le Projet](#comment-executer-le-projet)
- [Contributions](#contributions)

## Technologies Utilisées
- **Frontend** : React
- **Backend** : Node.js, Express
- **Base de Données** : MongoDB
- **Conteneurisation** : Docker, Docker Compose

## Variables d'Environnement
Les variables d'environnement suivantes sont utilisées dans l'application :

- **REACT_APP_API_URL** : Cette variable contient l'URL de base pour le serveur API. Elle est utilisée dans le client React pour faire des requêtes au serveur.
- **MONGO_URI** : L'URI de connexion à MongoDB utilisée par le serveur pour se connecter à l'instance MongoDB.

## Configuration de Docker
Ce projet comprend des Dockerfiles pour le client et le serveur, qui facilitent la construction et l'exécution des services dans des conteneurs isolés. Les configurations incluent :

- **Client** : Un environnement Node.js pour construire l'application React. Les dépendances sont installées et l'application est construite pour une utilisation en production. Un serveur HTTP simple peut être utilisé pour servir l'application construite.
  
- **Serveur** : Un environnement Node.js qui installe les dépendances nécessaires et configure l'application pour écouter sur un port spécifique.

## Docker Compose
Docker Compose est utilisé pour gérer les différents services de l'application, y compris le client, le serveur et MongoDB. Les services sont interconnectés, ce qui permet une communication fluide entre le client et le serveur. Le fichier de configuration spécifie les images, les ports exposés, ainsi que les variables d'environnement nécessaires pour chaque service.

## Comment Exécuter le Projet
1. Assurez-vous d'avoir Docker et Docker Compose installés sur votre machine.
2. Clonez ce dépôt sur votre machine locale.
3. Accédez au répertoire du projet dans votre terminal.
4. Construisez et démarrez l'application en utilisant Docker Compose :

   ```bash
   docker-compose up --build
   ```

5. Accédez au client à [http://localhost:3000](http://localhost:3000).

## Contributions
N'hésitez pas à soumettre des problèmes ou des demandes de tirage pour améliorer ce projet.
```

### Utilisation du README :
1. **Copier et Coller** : Vous pouvez copier ce texte dans un fichier nommé `README.md` à la racine de votre répertoire de projet.
2. **Personnaliser** : Remplacez "Nom du Projet" par le nom réel de votre projet et modifiez les sections si nécessaire pour répondre aux spécificités de votre application.
3. **Ajouter des Sections Supplémentaires** : Si votre projet nécessite des instructions ou une documentation supplémentaire, n'hésitez pas à ajouter des sections.