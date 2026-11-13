# EXAMEN OFICIAL - 1a EVALUACION (MODELO A)

| CAMPO | DETALLE |
| :--- | :--- |
| **PROGRAMA** | Desarrollo de Aplicaciones Web (DAW) |
| **MODULO** | Lenguajes de marcas |
| **CURSO Y GRUPO** | 1o DAW, GRUPO A |
| **MODELO** | A |

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

**1. Una pagina turistica tiene un `<h1>` «Valencia», un `<h2>` «Lugares de interes» y, dentro de ese apartado, «La Albufera» marcado con `<h4>` porque el desarrollador quiere que el titulo «se vea mas pequeno». ¿Cual es el problema?**
- A) Ninguno: el nivel del encabezado solo controla el tamano, asi que cualquiera sirve.
- B) Se salta el nivel `<h3>`: la jerarquia deja de reflejar la estructura real del contenido, que es lo que usan lectores de pantalla y buscadores.
- C) `<h4>` solo puede utilizarse dentro de un elemento `<section>`.
- D) Solo puede existir un `<h2>` por pagina, igual que ocurre con `<h1>`.

**2. ¿Que enlace abre un sitio externo en una nueva pestana siguiendo las buenas practicas de seguridad?**
- A) `<a href="https://www.visitvalencia.com/" target="_blank">Pagina oficial de turismo de Valencia</a>`
- B) `<a href="https://www.visitvalencia.com/" rel="noopener noreferrer">Pagina oficial de turismo de Valencia</a>`
- C) `<a href="https://www.visitvalencia.com/" target="_self" rel="noopener noreferrer">Pagina oficial de turismo de Valencia</a>`
- D) `<a href="https://www.visitvalencia.com/" target="_blank" rel="noopener noreferrer">Pagina oficial de turismo de Valencia</a>`

**3. En una revision de accesibilidad y SEO se analizan los textos de los enlaces. ¿Cual de estos enlaces es el mas adecuado?**
- A) `<a href="mailto:info@codeacademy.example">Contactar con nosotros por correo electronico</a>`
- B) `<a href="mailto:info@codeacademy.example">Pincha aqui</a>`
- C) `<a href="mailto:info@codeacademy.example">Mas informacion</a>`
- D) `<a href="mailto:info@codeacademy.example">Enlace</a>`

**4. En el texto «La matricula termina el viernes y nunca se admiten solicitudes fuera de plazo» quieres marcar «viernes» como informacion especialmente importante y enfatizar la expresion «nunca», aportando significado (no solo estilo). ¿Que marcado es correcto?**
- A) La matricula termina el `<em>viernes</em>` y `<strong>nunca</strong>` se admiten solicitudes fuera de plazo.
- B) La matricula termina el `<b>viernes</b>` y `<i>nunca</i>` se admiten solicitudes fuera de plazo.
- C) La matricula termina el `<strong>viernes</strong>` y `<em>nunca</em>` se admiten solicitudes fuera de plazo.
- D) La matricula termina el `<h3>viernes</h3>` y `<h3>nunca</h3>` se admiten solicitudes fuera de plazo.

**5. Una pagina muestra «InglÃ©s» y «MÃ¡s» en lugar de «Inglés» y «Más». ¿Cual es la causa mas probable?**
- A) Falta `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.
- B) Falta `<meta charset="UTF-8">` en el `<head>` (o el archivo no esta guardado en UTF-8).
- C) Falta el atributo `lang="es"` en la etiqueta `<html>`.
- D) Falta el elemento `<title>` dentro del `<head>`.

**6. ¿Que error de anidacion contiene este codigo?**
```html
<ul>
  <li>Frontend</li>
  <ul>
    <li>HTML</li>
    <li>CSS</li>
  </ul>
  <li>Backend</li>
