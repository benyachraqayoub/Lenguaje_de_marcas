# EXAMEN OFICIAL - 1a EVALUACION (MODELO D)

| CAMPO | DETALLE |
| :--- | :--- |
| **PROGRAMA** | Desarrollo de Aplicaciones Web (DAW) |
| **MODULO** | Lenguajes de marcas |
| **CURSO Y GRUPO** | 1o DAW, GRUPO A |
| **MODELO** | D |

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

**1. En la web de un festival de musica, el nombre del festival esta en un `<h1>`, el apartado «Conciertos del sabado» esta en un `<h2>`, y cada grupo musical dentro de ese apartado se pone con `<h6>` para que ocupe poco espacio. ¿Por que es una mala practica?**
- A) Porque `<h6>` solo sirve para notas a pie de pagina.
- B) Porque un documento HTML no puede tener simultaneamente `<h1>` y `<h6>`.
- C) Porque se saltan los niveles `<h3>`, `<h4>` y `<h5>`, rompiendo el esquema jerarquico del documento que utilizan los lectores de pantalla y buscadores.
- D) No es mala practica: elegir encabezados segun el tamano deseado es la forma estandar de trabajar en HTML.

**2. Quieres crear un enlace al portal del Ministerio de Educacion que se abra en una pestana nueva evitando vulnerabilidades de seguridad (`tabnabbing`). ¿Que etiqueta debes escribir?**
- A) `<a href="https://www.educacion.gob.es" target="_parent" rel="noopener">Portal del Ministerio de Educacion</a>`
- B) `<a href="https://www.educacion.gob.es" open="new" secure="true">Portal del Ministerio de Educacion</a>`
- C) `<a href="https://www.educacion.gob.es" target="_blank">Portal del Ministerio de Educacion</a>`
- D) `<a href="https://www.educacion.gob.es" target="_blank" rel="noopener noreferrer">Portal del Ministerio de Educacion</a>`

**3. Al auditar la accesibilidad de una tienda online, ¿cual de los siguientes enlaces resulta descriptivo y adecuado fuera de contexto?**
- A) `<a href="devoluciones.html">Consultar la politica de cambios y devoluciones</a>`
- B) `<a href="devoluciones.html">Pulsa aqui</a>`
- C) `<a href="devoluciones.html">Info</a>`
- D) `<a href="devoluciones.html">https://tienda.example/devoluciones.html</a>`

**4. En el aviso «Es obligatorio llevar calzado deportivo y jamas acceder con comida a la pista», ¿como debes marcar «obligatorio» (fuerte importancia) y «jamas» (enfasis de lectura) con valor semantico?**
- A) `<b>obligatorio</b>` e `<i>jamas</i>`
- B) `<strong>obligatorio</strong>` y `<em>jamas</em>`
- C) `<em>obligatorio</em>` y `<strong>jamas</strong>`
- D) `<big>obligatorio</big>` y `<cite>jamas</cite>`

**5. Un alumno sube su practica HTML y en el navegador se lee «DiseÃ±o de Interfaces» en vez de «Diseño de Interfaces». ¿Cual es el motivo?**
- A) Ha usado `<h1>` en lugar de `<h2>`.
- B) Falta la etiqueta `<!DOCTYPE html>` al final del archivo.
- C) No ha incluido `<meta charset="UTF-8">` en el `<head>` (o el archivo no se ha guardado con codificacion UTF-8).
- D) El navegador no soporta la letra ñ en etiquetas de parrafo.

**6. ¿Que error estructural presenta esta lista en HTML?**
```html
<ul>
  <li>Deportes de raqueta</li>
  <ul>
    <li>Tenis</li>
    <li>Padel</li>
  </ul>
  <li>Natacion</li>
</ul>
```
- A) La etiqueta `<ul>` interior no puede ser hija directa de la `<ul>` exterior; debe colocarse dentro de `<li>Deportes de raqueta ... </li>`.
- B) En HTML las listas anidadas siempre tienen que alternar `<ul>` con `<ol>`.
- C) Los elementos «Tenis» y «Padel» deben usar la etiqueta `<subli>`.
- D) No hay ningun error; el validador W3C lo da por valido.

