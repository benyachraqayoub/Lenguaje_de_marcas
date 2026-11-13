# EXAMEN OFICIAL - 1a EVALUACION (MODELO C)

| CAMPO | DETALLE |
| :--- | :--- |
| **PROGRAMA** | Desarrollo de Aplicaciones Web (DAW) |
| **MODULO** | Lenguajes de marcas |
| **CURSO Y GRUPO** | 1o DAW, GRUPO A |
| **MODELO** | C |

---

## CRONOGRAMA Y RUBRICA DE EVALUACION DEL EXAMEN

| PARTE / BLOQUE | DURACION | PESO |
| :--- | :--- | :--- |
| **PARTE 1:** evaluacion teorica | 30 min | $30\%$ |
| **PARTE 2:** evaluacion practica | 1 hora y media (90 min) | $50\%$ |
| **PARTE 3:** defensa individual | 3-5 min | $20\%$ |

### INSTRUCCIONES DEL EXAMEN

1. **PARTE 1: evaluacion teorica**
   - Sin apuntes ni dispositivos.
   - Test de 27 preguntas con una unica respuesta correcta y 3 preguntas abiertas.
   - Por cada tres respuestas erroneas se descontara una respuesta correcta.
2. **PARTE 2: evaluacion practica**
   - Se permite el uso de IA como herramienta de apoyo para consultar sintaxis, resolver un bloqueo/error puntual o consultar documentacion.
   - No se permite el uso de IA para copiar el enunciado entero y que la IA resuelva el examen por ti.
3. **PARTE 3: defensa individual**
   - Tendras que explicar y justificar lo que has hecho sin ayuda de pantallas ni IA.
   - **Aviso importante:** si en la defensa se comprueba que no entiendes lo aplicado (y hay indicios de uso abusivo de IA para resolver la practica), el examen completo queda automaticamente suspendido.

---

## PARTE 1: Evaluacion teorica de conocimientos (30 min)

### Preguntas tipo test

**1. En una web de recetas, el titulo principal es `<h1>` «Cocina Mediterranea», el bloque de entrantes es `<h2>` «Ensaladas» y cada receta dentro de «Ensaladas» se marca con `<h5>` «Ensalada Cesar» para que la letra salga pequena. ¿Que problema presenta?**
- A) Ninguno, porque `<h5>` esta dentro del rango permitido de `<h1>` a `<h6>`.
- B) Se saltan los niveles `<h3>` y `<h4>`, deteriorando la estructura semantica del documento para tecnologias de asistencia y motores de busqueda.
- C) Las etiquetas `<h5>` solo pueden utilizarse en el `<footer>`.
- D) HTML5 no permite usar mas de dos niveles de encabezado en la misma pagina.

**2. ¿Por que se recomienda anadir `rel="noopener noreferrer"` cuando un enlace lleva `target="_blank"`?**
- A) Para que la pagina externa cargue sin imagenes y consuma menos datos.
- B) Por seguridad y privacidad: evita que la pagina abierta pueda acceder al objeto `window.opener` de la pestana original.
- C) Para obligar al navegador a abrir el enlace en la misma pestana.
- D) Para que los buscadores pongan el texto del enlace en negrita.

**3. ¿Cual de los siguientes enlaces sigue las recomendaciones de accesibilidad para lectores de pantalla?**
- A) `<a href="bases-concurso.html">Consultar las bases legales del concurso</a>`
- B) `<a href="bases-concurso.html">Aqui</a>`
- C) `<a href="bases-concurso.html">Link</a>`
- D) `<a href="bases-concurso.html">Ver</a>`

**4. Quieres marcar en un aviso de seguridad la palabra «Peligro» como de maxima importancia semantica y dar enfasis de lectura a la palabra «inmediatamente». ¿Que opcion es la adecuada?**
- A) `<i>Peligro</i>` y `<b>inmediatamente</b>`
- B) `<strong>Peligro</strong>` y `<em>inmediatamente</em>`
- C) `<b>Peligro</b>` y `<em>inmediatamente</em>`
- D) `<mark>Peligro</mark>` y `<small>inmediatamente</small>`

**5. ¿Para que sirve incluir `<meta charset="UTF-8">` dentro de la seccion `<head>` de un documento HTML?**
- A) Para que la pagina se adapte automaticamente al ancho de las pantallas moviles.
- B) Para definir el idioma espanol como idioma de traduccion automatica.
- C) Para indicar la codificacion de caracteres y que simbolos como `ñ`, tildes o `€` se muestren correctamente.
- D) Para enlazar el archivo con un esquema de validacion XML.