</ul>
```
- A) La sublista `<ul>` es hija directa de otra `<ul>`; debe ir dentro del `<li>` padre («Frontend»).
- B) Los `<li>` deben ir dentro de `<ol>` cuando hay sublistas.
- C) HTML no permite anidar una lista dentro de otra.
- D) Falta un `<li>` que envuelva toda la lista interior y exterior.

**7. Una pagina tiene: logotipo y menu arriba; contenido principal con una noticia que se entiende por si sola; un bloque lateral con contenido relacionado; y un pie con datos de contacto. ¿Que estructura usa correctamente la semantica HTML?**
- A) Un `<div>` por cada bloque, porque visualmente es identico y mas sencillo.
- B) `<header>`, `<main>` y `<footer>` anidados unos dentro de otros, empezando por `<footer>`.
- C) Tres elementos `<main>` (uno por zona) para que cada zona se considere principal.
- D) `<header>` con `<nav>`; despues `<main>` con un `<article>` y un `<aside>`; y por ultimo `<footer>`.

**8. ¿Cual de estos fragmentos cumple las buenas practicas y no provocaria errores de validacion?**
- A) `<p>Aprende <strong>HTML y <em>CSS</strong></em>.</p>`
- B) `<p>Aprende <div>HTML</div></p>`
- C) `<p>Aprende <strong>HTML</strong> y <em>CSS</em>.</p>`
- D) `<img src="logo.png">`

**9. En un formulario de matricula hay tres `<input type="radio">` (Presencial, Online, Mixta) con `id` distintos, pero el usuario puede marcar los tres a la vez. ¿Cual es la causa?**
- A) Los tres botones no comparten el mismo atributo `name`.
- B) Falta el atributo `required` en cada boton.
- C) Deberian ser `type="checkbox"`, que es el tipo para elegir una unica opcion.
- D) Falta `method="post"` en el elemento `<form>`.

**10. ¿Cual de estos documentos XML esta bien formado?**
- A) `<?xml version="1.0"?><rutina><nombre>Fuerza</nombre></Rutina>`
- B) `<?xml version="1.0"?><rutina><nombre>Fuerza</nombre><nivel>Alto</nivel></rutina>`
- C) `<rutina><nombre>Fuerza</nombre></rutina><rutina><nombre>Yoga</nombre></rutina>`
- D) `<rutina><nombre>Fuerza<nivel>Alto</nombre></nivel></rutina>`

**11. El XSD de un gimnasio declara `<xs:element name="nombre" type="xs:string"/>`, pero en el XML aparece `<Nombre>Press banca</Nombre>`, cerrado correctamente con `Nombre`. ¿Que resultado es correcto?**
- A) Es valido: XML no distingue entre mayusculas y minusculas.
- B) No esta bien formado, porque el nombre del elemento debe coincidir con el del XSD.
- C) Es valido, aunque el validador mostrara una advertencia.
- D) Esta bien formado, pero no es valido segun el XSD: `Nombre` y `nombre` son elementos distintos.

**12. En `tienda.xml` cada pedido pertenece a un cliente que ya figura en la seccion `clientes` (nombre, apellidos, email, telefono y direccion). Quieres evitar repetir informacion innecesariamente. ¿Que estrategia es adecuada?**
- A) Copiar los datos completos del cliente dentro de cada pedido para que sea autosuficiente.
- B) Guardar en el pedido solo el nombre del cliente, porque el nombre siempre es unico.
- C) Guardar los datos completos una sola vez en `clientes`, y que cada pedido indique unicamente el identificador del cliente.
- D) Guardar los datos del cliente como atributos del pedido para que ocupen menos espacio.

**13. Una empresa debe enviar su catalogo a un proveedor. Los sistemas de ambos deben interpretar que significa cada dato (precio, stock...), sin importar como se vea. ¿Que tecnologia encaja mejor y por que?**
- A) XML, porque permite etiquetas personalizadas y se centra en el significado de los datos.
- B) HTML, porque sus etiquetas predefinidas describen cualquier tipo de dato.
- C) XML, porque define la apariencia que tendran los datos en el navegador.
- D) HTML, porque esta pensado para almacenar y transportar datos entre sistemas.

**14. Con este XSD, se valida un XML que contiene `<ejercicio><series>4</series><nombre>Press banca</nombre><repeticiones>10</repeticiones></ejercicio>`. ¿Que ocurre y por que?**
```xml
<xs:element name="ejercicio">
  <xs:complexType>
    <xs:sequence>
      <xs:element name="nombre" type="xs:string"/>
      <xs:element name="series" type="xs:integer"/>
      <xs:element name="repeticiones" type="xs:integer"/>
    </xs:sequence>
  </xs:complexType>