**7. ¿Cual de las siguientes estructuras representa mejor una pagina web semantica con cabecera de navegacion, bloque principal con un articulo y barra lateral complementaria, mas pie de pagina?**
- A) `<head>` (con `<nav>`), `<body>` (con `<div1>` y `<div2>`) y `<foot>`.
- B) Tres bloques `<article>` seguidos sin `<main>`.
- C) Un `<aside>` como contenedor raiz de `<header>`, `<main>` y `<footer>`.
- D) `<header>` (con `<nav>`), `<main>` (con `<article>` y `<aside>`) y `<footer>`.

**8. ¿Cual de estos fragmentos HTML es valido segun los estandares actuales?**
- A) `<p>Entrena <strong>fuerza y <em>resistencia</strong></em>.</p>`
- B) `<p>Horario de manana: <ul><li>09:00</li></ul></p>`
- C) `<p>Entrena <strong>fuerza</strong> y <em>resistencia</em>.</p>`
- D) `<a href="contacto.html"><h2>Contacto</a></h2>`

**9. En un formulario de inscripcion deportiva hay tres botones `<input type="radio">` para elegir talla de camiseta (S, M, L), pero el usuario puede dejar los tres marcados simultaneamente. ¿Por que sucede?**
- A) Porque tienen distinto atributo `id`.
- B) Porque cada `<input>` tiene un valor distinto en su atributo `name` (o no tienen atributo `name`).
- C) Porque falta el atributo `placeholder` en cada boton.
- D) Porque los botones de tipo `radio` permiten seleccion multiple por defecto.

**10. ¿Cual de estos documentos XML esta bien formado?**
- A) `<?xml version="1.0"?><socio><nombre>Iván</nombre><cuota>35</Cuota></socio>`
- B) `<?xml version="1.0"?><socio id="S01"><nombre>Iván</nombre><cuota>35</cuota></socio>`
- C) `<?xml version="1.0"?><socio id=S01><nombre>Iván</nombre></socio>`
- D) `<socio><nombre>Iván</nombre></socio><socio><nombre>Marta</nombre></socio>`

**11. El esquema `centro.xsd` define `<xs:element name="capacidad" type="xs:integer"/>`. En `centro.xml` se escribe `<Capacidad>25</Capacidad>`. ¿Que ocurre al validarlo?**
- A) Esta mal formado porque `Capacidad` empieza con mayuscula.
- B) Es valido porque el contenido `25` si es un numero entero.
- C) Es invalido porque `25` no lleva decimales.
- D) Esta bien formado (abre y cierra con `Capacidad`), pero es invalido respecto al XSD porque los nombres de elementos distinguen mayusculas de minusculas.

**12. En `polideportivo.xml` existe una seccion `socios` (con todos sus datos personales) y otra seccion `reservasPista`. Un socio realiza decenas de reservas al mes. ¿Que diseno es el mas apropiado?**
- A) Copiar el DNI, nombre, direccion y cuenta bancaria del socio dentro de cada reserva de pista.
- B) Almacenar los datos completos del socio una vez en `socios` con su `id`, y que cada reserva incluya unicamente el identificador del socio (`socioId`).
- C) No guardar que socio hace la reserva para que el archivo ocupe menos.
- D) Guardar todas las reservas del ano como atributos dentro de la etiqueta `<socio>`.

**13. Una federacion deportiva quiere publicar los resultados de los partidos para que las aplicaciones moviles de distintos medios de comunicacion los importen automaticamente. ¿Por que es adecuado XML?**
- A) Porque XML permite definir etiquetas semanticas personalizadas (`<partido>`, `<golesLocal>`) pensadas para el intercambio estructurado de datos entre sistemas.
- B) Porque XML aplica automaticamente colores y animaciones a la tabla de clasificacion.
- C) Porque HTML no permite escribir numeros dentro de etiquetas.
- D) Porque XML es un formato comprimido que no puede abrirse con un editor de texto.

