---
tipo: modulo
modulo: M03
estado: estable
tags: [punto-barrio, modulo/inventario]
cssclasses: [module-inventory]
---

# M03 Inventario

> [!inventory] Propósito
> Controlar existencias y anticipar reposiciones sin permitir stock negativo.

## Capacidades

- Ajustes positivos y negativos con motivo.
- Alertas por nivel mínimo.
- Reposición automática desde M07.
- Descuento automático desde M04 y M08.

## Contrato

`PATCH /api/products/:id/stock`

Ver [[02 Modulos/03 Inventario/Flujos y Evidencia]].
