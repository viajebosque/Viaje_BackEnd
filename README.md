# Viaje_BackEnd

API Node + Express para **Un Viaje por el Bosque**. Usa Supabase (supabase-js) y despliega en Railway.

## Local

```bash
npm install
cp .env.example .env   # rellena SUPABASE_URL y SUPABASE_SERVICE_ROLE_KEY
npm run dev
```

- `GET /health` → health check (usado por Railway)
- `GET /api/ping-db` → verifica conexión a Supabase

## Ambientes

| Branch | Railway    | Supabase   |
|--------|------------|------------|
| `dev`  | Viaje_Dev  | Viaje_Dev  |
| `main` | Viaje_Prod | Viaje_Prod |

Variables se configuran en Railway (no en el repo). Ver `.env.example`.
