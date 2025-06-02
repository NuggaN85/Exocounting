#  Exocounting Discord Bot

Le bot de comptage Discord est conçu pour offrir une expérience de jeu interactive où les utilisateurs peuvent tester leur précision dans divers modes de comptage, y compris les modes décimal, binaire et aléatoire.

## Description

Ce bot permet aux utilisateurs de participer à des jeux de comptage dans différents modes. Les joueurs peuvent compter en décimal, en binaire, ou essayer de deviner un nombre aléatoire. Le bot suit les scores, les tentatives, et attribue des badges en fonction des performances des joueurs.

## Fonctionnalités

- **Modes de Jeu** : Décimal, Binaire, et Aléatoire.
- **Suivi des Scores** : Le bot suit les scores et les tentatives des joueurs.
- **Badges** : Les joueurs peuvent gagner des badges en fonction de leurs performances.
- **Leaderboard** : Affiche les meilleurs scores dans un salon.
- **Relance du Jeu** : Permet de relancer le jeu en cas d'erreur ou pour recommencer.
- **Commandes Slash** : Utilisation de commandes slash pour interagir avec le bot.

## Prérequis

- Node.js (version 16 ou supérieure)
- Un bot Discord (créé via le [Portail Développeur Discord](https://discord.com/developers/applications))
- Les permissions nécessaires pour ajouter le bot à vos serveurs

## Installation

1. Clonez ce dépôt sur votre machine locale.
2. Installez les dépendances nécessaires en exécutant `npm install`.
3. Créez un fichier `.env` à la racine du projet et ajoutez vos variables d'environnement :

```plaintext
DISCORD_TOKEN=VOTRE_TOKEN_DE_BOT
CLIENT_ID=VOTRE_CLIENT_ID
```

4. Exécutez le bot avec la commande `node index.js`.

## Commandes

Le bot utilise des commandes slash pour interagir avec les utilisateurs. Voici les commandes disponibles :

- `/setup_decimal` : Démarrer/réinitialiser le jeu en mode Décimal.
- `/setup_binary` : Démarrer/réinitialiser le jeu en mode Binaire.
- `/setup_random` : Démarrer/réinitialiser le jeu en mode Aléatoire.
- `/relance_decimal` : Relancer le jeu en mode Décimal.
- `/relance_binary` : Relancer le jeu en mode Binaire.
- `/relance_random` : Relancer le jeu en mode Aléatoire.
- `/profile` : Afficher les statistiques de jeu d'un utilisateur.

## Utilisation

1. Invitez le bot sur votre serveur Discord en utilisant le lien OAuth2 généré dans le [Portail Développeur Discord](https://discord.com/developers/applications).
2. Utilisez les commandes slash pour démarrer un jeu dans le mode de votre choix.
3. Suivez les règles du jeu et essayez d'obtenir le meilleur score.
4. Utilisez la commande `/profile` pour afficher vos statistiques et badges.

## Contribution

Les contributions sont les bienvenues ! Pour contribuer à ce projet, veuillez suivre ces étapes :

1. Fork ce dépôt.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Commitez vos changements (`git commit -m 'Add some AmazingFeature'`).
4. Poussez vers la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Contact

Pour toute question ou suggestion, n'hésitez pas à ouvrir une issue ou à me contacter directement.

---

© 2025 Ludovic Rose. Tous droits réservés.