**14. Segun este fragmento XSD, ¿que pasa si el XML tiene `<sala><aforo>20</aforo><nombre>Spinning</nombre><planta>1</planta></sala>`?**
```xml
<xs:element name="sala">
  <xs:complexType>
    <xs:sequence>
      <xs:element name="nombre" type="xs:string"/>
      <xs:element name="planta" type="xs:integer"/>
      <xs:element name="aforo" type="xs:integer"/>
    </xs:sequence>
  </xs:complexType>
</xs:element>
```
- A) Es valido porque estan los tres elementos y sus tipos de datos coinciden.
- B) Esta mal formado porque `<aforo>` esta en primera posicion.
- C) Es invalido porque `<xs:sequence>` obliga a que los elementos hijos aparezcan exactamente en el orden `nombre`, `planta`, `aforo`.
- D) Es invalido porque `planta` y `aforo` no pueden tener el mismo tipo `xs:integer`.

**15. En el XSD de un torneo, el elemento `<jugador>` dentro de `<equipo>` tiene `minOccurs="5"` y `maxOccurs="12"`. Si un equipo en el XML tiene 14 elementos `<jugador>`, ¿cual es el resultado?**
- A) El XML esta mal formado porque ninguna etiqueta XML puede repetirse mas de 10 veces.
- B) El XML es valido porque tiene mas del minimo exigido (`5`).
- C) El validador ignora los 2 ultimos jugadores y da el documento por valido.
- D) El XML esta bien formado, pero es invalido porque supera el `maxOccurs="12"` definido en el XSD.

**16. El XSD declara `<xs:attribute name="codigo" type="xs:string" use="required"/>` en el elemento `<actividad>`. Si borramos `codigo="ACT01"` de una `<actividad>` en el XML, ¿que sucede?**
- A) El documento sigue bien formado, pero pasa a ser invalido porque `use="required"` exige la presencia del atributo.
- B) El documento queda mal formado porque `<actividad>` se queda vacia de atributos.
- C) Sigue siendo valido porque los atributos nunca se validan en XSD.
- D) Da error de codificacion UTF-8.

**17. En `club.xml` hay 3 elementos `<entrenador>` (cada uno con un hijo `<nombre>`) y 6 elementos `<actividad>` (cada una tambien con un hijo `<nombre>`). ¿Cuantos nodos devuelve la expresion XPath `//nombre`?**
- A) 3 nodos (solo los del primer nivel).
- B) 9 nodos (los 3 nombres de entrenador mas los 6 nombres de actividad).
- C) 6 nodos (solo los de las actividades).
- D) 0 nodos.

**18. Estructura XML: `/gimnasio/sala[@id='S02']/clases/clase[monitor='Laura']/plazas`. ¿Que selecciona esta expresion XPath?**
- A) Las salas cuyo elemento hijo `id` es `'S02'` y tienen un atributo `monitor='Laura'`.
- B) Todas las clases de la monitora `'Laura'` en todas las salas del gimnasio.
- C) El elemento `plazas` de las clases cuyo elemento hijo `monitor` vale `'Laura'`, dentro de la sala que tiene el atributo `id='S02'`.
- D) El atributo `plazas` del elemento `Laura`.

**19. En un XSD quieres restringir `<cuota>` a numeros con decimales y `<aforo>` a numeros enteros. ¿Que declaracion es la correcta?**
- A) `type="xs:decimal"` para `cuota` y `type="xs:integer"` para `aforo`.
- B) `type="xs:string"` para ambos porque en XML todo es texto.
- C) `type="xs:float"` para `aforo` y `type="xs:boolean"` para `cuota`.
- D) Usar XPath en lugar de XSD.

**20. ¿Cual de estos fragmentos JSON es sintacticamente valido?**
- A) `{ "socio": "Marta", "cuotaPagada": True, "deportes": ["tenis", "natación"], "descuento": null }`
- B) `{ socio: "Marta", "cuotaPagada": true, "deportes": ["tenis", "natación"] }`
- C) `{ "socio": "Marta", "cuotaPagada": true, "deportes": ["tenis", "natación"], "descuento": null }`
- D) `{ "socio": "Marta", "cuotaPagada": true, "deportes": ["tenis", "natación"], }`

**21. En un JSON se escribe `"aforoMaximo": "50"` en vez de `"aforoMaximo": 50`. ¿Que consecuencia tiene?**
- A) El archivo JSON no se puede abrir porque los digitos no pueden ir entre comillas.
- B) El archivo JSON es valido, pero el valor se almacena como texto (`string`) en lugar de numero (`number`).
- C) Se interpreta como el valor booleano `true`.
- D) Es obligatorio ponerlo con comillas si el numero es par.