**6. Analiza el siguiente codigo HTML. ¿Por que es estructuralmente incorrecto?**
```html
<ul>
  <li>Perifericos</li>
  <li>Componentes</li>
  <ol>
    <li>Procesadores</li>
    <li>Tarjetas graficas</li>
  </ol>
</ul>
```
- A) Porque no se puede combinar nunca una lista `<ol>` con una `<ul>` en el mismo documento.
- B) Porque la sublista `<ol>` esta colocada como hija directa de `<ul>`, cuando deberia estar anidada dentro del `<li>` correspondiente («Componentes»).
- C) Porque `<ol>` solo acepta dos elementos como maximo.
- D) Porque falta la etiqueta `<list>` envolviendo todo el bloque.

**7. En un periodico digital quieres etiquetar una noticia independiente (con su titular, texto y autor) que podria redistribuirse por si sola en un lector de noticias, situada dentro de la zona principal de la pagina. ¿Que combinacion semantica encaja mejor?**
- A) Un `<article>` situado dentro de `<main>`.
- B) Un `<nav>` situado dentro de `<footer>`.
- C) Un `<aside>` que contenga tres etiquetas `<header>`.
- D) Un `<p>` que envuelva a toda la pagina web.

**8. ¿Cual de estos fragmentos de codigo HTML es valido y respeta el anidamiento correcto?**
- A) `<p>Curso de <strong>Desarrollo <em>Web</strong></em></p>`
- B) `<a href="index.html"><p>Volver al inicio</a></p>`
- C) `<p>Curso de <strong>Desarrollo</strong> <em>Web</em>.</p>`
- D) `<ul><p>Elemento de lista</p></ul>`

**9. En un formulario de contacto hay tres casillas `<input type="radio">` para elegir la franja horaria de llamada («Manana», «Mediodia», «Tarde»), cada una con `name="franja1"`, `name="franja2"` y `name="franja3"`. ¿Que ocurrira al usarlo?**
- A) El navegador mostrara un error y no dejara enviar el formulario.
- B) Solo se podra elegir «Manana» por ser la primera.
- C) Funcionara correctamente como seleccion unica porque los `name` son diferentes.
- D) El usuario podra marcar las tres opciones a la vez y no podra desmarcarlas porque tienen distinto atributo `name`.

**10. ¿Cual de estos fragmentos XML esta bien formado?**
- A) `<?xml version="1.0"?><vehiculo><marca>Seat</marca><modelo>Ibiza</modelo>`
- B) `<?xml version="1.0"?><vehiculo matricula="1234BCD"><marca>Seat</marca><modelo>Ibiza</modelo></vehiculo>`
- C) `<?xml version="1.0"?><vehiculo><marca>Seat</marca></vehiculo><vehiculo><marca>Ford</marca></vehiculo>`
- D) `<?xml version="1.0"?><vehiculo><marca>Seat<modelo>Ibiza</marca></modelo></vehiculo>`

**11. Un archivo `facturas.xml` cierra todas sus etiquetas correctamente y tiene una unica raiz, pero incluye el elemento `<descuento>10</descuento>`, que no ha sido declarado en su archivo `facturas.xsd`. ¿Cual es su estado?**
- A) Esta mal formado y es invalido.
- B) Es valido, pero esta mal formado.
- C) Esta bien formado, pero es invalido respecto al XSD.
- D) Es tanto bien formado como valido, porque XML permite anadir etiquetas libres.

**12. En `concesionario.xml` se registran los `vehiculos` y las `revisiones` de taller. Un vehiculo pasa muchas revisiones a lo largo de los anos. ¿Como se disena correctamente la relacion?**
- A) Duplicando todos los datos tecnicos del vehiculo (marca, modelo, bastidor, cilindrada, color) dentro de cada revision.
- B) Almacenando los datos del vehiculo una sola vez en `vehiculos` con un `id`, e incluyendo solo la referencia `vehiculoId` en cada revision.
- C) Poniendo solo el color del coche en la revision para identificarlo.
- D) Creando una etiqueta distinta por cada matricula (`<coche1234>`, `<coche5678>`).

