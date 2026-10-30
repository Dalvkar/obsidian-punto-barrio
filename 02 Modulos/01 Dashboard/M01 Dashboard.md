---
tipo: modulo
modulo: M01
estado: estable
tags: [punto-barrio, modulo/dashboard]
cssclasses: [module-dashboard]
---

# M01 Dashboard

> [!dashboard] Propósito
> Resumir ingresos, ventas, productos, inventario, stock bajo y actividad reciente.

## Entradas y salidas

- Lee `Product`, `Sale` y `CashMovement`.
- Presenta métricas diarias y serie de siete días.
- Dirige a ventas e inventario.

## Contrato

`GET /api/dashboard`

Ver [[02 Modulos/01 Dashboard/Flujos y Evidencia]] y [[03 SDD/Matriz de Trazabilidad]].