**22. Un socio puede realizar varias reservas de pista, y de cada reserva interesa guardar `fecha`, `pista` y `duracionMinutos`. ¿Como debe estructurarse `"reservas"` en JSON?**
- A) Como un array de objetos, donde cada objeto tiene las propiedades `fecha`, `pista` y `duracionMinutos`.
- B) Como un objeto con claves `"reserva1"`, `"reserva2"`, `"reserva3"`...
- C) Como un texto unico separado por guiones.
- D) Como un array de booleanos.

**23. Con el siguiente JSON, ¿que ruta devuelve `"Pilates"`? (Los indices empiezan en 0)**
```json
{
  "centro": {
    "monitores": [
      { "nombre": "Álex", "clases": ["Boxeo", "Crossfit"] },
      { "nombre": "Sara", "clases": ["Yoga", "Pilates", "Estiramientos"] }
    ]
  }
}
```
- A) `centro.monitores[2].clases[2]`
- B) `centro.monitores[1].clases[2]`
- C) `centro.monitores[0].clases[1]`
- D) `centro.monitores[1].clases[1]`

**24. En un archivo JSON tienes un array `reservas` cuyos objetos contienen `id`, `socioId` y `salaId`. ¿Como obtendrias las reservas de la sala `"S01"`?**
- A) Consultando unicamente `reservas[1]`.
- B) Recorriendo el array `reservas` y filtrando los objetos cuya propiedad `salaId` sea igual a `"S01"`.
- C) Buscando la reserva cuyo `id` sea `"S01"`.
- D) Mirando el primer socio del array `socios`.

**25. Si en el modelo de datos JSON la propiedad `fidelidad` de un socio puede ser un objeto con `nivel` y `puntos` o bien no existir programa para ese socio, ¿como se representa cuando no tiene programa?**
- A) `"fidelidad": "null"`
- B) `"fidelidad": 0`
- C) `"fidelidad": null`
- D) `"fidelidad": ""`

**26. Al migrar a JSON el elemento XML `<suplemento codigo="SUP1"><precio>24.95</precio><vegano>true</vegano></suplemento>`, ¿que opcion conserva mejor la semantica y los tipos de datos?**
- A) `{ "codigo": "SUP1", "precio": "24.95", "vegano": "true" }`
- B) `{ "codigo": "SUP1", "precio": 24.95, "vegano": true }`
- C) `{ "suplemento": ["SUP1", 24.95, true] }`
- D) `{ codigo="SUP1", precio=24.95, vegano=true }`

**27. ¿Por que marca error el editor en este archivo JSON?**
```json
{
  "salas": [
    { "id": "S01", "nombre": "Sala Fitness", "climatizada": true }
    { "id": "S02", "nombre": "Sala Ciclo", "climatizada": true }
  ]
}
```
- A) Falta la coma `,` al final del primer objeto para separarlo del segundo elemento del array `salas`.
- B) No se puede repetir el valor `true` en dos objetos distintos.
- C) `"S01"` y `"S02"` no pueden llevar letras y numeros a la vez.
- D) Un array JSON no puede llamarse `"salas"`.

---

### Preguntas de respuesta abierta

1. **Explica por que los enlaces del tipo «Pincha aqui» o «Mas info» perjudican la accesibilidad y el SEO de una web,** y escribe un ejemplo de enlace HTML correctamente redactado y seguro que abra una web externa en una nueva pestana.
2. **Explica que diferencia hay entre un XML «bien formado» y un XML «valido».** Pon un ejemplo de modificacion sobre un archivo `club.xml` que lo deje *mal formado* y otro que lo deje *bien formado pero invalido* frente a su XSD.
3. **Representa en XML y en JSON la informacion de una misma sala deportiva** (`id`: `"S01"`, `nombre`: `"Sala Zen"`, `superficieM2`: `85.5`, `aforo`: `25`, `climatizada`: `true`) y senala tres diferencias entre ambos formatos.

---

## PARTE 2: Evaluacion practica de conocimientos (90 min)

### Enunciado — Caso: Centro Deportivo Levante Fit (modelado de datos en JSON)

