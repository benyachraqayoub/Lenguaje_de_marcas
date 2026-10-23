# CUESTIONARIO · JSON

Cuestionario sobre qué es JSON, sus usos, sintaxis, tipos de datos, objetos anidados y errores habituales.

### 1. ¿Qué significan las siglas JSON?
- [ ] Java Standard Object Network
- [ ] Java Syntax Online Notation
- [x] **JavaScript Object Notation** (Correcta)

### 2. ¿Qué es JSON?
- [x] **Un formato de texto para representar e intercambiar datos** (Correcta)
- [ ] Una base de datos relacional
- [ ] Un lenguaje de programación

### 3. ¿Qué extensión tiene habitualmente un archivo JSON?
- [x] **`.json`** (Correcta)
- [ ] `.js`
- [ ] `.jsn`

### 4. ¿Cuál es el uso principal de JSON?
- [x] **Intercambiar datos entre aplicaciones, por ejemplo entre cliente y servidor** (Correcta)
- [ ] Ejecutar lógica y cálculos
- [ ] Dar estilos a una página web

### 5. ¿Cuál de estos es un uso habitual de JSON?
- [x] **Guardar datos de una tienda online, como productos, clientes y pedidos** (Correcta)
- [ ] Compilar programas
- [ ] Dibujar gráficos en 3D

### 6. ¿Qué símbolos delimitan un array en JSON?
- [ ] `{ }`
- [ ] `( )`
- [x] **`[ ]`** (Correcta)

### 7. ¿Cuál de estos ejemplos es un array válido en JSON?
- [ ] `("P001", "P002", "P003")`
- [x] **`["P001", "P002", "P003"]`** (Correcta)
- [ ] `{"P001", "P002", "P003"}`

### 8. ¿Qué símbolos delimitan un objeto en JSON?
- [ ] `( )`
- [ ] `[ ]`
- [x] **`{ }`** (Correcta)

### 9. ¿De qué está formado un objeto JSON?
- [ ] Solo de números
- [x] **De pares clave:valor** (Correcta)
- [ ] De valores sueltos separados por comas

### 10. ¿Cuál es la diferencia principal entre un array y un objeto JSON?
- [x] **El array es una lista ordenada de valores a la que se accede por posición; el objeto agrupa propiedades con nombre en pares clave:valor** (Correcta)
- [ ] El array usa claves y el objeto usa posiciones
- [ ] No hay ninguna diferencia: son intercambiables

### 11. ¿Qué estructura JSON usarías para representar una lista de tres clientes de una tienda?
- [ ] Un objeto con tres propiedades
- [x] **Un array de objetos** (Correcta)
- [ ] Un string

### 12. ¿Qué tipos de datos admite JSON?
- [ ] `string`, `number`, `boolean`, `undefined` y `date`
- [x] **`string`, `number`, `boolean`, `null`, `object` y `array`** (Correcta)
- [ ] `string`, `int`, `float`, `date` y `function`

### 13. ¿Cuál de estos es un valor booleano válido en JSON?
- [ ] `True`
- [ ] `"true"`
- [x] **`true`** (Correcta)

### 14. ¿Qué tipo de dato tiene el valor de la propiedad `"precio"` en `{"precio": "19.99"}`?
- [ ] Boolean
- [x] **String** (Correcta)
- [ ] Number

### 15. ¿Es válido el JSON `{nombre: "Ana"}`?
- [ ] Sí, es válido
- [ ] Sí, pero solo si el valor es un string
- [x] **No, las claves deben ir entre comillas dobles** (Correcta)

### 16. ¿Es válido el JSON `{'nombre': 'Ana'}`?
- [x] **No, JSON exige comillas dobles, no simples** (Correcta)
- [ ] Sí, pero solo en los valores
- [ ] Sí, las comillas simples y dobles son equivalentes

### 17. ¿Es válido el array `["a", "b", "c",]`?
- [x] **No, la coma final después del último elemento es un error** (Correcta)
- [ ] Sí, es válido
- [ ] Sí, pero solo dentro de un objeto

### 18. ¿Se pueden escribir comentarios como `// comentario` en un archivo JSON?
- [ ] Sí, con `//`
- [x] **No, JSON no admite comentarios** (Correcta)
- [ ] Solo con `/* */`

### 19. ¿Qué error tiene el JSON `{"nombre": "Ana" "edad": 30}`?
- [ ] Ninguno, es correcto
- [ ] Falta una llave de cierre
- [x] **Falta una coma entre las dos propiedades** (Correcta)

### 20. ¿Qué es un objeto anidado?
- [ ] Un objeto repetido dos veces
- [x] **Un objeto que está dentro de otro objeto como valor de una propiedad** (Correcta)
- [ ] Un objeto guardado en otro archivo

### 21. ¿Qué propiedad del objeto anidado contiene el valor `"Valencia"`?

```json
{"nombre": "Ana", "direccion": {"ciudad": "Valencia"}}
```

- [ ] `nombre`
- [x] **`ciudad`** (Correcta)
- [ ] `direccion`

### 22. ¿Cuál de estos ejemplos es un array de objetos?
- [ ] `["P001", "P002"]`
- [x] **`[{"id": "P001"}, {"id": "P002"}]`** (Correcta)
- [ ] `{"id": ["P001", "P002"]}`

### 23. ¿Cuál de estos ejemplos es JSON válido?
- [ ] `{"id": "P001", "precio": 19.99, "disponible": true,}`
- [ ] `{"id": "P001", "precio": 19.99, "disponible": True}`
- [x] **`{"id": "P001", "precio": 19.99, "disponible": true}`** (Correcta)

### 24. En un pedido, ¿cómo se relaciona correctamente el pedido con un cliente?
- [ ] Copiando todos los datos del cliente dentro del pedido
- [x] **Usando un `clienteId` cuyo valor coincide con el `id` del cliente, por ejemplo `"C001"`** (Correcta)
- [ ] Escribiendo solo el nombre del cliente en un comentario

### 25. ¿Cuál de estos ejemplos con objetos anidados es JSON válido?
- [ ] `{"cliente": {"id": "C001", "direccion": {"ciudad": "Valencia"}}`
- [x] **`{"cliente": {"id": "C001", "direccion": {"ciudad": "Valencia"}}}`** (Correcta)
- [ ] `{"cliente": {"id": "C001", "direccion": {"ciudad": Valencia}}}`
