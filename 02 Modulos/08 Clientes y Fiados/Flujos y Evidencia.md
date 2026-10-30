---
tipo: evidencia-modulo
modulo: M08
tags: [punto-barrio, modulo/fiados, evidencia]
cssclasses: [module-credits]
---

# Clientes y fiados flujos y evidencia

## Fiado

Cliente activo → validar límite y stock → crear deuda e ítems → disminuir stock → no mover caja.

## Abono

Validar monto ≤ saldo → crear pago → reducir deuda del crédito y cliente → estado `PARTIAL` o `PAID` → ingreso en caja.

## Trazabilidad

HU-09 y HU-10 → RF-11 → rutas `customers.ts` y `credits.ts` → UI → pruebas de límite y abono.