El **Centro Deportivo Levante Fit** va a actualizar su aplicacion de gestion de salas deportivas, socios y reservas de eventos privados utilizando el formato JSON. Te encargan crear el archivo `gimnasio.json` con todos los datos de las tablas siguientes, estructurando objetos, arrays, anidaciones y tipos de datos de forma coherente.

El archivo tendra un objeto raiz con una unica propiedad `gimnasio` que contendra el resto de la estructura.

#### Informacion del centro deportivo

| Bloque | Datos |
| :--- | :--- |
| **Datos generales** | Nombre: Centro Deportivo Levante Fit · Categoría deportiva: 5 · Centro en activo: sí · Apertura: 07:00 · Cierre: 22:30 |
| **Direccion** | Avenida de las Cortes Valencianas 58, Valencia, código postal 46015 · Coordenadas en el mapa: 39.4891 y -0.4012 |
| **Contacto** | Email: recepcion@levantefit.example · Teléfonos: 963445566 y 963445577 · Web: aún no tiene |
| **Servicios** | vestuarios, sauna, cafetería, fisioterapia |

#### Salas deportivas

| ID | Num. | Nombre | Precio alquiler/dia | Aforo | Disponible | Ubicacion | Valoraciones | Equipamiento |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **S101** | 101 | Sala "Olimpo" | 95,00 EUR | 30 | Sí | Planta 1 · Interior | 5, 4, 5 | Espejos murales, Equipo de sonido, Esterillas |
| **S204** | 204 | Pista Polideportiva | 160,50 EUR | 60 | Sí | Planta 0 · Exterior | 5, 5 | Marcador electrónico, Canastas, Iluminación LED, Gradas |
| **S302** | 302 | Sala Estudio | 45,00 EUR | 12 | No | Planta 2 · Interior | *(ninguna)* | *(ninguno)* |

#### Socios

| ID | Nombre | Fecha nacimiento | Documento | Programa fidelidad | Preferencias |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **SO01** | Rubén Sanchis | 1992-06-15 | DNI 34567890V | Élite · 1500 puntos | horario matinal, taquilla grande |
| **SO02** | Clara Mengual | 2001-10-08 | Pasaporte KB778899 | No tiene programa | *(ninguna)* |
| **SO03** | Viktor Kovalenko | 1986-02-27 | NIE X5432109P | Bronce · 310 puntos | música suave |

#### Reservas de salas (Eventos)

| ID | Socio | Sala | Fechas (Inicio / Fin) | Estado | Pagada | Extras solicitados | Pago y notas |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **RE01** | SO01 | S101 | 12/12/2026 al 14/12/2026 | Confirmada | Sí | Monitor apoyo 30,00 EUR x 2 · Catering saludable 15,50 EUR x 10 | Tarjeta · sala 190,00 · extras 215,00 · impuestos 85,05 · total 490,05 · Nota: Montaje media hora antes |
| **RE02** | SO02 | S204 | 22/12/2026 al 23/12/2026 | Pendiente | No | *(ninguno)* | Sin pago todavía · sin notas |
| **RE03** | SO03 | S101 | 15/01/2027 al 16/01/2027 | Confirmada | Sí | Grabación vídeo 50,00 EUR x 1 | Bizum · sala 95,00 · extras 50,00 · impuestos 30,45 · total 175,45 · Nota: Necesita enchufe junto a la entrada |
| **RE04** | SO01 | S204 | 20/02/2027 al 21/02/2027 | Cancelada | No | *(ninguno)* | Sin pago · Nota: Cancelada por lluvia prevista |

---

### Tareas a realizar

