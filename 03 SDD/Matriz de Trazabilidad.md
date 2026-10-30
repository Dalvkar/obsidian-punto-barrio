---
tipo: trazabilidad
estado: activo
tags: [punto-barrio, sdd/trazabilidad]
---

# Matriz de trazabilidad

| Historia | RF | Módulo | Datos | API | Evidencia |
| --- | --- | --- | --- | --- | --- |
| HU-01 | RF-01 | M01 | Product, Sale, CashMovement | `/dashboard` | métricas |
| HU-02 | RF-02 | M02 | Product | `/products` | validación/SKU |
| HU-03 | RF-03 | M03 | Product | `/products/:id/stock` | stock negativo |
| HU-04 | RF-04/05 | M04 | Sale, SaleItem | `/sales` | build/transacción |
| HU-05 | RF-06 | M05 | CashMovement, CashClosing | `/cash` | caja y abono |
| HU-06 | RF-07 | M06 | Sale, SaleItem | `/reports` | build/agregación |
| HU-07/08 | RF-10 | M07 | Supplier, Purchase | `/suppliers`, `/purchases` | compra transaccional |
| HU-09/10 | RF-11 | M08 | Customer, Credit | `/customers`, `/credits` | límite y abono |
