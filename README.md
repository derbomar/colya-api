# COLYA API

Minimal clean repo for COLYA API using Express + Prisma + PostgreSQL/Supabase.

## Setup

1. Copy `.env.example` to `.env`
2. Put your real Supabase DB password in `DATABASE_URL`
3. Run:

```bash
npm install
npx prisma generate
npx prisma db push
npm run dev
```

## Routes
- GET /api/v1/parcels
- POST /api/v1/parcels
- GET /api/v1/tracking/:trackingNumber