**13. ¿Cual es la diferencia fundamental de proposito entre HTML y XML?**
- A) HTML esta disenado para almacenar y transportar datos estructurados; XML sirve para maquetar paginas web.
- B) XML es la version moderna que ha sustituido por completo a HTML en los navegadores.
- C) HTML distingue entre mayusculas y minusculas en las etiquetas y XML no.
- D) HTML se centra en presentar y estructurar contenido en la web con etiquetas predefinidas, mientras que XML permite definir etiquetas propias para estructurar y transportar datos segun su significado.

**14. Si un esquema XSD define un elemento complejo mediante `<xs:sequence>` con los hijos `calle`, `numero` y `ciudad` (en ese orden), ¿que ocurre si un XML pone primero `ciudad` y luego `calle` y `numero`?**
- A) El documento XML es invalido porque `<xs:sequence>` exige respetar estrictamente el orden declarado.
- B) El documento XML pasa a estar mal formado.
- C) El documento XML es valido porque estan presentes los tres elementos obligatorios.
- D) El validador reordena automaticamente las etiquetas del XML.

**15. En un XSD aparece `<xs:element name="extra" type="xs:string" minOccurs="0" maxOccurs="3"/>`. ¿Que significa para el XML?**
- A) Que el elemento `<extra>` debe aparecer obligatoriamente 3 veces.
- B) Que el elemento `<extra>` es opcional (puede no aparecer) y como maximo puede repetirse 3 veces seguidas.
- C) Que el texto dentro de `<extra>` debe tener entre 0 y 3 letras.
- D) Que el elemento `<extra>` puede repetirse un numero ilimitado de veces.

**16. En el XSD de un catalogo se define `<xs:attribute name="codigo" type="xs:string" use="required"/>` para el elemento `<producto>`. Si un `<producto>` en el XML no lleva el atributo `codigo`, ¿que ocurre?**
- A) El XML deja de estar bien formado porque falta un atributo.
- B) Es valido si el producto tiene un elemento hijo `<nombre>`.
- C) El XML sigue estando bien formado, pero resulta invalido al validar contra el XSD.
- D) El navegador no puede abrir el archivo como texto.

**17. En `empresa.xml` hay 4 elementos `<departamento>` (cada uno con un hijo `<responsable>`) y 10 elementos `<proyecto>` repartidos dentro de los departamentos (cada proyecto tambien tiene un hijo `<responsable>`). ¿Cuantos nodos devuelve la consulta XPath `/empresa/departamento/responsable`?**
- A) 14 nodos (todos los responsables del documento).
- B) 4 nodos (unicamente los hijos directos `responsable` de cada `departamento`).
- C) 10 nodos (solo los responsables de los proyectos).
- D) 0 nodos, porque falta poner `//` al principio.

**18. Dada la estructura XML `/concesionario/vehiculo[@id='V01']/equipamiento/item[categoria='Seguridad']/nombre`, ¿que devuelve esta ruta XPath?**
- A) El nombre de los items de equipamiento cuya categoria (elemento hijo) es `'Seguridad'`, pertenecientes al vehiculo con atributo `id='V01'`.
- B) Todos los vehiculos que tienen el atributo `categoria='Seguridad'`.
- C) El atributo `nombre` del vehiculo `'V01'`.
- D) Los items de equipamiento cuyo atributo `@categoria` es `'Seguridad'`.

**19. En un archivo XSD necesitas que `<unidades>` solo admita numeros enteros sin decimales y `<importeTotal>` admita numeros con decimales. ¿Que tipos de datos XSD debes asignar?**
- A) `xs:number` para ambos.
- B) `xs:string` para `unidades` y `xs:floatString` para `importeTotal`.
- C) `xs:boolean` para `unidades` y `xs:decimal` para `importeTotal`.
- D) `xs:integer` para `unidades` y `xs:decimal` para `importeTotal`.

**20. ¿Cual de los siguientes fragmentos cumple estrictamente la sintaxis de JSON?**
- A) `{ "modelo": "Corsa", "electrico": true, "revisiones": [2024, 2025], "incidencias": null }`
- B) `{ "modelo": "Corsa", "electrico": TRUE, "revisiones": [2024, 2025], "incidencias": null }`
- C) `{ "modelo": 'Corsa', "electrico": true, "revisiones": (2024, 2025) }`
- D) `{ modelo: "Corsa", electrico: true, incidencias: NULL }`

