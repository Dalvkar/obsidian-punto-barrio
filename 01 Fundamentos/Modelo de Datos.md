---
tipo: arquitectura
estado: estable
tags: [punto-barrio, base-datos]
---

# Modelo de datos

| Agregado | Entidades | Regla principal |
| --- | --- | --- |
| Catálogo | Product | SKU único, stock no negativo |
| Ventas | Sale, SaleItem | precios históricos y descuento de stock |
| Caja | CashMovement, CashClosing | ingreso, egreso y diferencia |
| Compras | Supplier, Purchase, PurchaseItem | reposición y costo |
| Crédito | Customer, Credit, CreditItem, CreditPayment | límite, deuda y abonos |

Los importes usan `Decimal(10,2)` y los ítems preservan el valor del momento de la operación.