</xs:element>
```
- A) Es valido: los hijos de un elemento complejo pueden ir en cualquier orden.
- B) Es invalido: `xs:sequence` exige que los hijos aparezcan en el orden declarado.
- C) Es invalido porque `series` debe ser de tipo `xs:string`.
- D) Esta mal formado, porque un elemento no puede tener tres hijos.

**15. En el XSD, el elemento `ejercicio` dentro de `ejercicios` pasa de `maxOccurs="unbounded"` a `maxOccurs="5"`. Una rutina del XML tiene 6 elementos `ejercicio`. ¿Que resultado es correcto?**
- A) Es valido: `maxOccurs` solo documenta el esquema, no restringe nada.
- B) Esta mal formado, porque XML no admite mas de cinco elementos iguales.
- C) Es valido: el validador acepta hasta 6 porque cuenta desde 0.
- D) Sigue estando bien formado, pero es invalido porque supera el numero maximo de ocurrencias.

**16. El XSD declara `<xs:attribute name="id" type="xs:string" use="required"/>` para `rutina`. Se elimina el atributo `id` de una `<rutina>` del XML. ¿Que ocurre?**
- A) El documento sigue bien formado, pero es invalido porque `use="required"` obliga a que el atributo exista.
- B) Es valido: un atributo siempre puede omitirse porque no forma parte de la estructura.
- C) Esta mal formado: todo elemento debe llevar al menos un atributo.
- D) Es valido, porque `type="xs:string"` admite tambien que el valor falte.

**17. Un `gimnasio.xml` tiene 2 elementos `<rutina>` (cada una con su `<nombre>`) y, entre ambas, 5 elementos `<ejercicio>` (cada uno con su `<nombre>`). ¿Cuantos nodos devuelve la expresion XPath `//nombre`?**
- A) 2 nodos, como `/gimnasio/rutina/nombre`.
- B) 7 nodos: los 2 nombres de rutina y los 5 de ejercicio.
- C) 5 nodos, solo los de los ejercicios.
- D) 0 nodos, porque la ruta no empieza en el elemento raiz.

**18. Estructura: `gimnasio/rutina` (atributo `id`; hijos `nombre`, `nivel`, `ejercicios`)/`ejercicios/ejercicio` (hijos `nombre`, `series`, `repeticiones`). ¿Que expresion devuelve las series del ejercicio «Sentadilla» de la rutina `RUT001`?**
- A) `/gimnasio/rutina[nombre='RUT001']/ejercicios/ejercicio[nombre='Sentadilla']/series`
- B) `/gimnasio/rutina[@id='RUT001']/ejercicios/ejercicio[@nombre='Sentadilla']/series`
- C) `/gimnasio/rutina[@id='RUT001']/ejercicios/ejercicio[nombre='Sentadilla']/series`
- D) `/gimnasio/rutina/@RUT001/ejercicios/ejercicio/Sentadilla/series`

**19. Para garantizar que `<precio>` solo admita numeros decimales y `<stock>` solo numeros enteros, ¿que debe utilizarse?**
- A) Basta con que el documento este bien formado, porque XML ya comprueba los tipos de datos.
- B) Una expresion XPath con el predicado `[precio>0]`.
- C) La declaracion `<?xml version="1.0"?>` al inicio del documento.
- D) Un XSD que declare `type="xs:decimal"` y `type="xs:integer"`.

**20. ¿Cual de estos fragmentos es JSON sintacticamente correcto?**
- A) `{ nombre: "Rosa", "edad": 41 }`
- B) `{ "nombre": "Rosa", "alergias": ["látex", "polen"], "seguro": null }`
- C) `{ "nombre": "Rosa", "edad": 41, }`
- D) `{ "nombre": "Rosa", "activo": True }`

**21. Un programador guarda `"duracionDias": "14"` en lugar de `"duracionDias": 14`. ¿Que consecuencia tiene?**
- A) Es JSON valido, pero el valor es texto y no numero: habria que convertirlo antes de operar con el.
- B) Ninguna: JSON convierte automaticamente a numero al leer el archivo.
- C) El JSON es invalido, porque las propiedades numericas no admiten comillas ni texto.
- D) El valor se interpreta como `null` por llevar comillas.

**22. Cada paciente puede tener varios diagnosticos, cada uno con `fecha`, `diagnostico` y `tratamiento`. ¿Que estructura es la adecuada para `historial`?**
- A) Un objeto con las propiedades `diagnostico1`, `diagnostico2`, `diagnostico3`...
- B) Un unico objeto que repite varias veces la clave `diagnostico`.
- C) Un array de textos donde cada elemento concatena fecha, diagnostico y medicamento.
- D) Un array de objetos, cada uno con `fecha`, `diagnostico` y `tratamiento`.