**21. En un JSON de inventario se escribe `"precio": "45.90"` en lugar de `"precio": 45.90`. ¿Que implicacion tiene?**
- A) Ninguna, en JSON los numeros con decimales deben ir siempre entre comillas dobles.
- B) El JSON es invalido porque el punto decimal no esta permitido dentro de comillas.
- C) El JSON es valido, pero `"45.90"` se trata como texto (`string`), por lo que una aplicacion tendria que convertirlo a numero antes de sumarlo o multiplicarlo.
- D) VS Code lo borrara automaticamente al guardar el archivo.

**22. Un vehiculo de alquiler puede tener varias incidencias registradas, y de cada una queremos almacenar `fecha`, `descripcion` y `costeReparacion`. ¿Como debe modelarse la propiedad `"incidencias"` en JSON?**
- A) Como un booleano `"incidencias": true`.
- B) Como un unico objeto repitiendo tres veces las mismas claves `fecha`, `descripcion` y `costeReparacion`.
- C) Como tres propiedades sueltas: `"incidencia1"`, `"incidencia2"` e `"incidencia3"`.
- D) Como un array de objetos, donde cada objeto contiene `fecha`, `descripcion` y `costeReparacion`.

**23. Dado el siguiente JSON, ¿que expresion accede a `"Automático"`?**
```json
{
  "flota": {
    "coches": [
      { "matricula": "1111AAA", "extras": ["GPS", "Techo solar"] },
      { "matricula": "2222BBB", "extras": ["Sensores", "Automático", "Asientos calefactables"] }
    ]
  }
}
```
- A) `flota.coches[2].extras[2]`
- B) `flota.coches[1].extras[1]`
- C) `flota.coches[1].extras[2]`
- D) `flota.coches[0].extras[1]`

**24. Tienes un array JSON `alquileres`, donde cada objeto incluye `id`, `vehiculoId` y `clienteId`. ¿Como puedes saber cuantas veces se ha alquilado el vehiculo `"V02"`?**
- A) Mirando el elemento `alquileres[2]`.
- B) Recorriendo el array `alquileres` y seleccionando los objetos cuya propiedad `vehiculoId` sea `"V02"`.
- C) Buscando en `alquileres` el objeto cuyo `id` sea `"V02"`.
- D) No es posible saberlo si los datos del vehiculo no estan copiados dentro del alquiler.

**25. Segun el diseno de una API en JSON, la propiedad `descuento` de un cliente debe ser un objeto con `tipo` y `porcentaje`, o bien indicar ausencia de valor si no tiene descuento. ¿Como se escribe cuando no tiene descuento?**
- A) `"descuento": "ninguno"`
- B) `"descuento": []`
- C) `"descuento": null`
- D) `"descuento": false`

**26. Se desea convertir a JSON el elemento XML `<envio codigo="E99"><peso>4.5</peso><urgente>false</urgente></envio>` respetando los tipos de datos. ¿Que opcion es la mas adecuada?**
- A) `{ "codigo": "E99", "peso": 4.5, "urgente": false }`
- B) `{ "codigo": "E99", "peso": "4.5", "urgente": "false" }`
- C) `{ "envio": "E99 - 4.5 - false" }`
- D) `{ codigo: "E99", peso: 4,5, urgente: 0 }`

**27. ¿Que error sintactico impide que este JSON sea valido?**
```json
{
  "sucursales": [
    { "id": 1, "ciudad": "València" }
    { "id": 2, "ciudad": "Alicante" }
  ]
}
```
- A) El valor de `"id"` debe ir obligatoriamente entre comillas.
- B) No se pueden usar corchetes `[` `]` dentro de un objeto JSON.
- C) La palabra `"ciudad"` esta repetida en el segundo objeto.
- D) Falta la coma `,` que debe separar el primer objeto del segundo dentro del array `sucursales`.

---

### Preguntas de respuesta abierta

1. **Un desarrollador maqueta toda una pagina web utilizando exclusivamente etiquetas `<div>` (para la cabecera, el menu, las noticias y el pie de pagina) porque «en pantalla se ve exactamente igual».** Explica por que es una mala practica y que ventajas aporta usar etiquetas semanticas de HTML5.
2. **Define que significa que un documento XML este «bien formado» frente a que sea «valido».** Sobre un archivo `concesionario.xml`, inventa un cambio que lo deje *mal formado* y otro cambio que lo deje *bien formado pero invalido* segun su XSD.
3. **Escribe la representacion en XML y en JSON de un mismo vehiculo** (`id`: `"V10"`, `modelo`: `"Seat León"`, `potenciaCV`: `150`, `consumoMedio`: `5.4`, `hibrido`: `true`) e indica tres diferencias sintacticas o de tipos entre ambos formatos.

