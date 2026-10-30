---
tipo: modulo
modulo: M04
estado: estable
tags: [punto-barrio, modulo/ventas]
cssclasses: [module-sales]
---

# M04 Ventas

> [!sales] Propósito
> Registrar una venta, generar comprobante y actualizar inventario y caja de forma atómica.

## Contrato

`GET/POST /api/sales` · `GET /api/sales/:id`

## Invariante

Crear venta, ítems, descuento de stock e ingreso de caja ocurre en una transacción.

Ver [[02 Modulos/04 Ventas/Flujos y Evidencia]].
