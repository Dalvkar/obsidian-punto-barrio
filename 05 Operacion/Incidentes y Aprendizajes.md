---
tipo: incidente
estado: resuelto
tags: [punto-barrio, render, prisma]
---

# Incidentes y aprendizajes

## INC-001 P3005 en Render

**Síntoma:** el commit compilaba y CI pasaba, pero Render conservaba la versión anterior.

**Causa:** la base fue creada con `prisma db push` y no tenía baseline; `prisma migrate deploy` rechazó el esquema no vacío.

**Recuperación:** restaurar `db push`, desplegar y verificar endpoints.

**Prevención:** crear baseline antes de adoptar Prisma Migrate en producción.