---

## PARTE 2: Evaluacion practica de conocimientos (90 min)

### Enunciado — Caso: Concesionario Albufera Motor (modelado de datos en JSON)

El concesionario y servicio de alquiler **Albufera Motor** va a implantar un nuevo sistema que intercambia datos en formato JSON. Debes elaborar el archivo `concesionario.json` con toda la informacion de las tablas adjuntas, organizando adecuadamente objetos, arrays, anidaciones y tipos de datos.

El archivo tendra un objeto raiz con una unica propiedad `concesionario` que englobara todo el contenido.

#### Informacion del concesionario

| Bloque | Datos |
| :--- | :--- |
| **Datos generales** | Nombre: Albufera Motor · Licencias de flota: 25 · Concesionario abierto: sí · Horario entrega: 08:30 · Horario devolución: 20:00 |
| **Direccion** | Pista de Silla km 5, Valencia, código postal 46470 · Coordenadas en el mapa: 39.4125 y -0.3841 |
| **Contacto** | Email: flota@albuferamotor.example · Teléfonos: 961223344 y 961223355 · Web: aún no tiene |
| **Servicios** | alquiler diario, renting, taller propio, asistencia en carretera |

#### Vehiculos

| ID | Num. plaza | Modelo | Precio dia | Plazas | Disponible | Ubicacion | Valoraciones | Equipamiento |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **V10** | 10 | Compacto "Eco" | 42,50 EUR | 5 | Sí | Nave 1 · Zona Norte | 4, 5, 4 | Climatizador, Bluetooth, Control de crucero |
| **V22** | 22 | SUV Familiar | 78,00 EUR | 7 | Sí | Nave 2 · Zona Sur | 5, 5 | Navegador GPS, Cámara 360, Techo panorámico, Bola remolque |
| **V35** | 35 | Furgoneta carga | 64,90 EUR | 2 | No | Nave 1 · Zona Exterior | *(ninguna)* | *(ninguno)* |

#### Clientes

| ID | Nombre | Fecha nacimiento | Documento | Club fidelidad | Preferencias |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **CL01** | Sofía Martí | 1990-07-18 | DNI 45678901L | Premium · 850 puntos | cambio automático, recogida rápida |
| **CL02** | David Orts | 1984-03-11 | Pasaporte ZP334455 | No pertenece al club | *(ninguna)* |
| **CL03** | Nadia Haddad | 1998-12-05 | NIE Y9876543W | Básico · 120 puntos | vehículo eléctrico o híbrido |

#### Alquileres

| ID | Cliente | Vehiculo | Fechas (Recogida / Devolucion) | Estado | Pagado | Extras contratados | Pago y notas |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **A001** | CL01 | V10 | 04/12/2026 al 07/12/2026 | Activo | Sí | Seguro todo riesgo 18,00 EUR x 3 · Silla infantil 8,50 EUR x 3 | Tarjeta · vehiculo 127,50 · extras 79,50 · impuestos 43,47 · total 250,47 · Nota: Entrega con depósito lleno |
| **A002** | CL02 | V22 | 18/12/2026 al 21/12/2026 | Pendiente | No | *(ninguno)* | Sin pago todavía · sin notas |
| **A003** | CL03 | V10 | 10/01/2027 al 12/01/2027 | Confirmado | Sí | Conductor adicional 15,00 EUR x 2 | Transferencia · vehiculo 85,00 · extras 30,00 · impuestos 24,15 · total 139,15 · Nota: Presenta carné internacional |
| **A004** | CL01 | V22 | 01/02/2027 al 03/02/2027 | Cancelado | No | *(ninguno)* | Sin pago · Nota: Cancelado con más de 48h de antelación |

---

### Tareas a realizar