**23. Con este JSON, ¿que ruta accede al medicamento del primer diagnostico del segundo paciente? (los indices de un array empiezan en 0)**
```json
{
  "clinica": {
    "pacientes": [
      {
        "nombre": "Rosa",
        "historial": [
          { "tratamiento": { "medicamento": "Ibuprofeno" } }
        ]
      },
      {
        "nombre": "Tomás",
        "historial": [
          { "tratamiento": { "medicamento": "Enalapril" } },
          { "tratamiento": { "medicamento": "Atorvastatina" } }
        ]
      },
      {
        "nombre": "Clara",
        "historial": [
          { "tratamiento": { "medicamento": "Hidrocortisona" } }
        ]
      }
    ]
  }
}
```
- A) `clinica.pacientes[2].historial[1].tratamiento.medicamento`
- B) `clinica.pacientes[1].historial.tratamiento.medicamento`
- C) `clinica.pacientes[1].historial[0].tratamiento.medicamento`
- D) `clinica.pacientes[0].historial[1].tratamiento.medicamento`

**24. El array `citas` contiene objetos con `id`, `pacienteId` y `medicoId`. ¿Como se obtienen las citas del medico cuyo `id` es 2?**
- A) Recorriendo `citas` y quedandose con las que tienen `medicoId` igual a 2.
- B) Mirando la cita que ocupa la posicion 2 del array.
- C) Leyendo el array `citas` que cada objeto de `medicos` contiene.
- D) Comparando el `id` de cada cita con el `id` del medico: las citas con `id` igual a 2.

**25. El diseno exige que `seguro` sea un objeto con `compania` y `numeroPoliza`, o `null` si el paciente no tiene seguro. ¿Como se representa a un paciente sin seguro?**
- A) `"seguro": "null"`
- B) `"seguro": {}`
- C) `"seguro": false`
- D) `"seguro": null`

**26. Se migra a JSON el elemento XML `<producto id="P001"><nombre>Ratón</nombre><activo>true</activo></producto>`. ¿Que resultado conserva mejor la informacion y los tipos?**
- A) `{ "id": "P001", "nombre": "Ratón", "activo": "true" }`
- B) `{ "id": "P001", "nombre": "Ratón", "activo": true }`
- C) `{ id="P001", nombre="Ratón", activo=true }`
- D) `{ "producto": "P001 Ratón true" }`

**27. Un editor marca un error en este JSON. ¿Cual es el problema?**
```json
{
  "medicos": [
    { "id": 1, "nombre": "Dra. Navarro", "consultas": ["lunes", "martes"] }
    { "id": 2, "nombre": "Dr. Romero", "consultas": ["viernes"] }
  ]
}
```
- A) Un array de objetos no puede contener mas de un objeto.
- B) `consultas` debe ser un objeto, no un array de textos.
- C) Falta la coma que separa los dos objetos del array.
- D) Las claves `id` y `nombre` no pueden repetirse en objetos distintos del mismo array.

---

### Preguntas de respuesta abierta

1. **Explica por que no seria buena practica utilizar `<h3>` simplemente porque «se ve mas pequeno». Indica, ademas, que usarias para cambiar el aspecto de un titulo sin alterar la jerarquia del documento.**
2. **Distingue entre un documento XML «bien formado» y uno «valido». Pon un ejemplo de cambio sobre un `gimnasio.xml` que lo deje mal formado y otro ejemplo de cambio que lo deje bien formado pero invalido respecto a su XSD.**
3. **Representa en XML y en JSON el mismo producto (`id` P001, `nombre` Ratón, `precio` 19.99, `stock` 20, `activo` true) y senala tres diferencias entre ambas representaciones.**

---

## PARTE 2: Evaluacion practica de conocimientos (90 min)

### Enunciado — Caso: Hotel Costa Valencia (modelado de datos en JSON)

El **Hotel Costa Valencia** va a migrar la gestion de sus habitaciones, clientes y reservas a una nueva aplicacion que intercambia la informacion en formato JSON. Te encargan crear el archivo `hotel.json` con todos los datos de la ficha siguiente, disenando una estructura jerarquica y coherente que combine objetos, arrays, anidaciones y los distintos tipos de datos de JSON.

El archivo debe poder abrirse sin errores en Visual Studio Code y ser comprensible para otra persona sin ninguna explicacion adicional.

El archivo tendra un objeto raiz con una unica propiedad `hotel` que contiene todo lo demas.

#### Informacion del hotel

