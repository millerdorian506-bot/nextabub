# NexaHub - Full Project (Template)

This ZIP contains a full-stack NexaHub project (backend + frontend).

## Quick start (local)

1. Backend
   - cd backend
   - npm install
   - update .env DATABASE_URL to your Postgres
   - npx prisma generate
   - npx prisma migrate dev --name init
   - npm run seed
   - npm run dev

2. Frontend
   - cd frontend
   - npm install
   - npm run dev
   - open http://localhost:3000

Notes:
- This template uses PostgreSQL. For fast local testing you can change datasource in prisma/schema.prisma to sqlite.
- Seed creates admin: admin@nexahub.store / AdminPass123!