- **Tarea 1. Detecta y corrige errores (10 min):** Corrige el siguiente fragmento en `fragmento_corregido.json` y detalla cada error en `respuestas.txt`:
```json
{
  nombre: 'Albufera Motor',
  "licenciasFlota": "25",
  "abierto": True,
  "servicios": ["alquiler diario", "renting",],
  "web": "null"
}
```
- **Tarea 2. Estructura base: objetos y tipos (20 min):** En `concesionario.json`, crea el objeto raiz `concesionario` con los datos generales, `direccion` y `contacto`. Justifica en `respuestas.txt` los tipos de dato para `licenciasFlota`, `codigoPostal` y `web`.
- **Tarea 3. Vehiculos: arrays de objetos y anidacion (20 min):** Anade el array `vehiculos`. Cada vehiculo tendra `id`, `numeroPlaza`, `modelo`, `precioDia`, `plazas`, `disponible`, el objeto `ubicacion` (`nave` y `zona`), el array `equipamiento` y el array `valoraciones`. Cuida el escape de comillas en `Compacto "Eco"`.
- **Tarea 4. Clientes y alquileres: relaciones y jerarquia profunda (30 min):** Anade los arrays `clientes` (con `documento` (`tipo` y `numero`), `fidelidad` (`nivel` y `puntos`, o `null`) y `preferencias`) y `alquileres` (con `clienteId`, `vehiculoId`, objeto `fechas` (`recogida` y `devolucion` en formato `AAAA-MM-DD`), `estado`, booleano `pagado`, array `extras` (`servicio`, `precioUnidad`, `cantidad`), objeto `pago` (`metodo`, `total` y `desglose` con `vehiculo`, `extras`, `impuestos`) o `null`, y `notas` como texto o `null`).
- **Tarea 5. Comprobacion y navegacion (10 min):** En `respuestas.txt`, responde:
  - **(a)** La ruta completa al importe de `vehiculo` dentro del desglose del pago del primer alquiler, y la ruta a la `cantidad` del segundo extra de ese mismo alquiler.
  - **(b)** Como averiguarias que alquileres corresponden al vehiculo `V10`.
  - **(c)** Como averiguarias que clientes no pertenecen al club de fidelidad.

---

## PARTE 3: Defensa individual / argumentacion (3-5 min)

Al finalizar las partes 1 y 2 del examen, realiza la entrega (`concesionario.json`, `fragmento_corregido.json`, `respuestas.txt` y `captura_json.png` comprimidos en `Apellido_Nombre_ModeloC.zip`) y espera a que el profesor te llame para responder a tres preguntas sobre la practica realizada.

---
---

# SOLUCIONARIO COMPLETO — MODELO C

## 1. Solucionario Parte 1: Tipo Test

| Pregunta | Respuesta | Pregunta | Respuesta | Pregunta | Respuesta |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **1** | **B** | **10** | **B** | **19** | **D** |
| **2** | **B** | **11** | **C** | **20** | **A** |
| **3** | **A** | **12** | **B** | **21** | **C** |
| **4** | **B** | **13** | **D** | **22** | **D** |
| **5** | **C** | **14** | **A** | **23** | **B** |
| **6** | **B** | **15** | **B** | **24** | **B** |
| **7** | **A** | **16** | **C** | **25** | **C** |
| **8** | **C** | **17** | **B** | **26** | **A** |
| **9** | **D** | **18** | **A** | **27** | **D** |

---

## 2. Solucionario Parte 1: Preguntas Abiertas

### Pregunta 1
- **Por que usar solo `<div>` es mala practica (`divitis`):** La etiqueta `<div>` es un contenedor generico sin ningun significado semantico. Si toda la web se construye con `<div>`, ni los motores de busqueda (SEO) ni los lectores de pantalla para personas con discapacidad visual pueden distinguir cual es el menu de navegacion, cual es el contenido principal o cual es el pie de pagina.
- **Ventajas del HTML5 semantico (`<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>`):** Mejora la accesibilidad (permite saltar directamente al contenido principal o al menu), mejora la indexacion en buscadores y hace que el codigo fuente sea mucho mas legible y mantenible para otros desarrolladores.

### Pregunta 2
- **Diferencia:** Un XML **bien formado** respeta las reglas sintacticas del estandar XML (etiquetas cerradas en orden, un unico nodo raiz, valores de atributos entrecomillados). Un XML **valido** es un documento bien formado que ademas respeta las restricciones estructurales y de tipos definidas en un esquema XSD o DTD.
- **Ejemplo mal formado en `concesionario.xml`:** Escribir un atributo sin comillas (`<vehiculo id=V10>`) o dejar una etiqueta `<modelo>` sin su cierre `</modelo>`.
- **Ejemplo bien formado pero invalido segun su XSD:** Eliminar el atributo obligatorio `id` de `<vehiculo>` cuando el XSD exige `<xs:attribute name="id" type="xs:string" use="required"/>`, o alterar el orden de los elementos hijos declarados en un `<xs:sequence>`.

