# SportSee

SportSee est un tableau de bord analytique pour sportifs, développé dans le cadre de la formation Développeur Front-End React chez OpenClassrooms.

## Sommaire

- [Présentation](#présentation)
- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du projet](#structure-du-projet)
- [Technologies](#technologies)
- [Auteurs](#auteurs)

## Présentation

SportSee permet de visualiser les performances sportives d’un utilisateur à travers différents graphiques interactifs (activité quotidienne, sessions, performances, score). L’application consomme une API REST pour récupérer les données.

## Fonctionnalités

- Tableau de bord personnalisé pour chaque utilisateur
- Graphiques dynamiques (activité, sessions, performances, score)
- Responsive design
- Composants réutilisables avec React
- Gestion des états avec React

## Prérequis

- Node.js (>= 14.x)
- npm ou yarn
- [Backend SportSee](https://github.com/OpenClassrooms-Student-Center/P9-front-end-dashboard) (API à lancer séparément)

## Installation

1. **Cloner le projet :**
    ```bash
    git clone https://github.com/votre-utilisateur/SportSee.git
    cd SportSee
    ```

2. **Installer les dépendances :**
    ```bash
    npm install
    # ou
    yarn install
    ```

3. **Lancer le backend :**
    Suivre les instructions du dépôt backend pour démarrer l’API.

4. **Lancer l’application :**
    ```bash
    npm start
    # ou
    yarn start
    ```

5. Accéder à [http://localhost:3000](http://localhost:3000)

## Utilisation

- Sélectionner un utilisateur pour afficher ses statistiques.
- Naviguer entre les différents graphiques pour analyser les performances.

## Structure du projet

```
SportSee/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── styles/
│   ├── App.jsx
│   └── main.jsx
├── package.json
└── README.md
```

## Technologies

- React
- Recharts
- Sass
- JavaScript

## Auteurs

Projet réalisé dans le cadre de la formation OpenClassrooms.

- Nino LITIM
- https://github.com/Ninol13/SportSee

---

© 2025 SportSee - OpenClassrooms