- **Tarea 1. Detecta y corrige errores (10 min):** Corrige el siguiente fragmento en `fragmento_corregido.json` y explica cada error en `respuestas.txt`:
```json
{
  nombre: 'Centro Deportivo Levante Fit',
  "categoriaDeportiva": "5",
  "activo": True,
  "servicios": ["vestuarios", "sauna",],
  "web": "null"
}
```
- **Tarea 2. Estructura base: objetos y tipos (20 min):** En `gimnasio.json`, crea el objeto raiz `gimnasio` con los datos generales, `direccion` y `contacto`. Justifica en `respuestas.txt` los tipos elegidos para `categoriaDeportiva`, `codigoPostal` y `web`.
- **Tarea 3. Salas: arrays de objetos y anidacion (20 min):** Anade el array `salas`. Cada sala tendra `id`, `numero`, `nombre`, `precioDia`, `aforo`, `disponible`, el objeto `ubicacion` (`planta` y `orientacion`), el array `equipamiento` y el array `valoraciones`. Escapa correctamente las comillas en `Sala "Olimpo"`.
- **Tarea 4. Socios y reservas: relaciones y jerarquia profunda (30 min):** Anade los arrays `socios` (con objeto `documento` (`tipo` y `numero`), `fidelidad` (`nivel` y `puntos`, o `null`) y `preferencias`) y `reservas` (relacionadas mediante `socioId` y `salaId`, objeto `fechas` (`inicio` y `fin` en formato `AAAA-MM-DD`), `estado`, booleano `pagada`, array `extras` (`servicio`, `precioUnidad`, `cantidad`), objeto `pago` (`metodo`, `total` y `desglose` con `sala`, `extras`, `impuestos`) o `null`, y `notas` como texto o `null`).
- **Tarea 5. Comprobacion y navegacion (10 min):** En `respuestas.txt`, escribe:
  - **(a)** La ruta completa al importe de `extras` dentro del desglose del pago de la primera reserva, y la ruta a la `cantidad` del segundo extra de esa misma reserva.
  - **(b)** Como averiguarias que reservas corresponden a la sala `S101`.
  - **(c)** Como averiguarias que socios no tienen programa de fidelidad.

---

## PARTE 3: Defensa individual / argumentacion (3-5 min)

Al finalizar las partes 1 y 2 del examen, realiza la entrega (`gimnasio.json`, `fragmento_corregido.json`, `respuestas.txt` y `captura_json.png` comprimidos en `Apellido_Nombre_ModeloD.zip`) y espera a que el profesor te llame para responder a tres preguntas sobre la practica realizada.

---
---

# SOLUCIONARIO COMPLETO — MODELO D

## 1. Solucionario Parte 1: Tipo Test

| Pregunta | Respuesta | Pregunta | Respuesta | Pregunta | Respuesta |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **1** | **C** | **10** | **B** | **19** | **A** |
| **2** | **D** | **11** | **D** | **20** | **C** |
| **3** | **A** | **12** | **B** | **21** | **B** |
| **4** | **B** | **13** | **A** | **22** | **A** |
| **5** | **C** | **14** | **C** | **23** | **D** |
| **6** | **A** | **15** | **D** | **24** | **B** |
| **7** | **D** | **16** | **A** | **25** | **C** |
| **8** | **C** | **17** | **B** | **26** | **B** |
| **9** | **B** | **18** | **C** | **27** | **A** |

---

## 2. Solucionario Parte 1: Preguntas Abiertas

### Pregunta 1
- **Por que «Pincha aqui» o «Mas info» perjudican la accesibilidad y el SEO:** Los usuarios que navegan con lectores de pantalla suelen listar todos los enlaces de una pagina para moverse rapido; si escuchan «Pincha aqui» fuera de contexto, no saben a donde lleva el enlace. Ademas, los buscadores utilizan el texto de anclaje (*anchor text*) para entender de que trata la pagina enlazada.
- **Ejemplo correcto y seguro en nueva pestana:**
```html
<a href="https://www.levantefit.example/horarios" target="_blank" rel="noopener noreferrer">
  Consultar los horarios de actividades dirigidas de Levante Fit
</a>
```

### Pregunta 2
- **Diferencia:** Un documento XML **bien formado** respeta las reglas sintacticas de XML (un unico elemento raiz, etiquetas cerradas y bien anidadas, sensibilidad a mayusculas/minusculas y atributos entre comillas). Un documento **valido** es aquel que, ademas de estar bien formado, cumple con todas las reglas de estructura y tipos especificadas en su esquema XSD.
- **Ejemplo mal formado en `club.xml`:** Poner dos elementos `<club>` en la raiz del documento o abrir `<socio>` y cerrarlo con `</Socio>`.
- **Ejemplo bien formado pero invalido frente a su XSD:** Que el XSD defina un maximo de 5 actividades (`maxOccurs="5"`) y el XML incluya 6 elementos `<actividad>` bien escritos.

