# Notes-V2

Application de prise de notes — monorepo.

| Dossier | Stack | Lancer en local |
|---|---|---|
| [`backend/`](backend) | Spring Boot 3 · Java 21 · PostgreSQL | `cd backend && ./mvnw spring-boot:run` |
| [`frontend/`](frontend) | Angular · Tailwind | `cd frontend && npm install && npm start` |

Déploiement sur le VPS via GitHub Actions (`.github/workflows/`), déclenché par un push sur `develop` touchant le dossier concerné.

Historique : fusion des anciens dépôts `Spring-Notes-V2` et `Angular-Notes-V2`, historique complet conservé.