### Pregunta 3
- **En XML:**
```xml
<vehiculo id="V10">
  <modelo>Seat León</modelo>
  <potenciaCV>150</potenciaCV>
  <consumoMedio>5.4</consumoMedio>
  <hibrido>true</hibrido>
</vehiculo>
```
- **En JSON:**
```json
{
  "id": "V10",
  "modelo": "Seat León",
  "potenciaCV": 150,
  "consumoMedio": 5.4,
  "hibrido": true
}
```
- **Tres diferencias:**
  1. En XML se utilizan etiquetas de apertura/cierre y atributos (`id="V10"`), mientras que en JSON todo son propiedades `"clave": valor`.
  2. JSON tipa directamente numeros enteros (`150`), decimales (`5.4`) y booleanos (`true`) sin comillas; en XML todo el contenido textual entre etiquetas es texto a menos que un XSD defina su tipo.
  3. JSON soporta arrays nativos con corchetes `[...]` para colecciones, mientras que XML requiere repetir etiquetas hermanas con el mismo nombre.

---

## 3. Solucionario Parte 2: Practica JSON

### Archivo 1: `fragmento_corregido.json` (Tarea 1)
```json
{
  "nombre": "Albufera Motor",
  "licenciasFlota": 25,
  "abierto": true,
  "servicios": ["alquiler diario", "renting"],
  "web": null
}
```

### Archivo 2: `respuestas.txt` (Tareas 1, 2 y 5)
```text
=== TAREA 1: ERRORES DETECTADOS ===
1. nombre: 'Albufera Motor' -> La propiedad "nombre" no está encerrada entre comillas dobles y el texto del valor utiliza comillas simples en lugar de comillas dobles.
2. "licenciasFlota": "25" -> Error de tipo de dato: la cantidad de licencias de flota es una magnitud numérica entera (25), no un texto ("25").
3. "abierto": True -> Error de sintaxis: el booleano debe escribirse íntegramente en minúsculas (true).
4. "servicios": ["alquiler diario", "renting",] -> Error de sintaxis: sobra la coma después del último elemento del array ("renting").
5. "web": "null" -> Error de tipo de dato: está escrito como cadena de texto ("null") en vez del literal nulo de JSON (null).

=== TAREA 2: JUSTIFICACION DE TIPOS ===
- licenciasFlota (number -> 25): Representa una cantidad contable de licencias con la que se puede operar matemáticamente.
- codigoPostal (string -> "46470"): Es un identificador postal de longitud fija con el que no se hacen cálculos aritméticos y que debe conservar posibles ceros iniciales.
- web (null -> null): Indica explícitamente que el concesionario carece actualmente de sitio web.

=== TAREA 5: COMPROBACION Y NAVEGACION ===
(a) Rutas de acceso:
- Importe de vehiculo del desglose del pago del primer alquiler:
  concesionario.alquileres[0].pago.desglose.vehiculo
- Cantidad del segundo extra de ese mismo alquiler:
  concesionario.alquileres[0].extras[1].cantidad

(b) Cómo averiguar qué alquileres corresponden al vehículo V10:
Recorriendo el array concesionario.alquileres y filtrando los objetos cuya propiedad vehiculoId sea igual a "V10".

(c) Cómo averiguar qué clientes no pertenecen al club de fidelidad:
Recorriendo el array concesionario.clientes y seleccionando aquellos cuya propiedad fidelidad tenga el valor null.
```