### Pregunta 3
- **En XML:**
```xml
<sala id="S01">
  <nombre>Sala Zen</nombre>
  <superficieM2>85.5</superficieM2>
  <aforo>25</aforo>
  <climatizada>true</climatizada>
</sala>
```
- **En JSON:**
```json
{
  "id": "S01",
  "nombre": "Sala Zen",
  "superficieM2": 85.5,
  "aforo": 25,
  "climatizada": true
}
```
- **Tres diferencias:**
  1. XML emplea etiquetas de apertura y cierre (`<nombre>...</nombre>`) y atributos (`id="S01"`), mientras que JSON usa pares `"clave": valor` separados por comas.
  2. JSON representa numeros (`85.5`, `25`) y booleanos (`true`) como tipos primitivos sin comillas, mientras que en XML todo el contenido es texto a menos que se valide con un XSD.
  3. JSON es menos verboso (no repite el nombre de cada campo al cerrar) y se parsea de forma directa en JavaScript y APIs REST.

---

## 3. Solucionario Parte 2: Practica JSON

### Archivo 1: `fragmento_corregido.json` (Tarea 1)
```json
{
  "nombre": "Centro Deportivo Levante Fit",
  "categoriaDeportiva": 5,
  "activo": true,
  "servicios": ["vestuarios", "sauna"],
  "web": null
}
```

### Archivo 2: `respuestas.txt` (Tareas 1, 2 y 5)
```text
=== TAREA 1: ERRORES DETECTADOS ===
1. nombre: 'Centro Deportivo Levante Fit' -> La clave "nombre" carece de comillas dobles obligatorias y su valor está delimitado por comillas simples en lugar de comillas dobles.
2. "categoriaDeportiva": "5" -> Error de tipo de dato: la categoría deportiva (5) es un número entero y no debe ir entre comillas como texto.
3. "activo": True -> Error de sintaxis: en JSON el valor booleano verdadero se escribe en minúsculas (true).
4. "servicios": ["vestuarios", "sauna",] -> Error de sintaxis: existe una coma sobrante después del último elemento del array ("sauna").
5. "web": "null" -> Error de tipo de dato: "null" con comillas es una cadena de texto de 4 letras, cuando debe usarse el literal null sin comillas para indicar que aún no tiene web.

=== TAREA 2: JUSTIFICACION DE TIPOS ===
- categoriaDeportiva (number -> 5): Es un valor numérico entero (equivalente a las estrellas de una instalación) que permite comparaciones numéricas.
- codigoPostal (string -> "46015"): Es un código identificador postal con el que no se realizan operaciones aritméticas y que debe preservar su formato textual.
- web (null -> null): El centro deportivo aún no dispone de sitio web, por lo que se representa la ausencia de valor con null.

=== TAREA 5: COMPROBACION Y NAVEGACION ===
(a) Rutas de acceso:
- Importe de extras del desglose del pago de la primera reserva:
  gimnasio.reservas[0].pago.desglose.extras
- Cantidad del segundo extra de esa misma reserva:
  gimnasio.reservas[0].extras[1].cantidad

(b) Cómo averiguar qué reservas corresponden a la sala S101:
Recorriendo el array gimnasio.reservas y quedándose con los objetos cuya propiedad salaId sea igual a "S101".

(c) Cómo averiguar qué socios no tienen programa de fidelidad:
Recorriendo el array gimnasio.socios y filtrando aquellos objetos donde la propiedad fidelidad sea null.
```