| Bloque | Datos |
| :--- | :--- |
| **Datos generales** | Nombre: Hotel Costa Valencia · Estrellas: 4 · Hotel en activo: sí · Check-in: 14:00 · Check-out: 12:00 |
| **Direccion** | Avenida del Puerto 120, Valencia, código postal 46023 · Coordenadas en el mapa: 39.4699 y -0.3763 |
| **Contacto** | Email: reservas@costavalencia.example · Teléfonos: 961112233 y 961112244 · Web: aún no tiene |
| **Servicios** | wifi, desayuno, parking, spa |

#### Habitaciones

| ID | Num. | Nombre | Precio noche | Capac. | Disp. | Ubicacion | Valoraciones | Equipamiento |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **H101** | 101 | Habitación doble | 89,90 EUR | 2 | Sí | Planta 1 · Mar | 4, 5, 5 | TV, Aire acondicionado, Minibar |
| **H205** | 205 | Suite "Mar" | 189,00 EUR | 4 | Sí | Planta 2 · Mar | 5, 5 | TV, Aire acondicionado, Jacuzzi, Terraza |
| **H310** | 310 | Individual económica | 59,50 EUR | 1 | No | Planta 3 · Ciudad | *(ninguna)* | *(ninguno)* |

#### Clientes

| ID | Nombre | Nacimiento | Documento | Fidelidad | Preferencias |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **C001** | Laura Giménez | 1988-04-12 | DNI 12345678Z | Oro · 1250 puntos | planta alta, almohada extra |
| **C002** | Marc Soler | 1995-09-30 | Pasaporte XK918273 | No tiene programa | *(ninguna)* |
| **C003** | Anna Petrova | 1979-01-22 | NIE Y1234567X | Plata · 430 puntos | sin gluten |

#### Reservas

| ID | Cliente | Habit. | Fechas | Estado | Pagada | Extras | Pago y notas |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **R001** | C001 | H101 | 10/12/2026 al 13/12/2026 | Confirmada | Sí | Desayuno 12,50 EUR x 3 · Parking 15,00 EUR x 3 | Tarjeta · habitación 269,70 · extras 82,50 · impuestos 35,22 · total 387,42 · Nota: Llegada tardía |
| **R002** | C002 | H205 | 20/12/2026 al 22/12/2026 | Pendiente | No | *(ninguno)* | Sin pago todavía · sin notas |
| **R003** | C003 | H101 | 05/01/2027 al 08/01/2027 | Confirmada | Sí | Spa 40,00 EUR x 1 | Transferencia · habitación 269,70 · extras 40,00 · impuestos 30,97 · total 340,67 · Nota: Sin gluten en el desayuno |
| **R004** | C001 | H205 | 14/02/2027 al 16/02/2027 | Cancelada | No | *(ninguno)* | Sin pago · Nota: Cancelada por la clienta |

---

### Tareas a realizar

- **Tarea 1. Detecta y corrige errores (10 min):** El siguiente fragmento contiene varios errores, de sintaxis y de tipo de dato. Guardalo como `fragmento_corregido.json` ya corregido y, en `respuestas.txt`, anota cada error encontrado y por que lo es:
```json
{
  nombre: 'Hotel Costa Valencia',
  "estrellas": "4",
  "activo": True,
  "servicios": ["wifi", "parking",],
  "web": "null"
}
```
- **Tarea 2. Estructura base: objetos y tipos (20 min):** En `hotel.json` crea el objeto raiz y, dentro de `hotel`, los datos generales, la `direccion` y el `contacto`:
  - Usa el tipo de dato adecuado en cada valor (texto, numero, booleano, null) y justificalo en `respuestas.txt` para `estrellas`, `codigoPostal` y `web`.
  - `direccion` y `contacto` son objetos anidados.
  - `servicios` y `telefonos` son arrays de textos; `coordenadas` es un array de numeros.
- **Tarea 3. Habitaciones: arrays de objetos y anidacion (20 min):** Anade la propiedad `habitaciones` como array de objetos. Cada habitacion tiene `id`, `numero`, `nombre`, `precioNoche`, `capacidad`, `disponible` y:
  - un objeto anidado `ubicacion` con `planta` y `orientacion`;
  - un array `equipamiento` de textos (vacio cuando no hay);
  - un array `valoraciones` de numeros (vacio cuando no hay).
  - Cuida los caracteres especiales del nombre de la suite y escribe los decimales correctamente.