### Archivo 3: `concesionario.json` (Tareas 2, 3 y 4 completas)
```json
{
  "concesionario": {
    "nombre": "Albufera Motor",
    "licenciasFlota": 25,
    "abierto": true,
    "horario": {
      "entrega": "08:30",
      "devolucion": "20:00"
    },
    "direccion": {
      "calle": "Pista de Silla km 5",
      "ciudad": "Valencia",
      "codigoPostal": "46470",
      "coordenadas": [39.4125, -0.3841]
    },
    "contacto": {
      "email": "flota@albuferamotor.example",
      "telefonos": ["961223344", "961223355"],
      "web": null
    },
    "servicios": [
      "alquiler diario",
      "renting",
      "taller propio",
      "asistencia en carretera"
    ],
    "vehiculos": [
      {
        "id": "V10",
        "numeroPlaza": 10,
        "modelo": "Compacto \"Eco\"",
        "precioDia": 42.5,
        "plazas": 5,
        "disponible": true,
        "ubicacion": {
          "nave": 1,
          "zona": "Zona Norte"
        },
        "equipamiento": [
          "Climatizador",
          "Bluetooth",
          "Control de crucero"
        ],
        "valoraciones": [4, 5, 4]
      },
      {
        "id": "V22",
        "numeroPlaza": 22,
        "modelo": "SUV Familiar",
        "precioDia": 78.0,
        "plazas": 7,
        "disponible": true,
        "ubicacion": {
          "nave": 2,
          "zona": "Zona Sur"
        },
        "equipamiento": [
          "Navegador GPS",
          "Cámara 360",
          "Techo panorámico",
          "Bola remolque"
        ],
        "valoraciones": [5, 5]
      },
      {
        "id": "V35",
        "numeroPlaza": 35,
        "modelo": "Furgoneta carga",
        "precioDia": 64.9,
        "plazas": 2,
        "disponible": false,
        "ubicacion": {
          "nave": 1,
          "zona": "Zona Exterior"
        },
        "equipamiento": [],
        "valoraciones": []
      }
    ],
    "clientes": [
      {
        "id": "CL01",
        "nombre": "Sofía Martí",
        "fechaNacimiento": "1990-07-18",
        "documento": {
          "tipo": "DNI",
          "numero": "45678901L"
        },
        "fidelidad": {
          "nivel": "Premium",
          "puntos": 850
        },
        "preferencias": ["cambio automático", "recogida rápida"]
      },
      {
        "id": "CL02",
        "nombre": "David Orts",
        "fechaNacimiento": "1984-03-11",
        "documento": {
          "tipo": "Pasaporte",
          "numero": "ZP334455"
        },
        "fidelidad": null,
        "preferencias": []
      },
      {
        "id": "CL03",
        "nombre": "Nadia Haddad",
        "fechaNacimiento": "1998-12-05",
        "documento": {
          "tipo": "NIE",
          "numero": "Y9876543W"
        },
        "fidelidad": {
          "nivel": "Básico",
          "puntos": 120
        },
        "preferencias": ["vehículo eléctrico o híbrido"]
      }
    ],
    "alquileres": [
      {
        "id": "A001",
        "clienteId": "CL01",
        "vehiculoId": "V10",
        "fechas": {
          "recogida": "2026-12-04",
          "devolucion": "2026-12-07"
        },
        "estado": "Activo",
        "pagado": true,
        "extras": [
          {
            "servicio": "Seguro todo riesgo",
            "precioUnidad": 18.0,
            "cantidad": 3
          },
          {
            "servicio": "Silla infantil",
            "precioUnidad": 8.5,
            "cantidad": 3
          }
        ],
        "pago": {
          "metodo": "Tarjeta",
          "total": 250.47,
          "desglose": {
            "vehiculo": 127.5,
            "extras": 79.5,
            "impuestos": 43.47
          }
        },
        "notas": "Entrega con depósito lleno"
      },
      {
        "id": "A002",
        "clienteId": "CL02",
        "vehiculoId": "V22",
        "fechas": {
          "recogida": "2026-12-18",
          "devolucion": "2026-12-21"
        },
        "estado": "Pendiente",
        "pagado": false,
        "extras": [],
        "pago": null,
        "notas": null
      },
      {
        "id": "A003",
        "clienteId": "CL03",
        "vehiculoId": "V10",
        "fechas": {
          "recogida": "2027-01-10",
          "devolucion": "2027-01-12"
        },
        "estado": "Confirmado",
        "pagado": true,
        "extras": [
          {
            "servicio": "Conductor adicional",
            "precioUnidad": 15.0,
            "cantidad": 2
          }
        ],
        "pago": {
          "metodo": "Transferencia",
          "total": 139.15,
          "desglose": {
            "vehiculo": 85.0,
            "extras": 30.0,
            "impuestos": 24.15
          }
        },
        "notas": "Presenta carné internacional"
      },
      {
        "id": "A004",
        "clienteId": "CL01",
        "vehiculoId": "V22",
        "fechas": {
          "recogida": "2027-02-01",
          "devolucion": "2027-02-03"
        },
        "estado": "Cancelado",
        "pagado": false,
        "extras": [],
        "pago": null,
        "notas": "Cancelado con más de 48h de antelación"
      }
    ]
  }
}
```