# Ejercicio 16 — Catálogo de tienda online

## Solución

```json
{
  "tienda": {
    "nombre": "Mundo Tech",
    "abierta": true,
    "contacto": {
      "telefono": "+34 960 123 456",
      "email": "contacto@mundotech.example"
    },
    "categorias": [
      {
        "id": "cat-001",
        "nombre": "Informática",
        "productos": [
          {
            "sku": "INF-001",
            "nombre": "Teclado mecánico",
            "precio": 79.99,
            "stock": 12,
            "etiquetas": ["periférico", "mecánico"],
            "dimensiones": {
              "alto": 4,
              "ancho": 44,
              "fondo": 14
            },
            "disponible": true
          },
          {
            "sku": "INF-002",
            "nombre": "Ratón inalámbrico",
            "precio": 34.5,
            "stock": 0,
            "etiquetas": ["periférico", "inalámbrico"],
            "dimensiones": {
              "alto": 4,
              "ancho": 7,
              "fondo": 12
            },
            "disponible": false
          }
        ]
      },
      {
        "id": "cat-002",
        "nombre": "Audio",
        "productos": [
          {
            "sku": "AUD-001",
            "nombre": "Auriculares Bluetooth",
            "precio": 59.99,
            "stock": 8,
            "etiquetas": ["audio", "bluetooth"],
            "dimensiones": {
              "alto": 19,
              "ancho": 17,
              "fondo": 8
            },
            "disponible": true
          },
          {
            "sku": "AUD-002",
            "nombre": "Altavoz portátil",
            "precio": 42,
            "stock": 5,
            "etiquetas": ["audio", "portátil"],
            "dimensiones": {
              "alto": 10,
              "ancho": 8,
              "fondo": 8
            },
            "disponible": true
          }
        ]
      },
      {
        "id": "cat-003",
        "nombre": "Accesorios",
        "productos": [
          {
            "sku": "ACC-001",
            "nombre": "Funda para portátil",
            "precio": 24.9,
            "stock": 15,
            "etiquetas": ["protección", "portátil"],
            "dimensiones": {
              "alto": 3,
              "ancho": 36,
              "fondo": 26
            },
            "disponible": true
          },
          {
            "sku": "ACC-002",
            "nombre": "Cable USB-C",
            "precio": 9.99,
            "stock": 30,
            "etiquetas": ["cable", "usb-c"],
            "dimensiones": {
              "alto": 2,
              "ancho": 10,
              "fondo": 10
            },
            "disponible": true
          }
        ]
      }
    ]
  }
}
```

## Tipos de Datos Utilizados
* **tienda**, **contacto**, **categorias**, **productos** y **dimensiones:** Object o Array, según corresponda.
* **nombre**, **telefono**, **email**, **id**, **sku** y **etiquetas:** String.
* **abierta** y **disponible:** Boolean.
* **precio**, **stock** y las medidas **alto**, **ancho** y **fondo:** Number.
* Cada categoría contiene al menos dos productos.

**Objetivo:** Practicar arrays anidados y combinar objetos y arrays en distintos niveles.