- **Tarea 4. Clientes y reservas: relaciones y jerarquia profunda (30 min):** Anade `clientes` y `reservas` como arrays de objetos:
  - Cada cliente incluye un objeto `documento` (`tipo` y `numero`), un valor `fidelidad` (objeto con `nivel` y `puntos`, o `null` si no tiene programa) y un array `preferencias`.
  - Cada reserva se relaciona con su cliente y su habitacion mediante identificadores (`clienteId`, `habitacionId`), sin copiar sus datos.
  - Cada reserva contiene un objeto `fechas` (`entrada` y `salida`), el `estado`, un booleano `pagado` y un array `extras` de objetos (`servicio`, `precioUnidad` y `cantidad`).
  - Cada reserva contiene un objeto `pago` (o `null` si no hay pago) con `metodo`, `total` y un objeto anidado `desglose` (`habitacion`, `extras` e `impuestos`), y una propiedad `notas` (texto o `null`).
  - Escribe las fechas como texto en formato `AAAA-MM-DD`.
- **Tarea 5. Comprobacion y navegacion (10 min):** Da formato al archivo con VS Code y comprueba que no muestra errores en el panel de problemas. Despues, en `respuestas.txt`, escribe:
  - **(a)** la ruta completa para acceder al importe de `extras` del desglose del pago de la primera reserva, y la ruta a la `cantidad` del segundo extra de esa misma reserva;
  - **(b)** como averiguarias que reservas pertenecen a la habitacion `H101`;
  - **(c)** como averiguarias que clientes no tienen programa de fidelidad.

---

## PARTE 3: Defensa individual / argumentacion (3-5 min)

Al finalizar las partes 1 y 2 del examen, realiza la entrega (`hotel.json`, `fragmento_corregido.json`, `respuestas.txt` y `captura_json.png` comprimidos en `Apellido_Nombre_ModeloA.zip`) y espera a que el profesor te llame para responder a tres preguntas sobre la practica realizada.

---
---

# SOLUCIONARIO COMPLETO — MODELO A

## 1. Solucionario Parte 1: Tipo Test

| Pregunta | Respuesta | Pregunta | Respuesta | Pregunta | Respuesta |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **1** | **B** | **10** | **B** | **19** | **D** |
| **2** | **D** | **11** | **D** | **20** | **B** |
| **3** | **A** | **12** | **C** | **21** | **A** |
| **4** | **C** | **13** | **A** | **22** | **D** |
| **5** | **B** | **14** | **B** | **23** | **C** |
| **6** | **A** | **15** | **D** | **24** | **A** |
| **7** | **D** | **16** | **A** | **25** | **D** |
| **8** | **C** | **17** | **B** | **26** | **B** |
| **9** | **A** | **18** | **C** | **27** | **C** |

---

## 2. Solucionario Parte 1: Preguntas Abiertas

### Pregunta 1
- **Por que no usar `<h3>` solo por el tamano visual:** Las etiquetas de encabezado (`<h1>` a `<h6>`) definen la estructura semantica y el indice jerarquico del documento, no su estilo visual. Si se salta de un `<h1>` o se elige un `<h3>` solo por su apariencia, los lectores de pantalla (accesibilidad) y los motores de busqueda (SEO) interpretan una jerarquia rota o incoherente.
- **Que usar para cambiar el aspecto sin alterar la jerarquia:** Se debe mantener el nivel de encabezado que corresponda logicamente (por ejemplo, `<h2>`) y modificar su tamano de fuente y apariencia utilizando hojas de estilo **CSS** (mediante la propiedad `font-size`).

### Pregunta 2
- **Diferencia:** Un documento XML **bien formado** cumple las reglas sintacticas basicas de XML (un unico elemento raiz, todas las etiquetas abiertas se cierran en el orden correcto sin solaparse, distincion entre mayusculas y minusculas, atributos entre comillas). Un documento XML **valido** es un documento bien formado que, ademas, cumple todas las restricciones de estructura, elementos permitidos, cardinalidad y tipos de datos definidas en un esquema (XSD o DTD).
- **Ejemplo de cambio que deje `gimnasio.xml` mal formado:** Cambiar la etiqueta de cierre `</rutina>` por `</Rutina>` (con mayuscula) o eliminar la etiqueta de cierre `</nombre>`.
- **Ejemplo de cambio que deje `gimnasio.xml` bien formado pero invalido frente a su XSD:** Escribir `<series>cuatro</series>` cuando el XSD exige `type="xs:integer"`, o poner los hijos de `<ejercicio>` en un orden distinto al establecido por `<xs:sequence>`.

