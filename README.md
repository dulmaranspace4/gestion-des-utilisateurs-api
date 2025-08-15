# Gestion des Utilisateurs API

Bienvenue dans le projet **Gestion des Utilisateurs API**. Cette API RESTful vous permettra de gérer des utilisateurs via des endpoints simples et efficaces.

## Fonctionnalités
- Inscription des utilisateurs
- Authentification
- Récupération et mise à jour des profils

## Installation
Assurez-vous d'avoir Node.js et npm installés. Suivez les étapes ci-dessous :

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/gestion-des-utilisateurs-api.git
   cd gestion-des-utilisateurs-api
   ```
2. Installez les dépendances :
   ```bash
   npm install
   ```
3. Démarrez le serveur :
   ```bash
   npm start
   ```

## API
### Inscription de l'utilisateur
- **POST** `/api/utilisateurs`

### Connexion
- **POST** `/api/login`

### Récupération du profil
- **GET** `/api/utilisateurs/:id`

### Mise à jour du profil
- **PUT** `/api/utilisateurs/:id`

## Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à soumettre un pull request.

## License
Ce projet est sous license MIT.