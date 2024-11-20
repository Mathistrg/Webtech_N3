# Webtech_N3



# nom_du_projet : Organisateur de compétitions amicales

## À propos du projet

nom_du_projet est une application web et mobile conçue pour simplifier l'organisation et la planification de compétitions amicales dans divers sports tels que le football, le basketball et le tennis. Elle offre une plateforme conviviale pour gérer les inscriptions, suivre les scores et planifier les matchs.

## Technologies utilisées

- Backend : PHP Laravel
- Frontend Web : React
- Application Mobile : React Native
- Base de données : SQL

## Fonctionnalités principales

- Inscriptions des équipes et des joueurs
- Tableaux de scores en temps réel
- Calendriers de matchs interactifs

## Installation

```bash
# Cloner le dépôt
git clone https://github.com/votre-nom/nom_du_projet.git

# Installer les dépendances du backend
cd nom_du_projet/backend
composer install

# Configurer la base de données
cp .env.example .env
php artisan key:generate
# Editez le fichier .env avec vos informations de base de données

# Migrer la base de données
php artisan migrate

# Installer les dépendances du frontend web
cd ../frontend-web
npm install

# Installer les dépendances de l'application mobile
cd ../mobile-app
npm install