### Pregunta 3
- **En XML:**
```xml
<producto id="P001">
  <nombre>Ratón</nombre>
  <precio>19.99</precio>
  <stock>20</stock>
  <activo>true</activo>
</producto>
```
- **En JSON:**
```json
{
  "id": "P001",
  "nombre": "Ratón",
  "precio": 19.99,
  "stock": 20,
  "activo": true
}
```
- **Tres diferencias entre ambas representaciones:**
  1. **Formato y sintaxis:** XML usa etiquetas de apertura y cierre (`<precio>19.99</precio>`) y atributos (`id="P001"`), mientras que JSON usa pares `"clave": valor` separados por comas dentro de un objeto `{...}`.
  2. **Tipado de datos:** En JSON los numeros (`19.99`, `20`) y booleanos (`true`) se escriben sin comillas como tipos nativos; en XML todo el contenido es texto plano a menos que se valide con un esquema externo (XSD).
  3. **Concision:** JSON es menos verboso al no repetir el nombre del campo al final de cada dato, lo que reduce el tamano del archivo y facilita su lectura directa en JavaScript.

---

## 3. Solucionario Parte 2: Practica JSON

### Archivo 1: `fragmento_corregido.json` (Tarea 1)
```json
{
  "nombre": "Hotel Costa Valencia",
  "estrellas": 4,
  "activo": true,
  "servicios": ["wifi", "parking"],
  "web": null
}
```

### Archivo 2: `respuestas.txt` (Tareas 1, 2 y 5)
```text
=== TAREA 1: ERRORES DETECTADOS ===
1. nombre: 'Hotel Costa Valencia' -> La clave "nombre" no lleva comillas dobles obligatorias en JSON, y el valor usa comillas simples (' ') en lugar de comillas dobles (" ").
2. "estrellas": "4" -> Error de tipo de dato: el número de estrellas del hotel es una cantidad entera (4), pero está escrito entre comillas como texto ("4").
3. "activo": True -> Error de sintaxis: en JSON los valores booleanos deben escribirse íntegramente en minúsculas (true o false), no con mayúscula inicial.
4. "servicios": ["wifi", "parking",] -> Error de sintaxis: hay una coma sobrante (trailing comma) después del último elemento del array ("parking").
5. "web": "null" -> Error de tipo de dato: al escribir "null" entre comillas se guarda un texto literal de cuatro letras en vez del valor especial null que representa ausencia de valor.

=== TAREA 2: JUSTIFICACION DE TIPOS ===
- estrellas (number -> 4): Representa una categoría numérica entera con la que se pueden realizar comparaciones o filtros matemáticos (ej. hoteles de 4 o más estrellas).
- codigoPostal (string -> "46023"): Es un código identificador postal con formato textual fijo (en muchas provincias empieza por 0, como "03001", que se perdería al guardarlo como número) y no se realizan operaciones aritméticas con él.
- web (null -> null): El enunciado indica que el hotel aún no tiene web, por lo que debe emplearse el literal null (sin comillas) para reflejar la ausencia de dato.

=== TAREA 5: COMPROBACION Y NAVEGACION ===
(a) Rutas de acceso:
- Importe de extras del desglose del pago de la primera reserva:
  hotel.reservas[0].pago.desglose.extras
- Cantidad del segundo extra de esa misma reserva:
  hotel.reservas[0].extras[1].cantidad

(b) Cómo averiguar qué reservas pertenecen a la habitación H101:
Recorriendo el array hotel.reservas y filtrando aquellos objetos cuya propiedad habitacionId sea igual a "H101".

(c) Cómo averiguar qué clientes no tienen programa de fidelidad:
Recorriendo el array hotel.clientes y comprobando qué objetos tienen la propiedad fidelidad con valor igual a null.
```

