# Respuestas prácticas

## Tarea 1 — Errores del fragmento

1. A `nombre` le faltan las comillas dobles.
2. El nombre del hotel debe ir entre comillas dobles, no simples.
3. `estrellas` debe ser un número: `4`, no el texto `"4"`.
4. En JSON se escribe `true` en minúsculas, no `True`.
5. Sobra la coma después de `"parking"`.
6. `null` se escribe sin comillas. Con comillas, sería texto.

## Tarea 2 — Tipos de datos

- `estrellas` es `4`, un número.
- `codigoPostal` es texto (`"46023"`) porque es un código y así se preservan los ceros iniciales.
- `web` es `null` porque el hotel no tiene página web.

La estructura de esta tarea, las habitaciones de la tarea 3 y los clientes y reservas de la tarea 4 están en [hotel.json](./hotel.json).

## Tarea 5 — Rutas y búsquedas

### a. Acceso a los datos

Precio de los extras de la primera reserva:

```text
hotel.reservas[0].pago.desglose.extras
```

Cantidad del segundo extra:

```text
hotel.reservas[0].extras[1].cantidad
```

### b. Reservas de la habitación H101

Busco las reservas cuyo `habitacionId` sea `"H101"`. Son `R001` y `R003`.

### c. Clientes sin fidelidad asignada

Busco los clientes cuyo `fidelidad` sea `null`. Es `C002`, Marc Soler.