### Archivo 3: `gimnasio.json` (Tareas 2, 3 y 4 completas)
```json
{
  "gimnasio": {
    "nombre": "Centro Deportivo Levante Fit",
    "categoriaDeportiva": 5,
    "activo": true,
    "horario": {
      "apertura": "07:00",
      "cierre": "22:30"
    },
    "direccion": {
      "calle": "Avenida de las Cortes Valencianas 58",
      "ciudad": "Valencia",
      "codigoPostal": "46015",
      "coordenadas": [39.4891, -0.4012]
    },
    "contacto": {
      "email": "recepcion@levantefit.example",
      "telefonos": ["963445566", "963445577"],
      "web": null
    },
    "servicios": [
      "vestuarios",
      "sauna",
      "cafetería",
      "fisioterapia"
    ],
    "salas": [
      {
        "id": "S101",
        "numero": 101,
        "nombre": "Sala \"Olimpo\"",
        "precioDia": 95.0,
        "aforo": 30,
        "disponible": true,
        "ubicacion": {
          "planta": 1,
          "orientacion": "Interior"
        },
        "equipamiento": [
          "Espejos murales",
          "Equipo de sonido",
          "Esterillas"
        ],
        "valoraciones": [5, 4, 5]
      },
      {
        "id": "S204",
        "numero": 204,
        "nombre": "Pista Polideportiva",
        "precioDia": 160.5,
        "aforo": 60,
        "disponible": true,
        "ubicacion": {
          "planta": 0,
          "orientacion": "Exterior"
        },
        "equipamiento": [
          "Marcador electrónico",
          "Canastas",
          "Iluminación LED",
          "Gradas"
        ],
        "valoraciones": [5, 5]
      },
      {
        "id": "S302",
        "numero": 302,
        "nombre": "Sala Estudio",
        "precioDia": 45.0,
        "aforo": 12,
        "disponible": false,
        "ubicacion": {
          "planta": 2,
          "orientacion": "Interior"
        },
        "equipamiento": [],
        "valoraciones": []
      }
    ],
    "socios": [
      {
        "id": "SO01",
        "nombre": "Rubén Sanchis",
        "fechaNacimiento": "1992-06-15",
        "documento": {
          "tipo": "DNI",
          "numero": "34567890V"
        },
        "fidelidad": {
          "nivel": "Élite",
          "puntos": 1500
        },
        "preferencias": ["horario matinal", "taquilla grande"]
      },
      {
        "id": "SO02",
        "nombre": "Clara Mengual",
        "fechaNacimiento": "2001-10-08",
        "documento": {
          "tipo": "Pasaporte",
          "numero": "KB778899"
        },
        "fidelidad": null,
        "preferencias": []
      },
      {
        "id": "SO03",
        "nombre": "Viktor Kovalenko",
        "fechaNacimiento": "1986-02-27",
        "documento": {
          "tipo": "NIE",
          "numero": "X5432109P"
        },
        "fidelidad": {
          "nivel": "Bronce",
          "puntos": 310
        },
        "preferencias": ["música suave"]
      }
    ],
    "reservas": [
      {
        "id": "RE01",
        "socioId": "SO01",
        "salaId": "S101",
        "fechas": {
          "inicio": "2026-12-12",
          "fin": "2026-12-14"
        },
        "estado": "Confirmada",
        "pagada": true,
        "extras": [
          {
            "servicio": "Monitor apoyo",
            "precioUnidad": 30.0,
            "cantidad": 2
          },
          {
            "servicio": "Catering saludable",
            "precioUnidad": 15.5,
            "cantidad": 10
          }
        ],
        "pago": {
          "metodo": "Tarjeta",
          "total": 490.05,
          "desglose": {
            "sala": 190.0,
            "extras": 215.0,
            "impuestos": 85.05
          }
        },
        "notas": "Montaje media hora antes"
      },
      {
        "id": "RE02",
        "socioId": "SO02",
        "salaId": "S204",
        "fechas": {
          "inicio": "2026-12-22",
          "fin": "2026-12-23"
        },
        "estado": "Pendiente",
        "pagada": false,
        "extras": [],
        "pago": null,
        "notas": null
      },
      {
        "id": "RE03",
        "socioId": "SO03",
        "salaId": "S101",
        "fechas": {
          "inicio": "2027-01-15",
          "fin": "2027-01-16"
        },
        "estado": "Confirmada",
        "pagada": true,
        "extras": [
          {
            "servicio": "Grabación vídeo",
            "precioUnidad": 50.0,
            "cantidad": 1
          }
        ],
        "pago": {
          "metodo": "Bizum",
          "total": 175.45,
          "desglose": {
            "sala": 95.0,
            "extras": 50.0,
            "impuestos": 30.45
          }
        },
        "notas": "Necesita enchufe junto a la entrada"
      },
      {
        "id": "RE04",
        "socioId": "SO01",
        "salaId": "S204",
        "fechas": {
          "inicio": "2027-02-20",
          "fin": "2027-02-21"
        },
        "estado": "Cancelada",
        "pagada": false,
        "extras": [],
        "pago": null,
        "notas": "Cancelada por lluvia prevista"
      }
    ]
  }
}
```