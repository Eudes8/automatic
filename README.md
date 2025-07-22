

# AUTOMATIC

Entreprise de création de logiciels et d’applications sur mesure.

## Vision
Créer des outils numériques innovants, performants et accessibles pour accompagner la croissance des entreprises et startups.

## Architecture du projet

- **Frontend** : Next.js (TypeScript, Tailwind CSS)
- **Backend** : NestJS (Node.js)
- **Base de données** : Supabase (PostgreSQL)
- **Hébergement** : Vercel (frontend), AWS/Render/Heroku (backend)

## Structure du monorepo

- `/frontend` : Application web Next.js
- `/backend` : API NestJS connectée à Supabase
- `/docs` : Documentation technique et fonctionnelle
- `/design` : Maquettes Figma et ressources UI/UX

## Démarrage rapide

### Prérequis
- Node.js >= 18
- npm >= 9

### Installation

```bash
# Cloner le dépôt
git clone <repo-url>
cd automatic

# Installer les dépendances frontend
cd frontend
npm install

# Installer les dépendances backend
cd ../backend
npm install
```

### Lancer le frontend

```bash
cd frontend
npm run dev
# Accès : http://localhost:3000
```

### Lancer le backend

```bash
cd backend
npm run start:dev
# Accès : http://localhost:3001 (par défaut)
```

### Configuration Supabase

Renseigner les variables d’environnement dans `backend/.env` :

```
SUPABASE_URL=https://ninkgrmrbugjbznjmnei.supabase.co
SUPABASE_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Im5pbmtncm1yYnVnamJ6bmptbmVpIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NDY3MDAwMzYsImV4cCI6MjA2MjI3NjAzNn0.kdex8jc_PWRPRzNA59xuSYBNdwEd6rg9tF1M5M-J9H8
```

## Documentation

Voir le dossier `/docs` pour le cahier des charges, les spécifications et la documentation technique.

## Auteur
Eudes8
