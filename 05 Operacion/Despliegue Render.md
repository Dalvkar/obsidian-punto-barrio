---
tipo: operacion
estado: activo
tags: [punto-barrio, render]
---

# Despliegue Render

## Backend

- Build: `npm ci --include=dev && npm run db:generate && npm run build`
- Start: `npm run render:start`
- Health: `/api/health`

## Frontend

- Build: `npm ci && npm run build`
- Publish: `dist`
- API: `VITE_API_URL=https://punto-barrio-backend.onrender.com/api`

## Smoke test

- `/api/health` → 200.
- `/api/suppliers` → 200.
- `/api/customers` → 200.

Ver [[05 Operacion/Incidentes y Aprendizajes]].
