# SimulEntretien

Application de simulation d'entretien avec IA

## Prérequis

- Docker
- Docker Compose

## Installation

1. Cloner le repository
2. Se placer dans le dossier du projet
3. Lancer les conteneurs avec Docker Compose :

```bash
docker-compose up --build
```

## Accès aux services

- Frontend : http://localhost:3000
- Backend API : http://localhost:5000
- Base de données PostgreSQL : localhost:5432

## Structure du projet

```
simulentretien/
├── frontend/          # Application React
├── backend/           # API Flask
└── docker-compose.yml # Configuration Docker
```

## Développement

- Le frontend est accessible sur le port 3000
- Le backend est accessible sur le port 5000
- Les modifications des fichiers sont reflétées en temps réel grâce aux volumes Docker 