# Projet DevOPS

## Description
Ce projet implémente un serveur HTTP en Node.js. Il expose une route `/ping` qui retourne les headers de la requête en JSON.

## Prérequis
- Node.js 

## Installation et exécution
```bash
npm install
npx tsc
node dist/index.js
```

## Configuration
- La variable d'environnement PING_LISTEN_PORT permet de définir le port d'écoute (par défaut, 8000).

## Fonctionnalités
- Route GET `/ping` : retourne les en-têtes de la requête en format JSON.