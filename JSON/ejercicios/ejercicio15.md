# Ejercicio 15 — Registro de pedidos avanzado

## Solución

```json
{
  "pedidos": [
    {
      "numero": 1001,
      "cliente": {
        "nombre": "Ana López",
        "email": "ana.lopez@example.com",
        "direccion": {
          "calle": "Calle Mayor, 12",
          "ciudad": "Valencia",
          "codigoPostal": "46001"
        }
      },
      "producto": "Teclado",
      "cantidad": 1,
      "entregado": true
    },
    {
      "numero": 1002,
      "cliente": {
        "nombre": "Marcos Ruiz",
        "email": "marcos.ruiz@example.com",
        "direccion": {
          "calle": "Avenida del Puerto, 25",
          "ciudad": "Valencia",
          "codigoPostal": "46021"
        }
      },
      "producto": "Auriculares",
      "cantidad": 2,
      "entregado": false
    },
    {
      "numero": 1003,
      "cliente": {
        "nombre": "Nuria García",
        "email": "nuria.garcia@example.com",
        "direccion": {
          "calle": "Calle de Alcalá, 50",
          "ciudad": "Madrid",
          "codigoPostal": "28014"
        }
      },
      "producto": "Ratón",
      "cantidad": 1,
      "entregado": false
    }
  ]
}
```

## Tipos de Datos Utilizados
* **pedidos:** Array con tres objetos, uno por pedido.
* **numero** y **cantidad:** Number.
* **cliente:** Object con el nombre, el email y la dirección del cliente.
* **direccion:** Object anidado con **calle**, **ciudad** y **codigoPostal**, todos de tipo String.
* **producto**, **nombre**, **email**, **calle**, **ciudad** y **codigoPostal:** String.
* **entregado:** Boolean.

**Objetivo:** Practicar estructuras JSON con varios niveles de objetos anidados.