### Archivo 3: `hotel.json` (Tareas 2, 3 y 4 completas)
```json
{
  "hotel": {
    "nombre": "Hotel Costa Valencia",
    "estrellas": 4,
    "activo": true,
    "horario": {
      "checkIn": "14:00",
      "checkOut": "12:00"
    },
    "direccion": {
      "calle": "Avenida del Puerto 120",
      "ciudad": "Valencia",
      "codigoPostal": "46023",
      "coordenadas": [39.4699, -0.3763]
    },
    "contacto": {
      "email": "reservas@costavalencia.example",
      "telefonos": ["961112233", "961112244"],
      "web": null
    },
    "servicios": ["wifi", "desayuno", "parking", "spa"],
    "habitaciones": [
      {
        "id": "H101",
        "numero": 101,
        "nombre": "Habitación doble",
        "precioNoche": 89.9,
        "capacidad": 2,
        "disponible": true,
        "ubicacion": {
          "planta": 1,
          "orientacion": "Mar"
        },
        "equipamiento": ["TV", "Aire acondicionado", "Minibar"],
        "valoraciones": [4, 5, 5]
      },
      {
        "id": "H205",
        "numero": 205,
        "nombre": "Suite \"Mar\"",
        "precioNoche": 189.0,
        "capacidad": 4,
        "disponible": true,
        "ubicacion": {
          "planta": 2,
          "orientacion": "Mar"
        },
        "equipamiento": ["TV", "Aire acondicionado", "Jacuzzi", "Terraza"],
        "valoraciones": [5, 5]
      },
      {
        "id": "H310",
        "numero": 310,
        "nombre": "Individual económica",
        "precioNoche": 59.5,
        "capacidad": 1,
        "disponible": false,
        "ubicacion": {
          "planta": 3,
          "orientacion": "Ciudad"
        },
        "equipamiento": [],
        "valoraciones": []
      }
    ],
    "clientes": [
      {
        "id": "C001",
        "nombre": "Laura Giménez",
        "fechaNacimiento": "1988-04-12",
        "documento": {
          "tipo": "DNI",
          "numero": "12345678Z"
        },
        "fidelidad": {
          "nivel": "Oro",
          "puntos": 1250
        },
        "preferencias": ["planta alta", "almohada extra"]
      },
      {
        "id": "C002",
        "nombre": "Marc Soler",
        "fechaNacimiento": "1995-09-30",
        "documento": {
          "tipo": "Pasaporte",
          "numero": "XK918273"
        },
        "fidelidad": null,
        "preferencias": []
      },
      {
        "id": "C003",
        "nombre": "Anna Petrova",
        "fechaNacimiento": "1979-01-22",
        "documento": {
          "tipo": "NIE",
          "numero": "Y1234567X"
        },
        "fidelidad": {
          "nivel": "Plata",
          "puntos": 430
        },
        "preferencias": ["sin gluten"]
      }
    ],
    "reservas": [
      {
        "id": "R001",
        "clienteId": "C001",
        "habitacionId": "H101",
        "fechas": {
          "entrada": "2026-12-10",
          "salida": "2026-12-13"
        },
        "estado": "Confirmada",
        "pagado": true,
        "extras": [
          {
            "servicio": "Desayuno",
            "precioUnidad": 12.5,
            "cantidad": 3
          },
          {
            "servicio": "Parking",
            "precioUnidad": 15.0,
            "cantidad": 3
          }
        ],
        "pago": {
          "metodo": "Tarjeta",
          "total": 387.42,
          "desglose": {
            "habitacion": 269.7,
            "extras": 82.5,
            "impuestos": 35.22
          }
        },
        "notas": "Llegada tardía"
      },
      {
        "id": "R002",
        "clienteId": "C002",
        "habitacionId": "H205",
        "fechas": {
          "entrada": "2026-12-20",
          "salida": "2026-12-22"
        },
        "estado": "Pendiente",
        "pagado": false,
        "extras": [],
        "pago": null,
        "notas": null
      },
      {
        "id": "R003",
        "clienteId": "C003",
        "habitacionId": "H101",
        "fechas": {
          "entrada": "2027-01-05",
          "salida": "2027-01-08"
        },
        "estado": "Confirmada",
        "pagado": true,
        "extras": [
          {
            "servicio": "Spa",
            "precioUnidad": 40.0,
            "cantidad": 1
          }
        ],
        "pago": {
          "metodo": "Transferencia",
          "total": 340.67,
          "desglose": {
            "habitacion": 269.7,
            "extras": 40.0,
            "impuestos": 30.97
          }
        },
        "notas": "Sin gluten en el desayuno"
      },
      {
        "id": "R004",
        "clienteId": "C001",
        "habitacionId": "H205",
        "fechas": {
          "entrada": "2027-02-14",
          "salida": "2027-02-16"
        },
        "estado": "Cancelada",
        "pagado": false,
        "extras": [],
        "pago": null,
        "notas": "Cancelada por la clienta"
      }
    ]
  }
}
```