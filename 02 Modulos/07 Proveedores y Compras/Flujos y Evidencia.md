---
tipo: evidencia-modulo
modulo: M07
tags: [punto-barrio, modulo/compras, evidencia]
cssclasses: [module-purchases]
---

# Proveedores y compras flujos y evidencia

Proveedor activo → productos/cantidades/costos → cálculo del servidor → compra e ítems → stock/costo → egreso.

## Invariante transaccional

Si proveedor o producto no existe, ninguna parte queda guardada.

## Trazabilidad

HU-07 y HU-08 → RF-10 → rutas `suppliers.ts` y `purchases.ts` → UI → prueba de compra transaccional.
