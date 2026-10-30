---
tipo: operacion
estado: activo
tags: [punto-barrio, seguridad]
---

# Seguridad

- `.env` y secretos no se versionan.
- Helmet y CORS protegen la API.
- Zod valida todas las escrituras.
- Hooks bloquean archivos sensibles, comandos destructivos y commits inválidos.
- Errores 500 no exponen trazas ni credenciales.
- Operaciones monetarias críticas usan transacciones.

Ver [[01 Fundamentos/Arquitectura]] y [[06 Evidencias/Checklist de Entrega]].
