---
tipo: arquitectura
estado: estable
tags: [punto-barrio, arquitectura]
---

# Arquitectura

```text
React + Vite → API Express /api → Prisma → PostgreSQL
     Render          Render          Render DB
```

## Responsabilidades

| Capa | Responsabilidad |
| --- | --- |
| Frontend | experiencia, formularios y estados |
| Backend | validación, reglas, totales y transacciones |
| Datos | relaciones, restricciones, índices y decimales |

## Invariantes

- El servidor calcula importes confiables.
- Venta y fiado nunca dejan stock negativo.
- Compra, venta y abono son operaciones atómicas.
- Un fiado no crea ingreso hasta recibir un abono.

Relacionada con [[01 Fundamentos/Modelo de Datos]] y [[05 Operacion/Seguridad]].
