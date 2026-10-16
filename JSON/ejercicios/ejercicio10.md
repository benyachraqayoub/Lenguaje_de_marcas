# Ejercicio 10 — Combinar arrays y objetos anidados

## Solución

```json
{
  "nombre": "Tienda Mundo Tech",
  "direccion": {
    "calle": "Avenida del Puerto, 25",
    "ciudad": "Valencia"
  },
  "productos": [
    {
      "nombre": "Teclado",
      "precio": 49.99,
      "disponible": true
    },
    {
      "nombre": "Ratón",
      "precio": 24.5,
      "disponible": true
    },
    {
      "nombre": "Monitor",
      "precio": 189.99,
      "disponible": false
    }
  ]
}
```

## Tipos de Datos Utilizados
* **nombre**, **calle**, **ciudad** y el nombre de cada producto: String.
* **direccion:** Object (Contiene la calle y la ciudad).
* **productos:** Array con tres objetos, uno por producto.
* **precio:** Number.
* **disponible:** Boolean.

**Objetivo:** Combinar objetos anidados, arrays y arrays de objetos en una estructura JSON.
