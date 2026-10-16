# Ejercicio final — Proyecto: tienda online

## Solución

La tienda online completa está en [tienda_online.json](./tienda_online.json). Contiene la información de contacto y dirección de la tienda, cuatro productos, tres clientes y cuatro pedidos. Los pedidos relacionan clientes y productos mediante sus identificadores, sin duplicar sus datos.

## Reto extra

1. Nombre del cliente **C002**: `tienda.clientes[1].nombre` → **Bruno García**.
2. Productos del pedido **PED003**: `tienda.pedidos[2].productos` → **P003** (Monitor) y **P001** (Portátil).
3. Cantidad del producto **P001** en **PED001**: `tienda.pedidos[0].productos[0].cantidad` → **1**.
4. Cliente del pedido **PED004**: `tienda.pedidos[3].clienteId` → **C002**, Bruno García.
5. Precio del producto **P003**: `tienda.productos[2].precio` → **199.99**.
6. Productos en la tienda: `tienda.productos.length` → **4**.
7. Clientes registrados: `tienda.clientes.length` → **3**.
8. Pedidos registrados: `tienda.pedidos.length` → **4**.
9. Pedidos con estado **"pendiente"**: **PED002** y **PED003**.
10. Clientes de cada pedido:
    * **PED001** → **C001**, Ana López.
    * **PED002** → **C002**, Bruno García.
    * **PED003** → **C003**, Carla Ruiz.
    * **PED004** → **C002**, Bruno García.

**Objetivo:** Integrar objetos, arrays, tipos de datos y relaciones entre elementos mediante identificadores en un JSON válido.
