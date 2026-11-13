# EXAMEN OFICIAL - 1a EVALUACION (MODELO B)

| CAMPO | DETALLE |
| :--- | :--- |
| **PROGRAMA** | Desarrollo de Aplicaciones Web (DAW) |
| **MODULO** | Lenguajes de marcas |
| **CURSO Y GRUPO** | 1o DAW, GRUPO A |
| **MODELO** | B |

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

**1. En el blog de una tienda hay un `<h1>` «Catalogo 2026», seguido directamente de un `<h3>` «Portatiles gaming» porque al disenador el `<h2>` le parecia demasiado grande. ¿Por que es incorrecto?**
- A) Porque un documento HTML no puede tener etiquetas `<h3>` si no estan dentro de un `<article>`.
- B) Porque rompe la jerarquia logica de encabezados al omitir el nivel `<h2>`, dificultando la navegacion con lectores de pantalla y el indexado SEO.
- C) Porque solo puede usarse un unico encabezado secundario por pagina web.
- D) No es incorrecto: los niveles `<h1>` a `<h6>` sirven exclusivamente para ajustar el tamano de la fuente.

**2. Quieres enlazar a una pasarela de pago externa abriendo una pestana nueva de forma segura. ¿Que codigo es el correcto?**
- A) `<a href="https://pago.example.com" target="_blank" rel="noopener noreferrer">Ir a la pasarela de pago</a>`
- B) `<a href="https://pago.example.com" target="_new">Ir a la pasarela de pago</a>`
- C) `<a href="https://pago.example.com" target="_blank">Ir a la pasarela de pago</a>`
- D) `<a href="https://pago.example.com" rel="external">Ir a la pasarela de pago</a>`

**3. Desde el punto de vista de la accesibilidad web y el posicionamiento SEO, ¿cual de estos enlaces esta mejor redactado?**
- A) `<a href="horario.pdf">Haz clic aqui</a>`
- B) `<a href="horario.pdf">Descargar el horario de clases en PDF</a>`
- C) `<a href="horario.pdf">Ver mas</a>`
- D) `<a href="horario.pdf">archivo.pdf</a>`

**4. En la frase «Atencion: el servidor se apagara hoy y solo tendras cinco minutos para guardar», quieres dar gran importancia a «Atencion» y enfasis de entonacion a «solo» con significado semantico. ¿Que etiquetas debes usar?**
- A) `<b>Atencion</b>` e `<i>solo</i>`
- B) `<em>Atencion</em>` y `<strong>solo</strong>`
- C) `<strong>Atencion</strong>` y `<em>solo</em>`
- D) `<span>Atencion</span>` y `<u>solo</u>`

**5. Al abrir tu pagina web en el navegador, la palabra «Programación» aparece como «ProgramaciÃ³n». ¿Que debes revisar?**
- A) Que la etiqueta `<meta charset="UTF-8">` este incluida en el `<head>` y el archivo este codificado en UTF-8.
- B) Que la etiqueta `<html>` tenga el atributo `dir="ltr"`.
- C) Que el archivo tenga enlazada una hoja de estilos CSS valida.
- D) Que el `<title>` no contenga tildes ni caracteres especiales.

**6. ¿Por que no valida el siguiente fragmento de lista ordenada?**
```html
<ol>
  <li>Instalacion</li>
  <p>Requiere permisos de administrador</p>
  <li>Configuracion</li>
</ol>
```
- A) Porque `<ol>` no admite texto en espanol con tildes.
- B) Porque los unicos hijos directos permitidos dentro de `<ol>` son elementos `<li>` (el `<p>` debe ir dentro del `<li>`).
- C) Porque dentro de una lista `<ol>` es obligatorio usar `<ul>` antes de un parrafo.
- D) Porque una lista ordenada debe tener al menos tres elementos `<li>`.

**7. Una web corporativa tiene: cabecera superior con menu principal, zona central con el contenido unico de la pagina, una barra lateral de enlaces patrocinados y un pie de pagina con el aviso legal. ¿Que estructura semantica es la adecuada?**
- A) `<header>` con `<nav>`; luego `<main>` junto con `<aside>`; y finalmente `<footer>`.
- B) `<top>`, `<center>`, `<sidebar>` y `<bottom>`.
- C) Cuatro etiquetas `<section>` numeradas con `id="1"` a `id="4"`.
- D) Un `<main>` general que envuelva a tres `<header>` y un `<footer>`.

**8. ¿Cual de las siguientes lineas de codigo HTML5 esta bien anidada y cumple las buenas practicas de accesibilidad?**
- A) `<p>Oferta <strong>exclusiva <em>hoy</strong></em></p>`
- B) `<img src="banner.jpg" alt="Descuento del 20% en monitores">`
- C) `<p>Bienvenido a <h1>Mi Tienda</h1></p>`
- D) `<img src="banner.jpg">`

**9. En un cuestionario quieres que el usuario elija un unico turno («Manana» o «Tarde») usando `<input type="radio">`. Actualmente puede seleccionar ambos a la vez y no se desmarca el otro. ¿Como se soluciona?**
- A) Poniendo el mismo valor en el atributo `id` de ambos `<input>`.
- B) Cambiando el tipo a `<input type="checkbox">`.
- C) Asignando exactamente el mismo valor en el atributo `name` de ambos `<input>` (por ejemplo, `name="turno"`).
- D) Anadiendo el atributo `checked` a los dos elementos.

**10. ¿Cual de estos fragmentos corresponde a un documento XML bien formado?**
- A) `<?xml version="1.0"?><libro><titulo>XML practico</Titulo></libro>`
- B) `<?xml version="1.0"?><libro id=1><titulo>XML practico</titulo></libro>`
- C) `<?xml version="1.0"?><libro id="1"><titulo>XML practico</titulo><autor>Ana Gil</autor></libro>`
- D) `<?xml version="1.0"?><libro><titulo>XML practico</libro></titulo>`

**11. En un esquema XSD se define `<xs:element name="precio" type="xs:decimal"/>`. En el archivo XML se escribe `<PRECIO>15.50</PRECIO>`. ¿Que afirmacion es cierta?**
- A) El XML esta bien formado, pero es invalido respecto al XSD porque XML/XSD distingue entre mayusculas y minusculas.
- B) El XML esta mal formado porque las etiquetas XML no pueden escribirse en mayusculas.
- C) El XML es valido y bien formado, ya que `PRECIO` y `precio` representan la misma palabra.
- D) El XML es invalido porque `15.50` lleva punto en lugar de coma.

**12. En `academia.xml` tienes una lista de `profesores` (con DNI, nombre, email y telefono) y una lista de `cursos`. Un mismo profesor imparte varios cursos. ¿Como debes relacionarlos para evitar redundancia?**
- A) Copiando el nombre, email y telefono del profesor dentro de cada curso que imparta.
- B) Asignando un atributo identificador unico (ej. `id="P01"`) a cada profesor y referenciandolo desde cada curso (ej. `profesorId="P01"`).
- C) Creando un archivo XML distinto por cada curso y duplicando alli la ficha del profesor.
- D) Guardando todos los cursos como texto separado por comas dentro del elemento `<nombre>` del profesor.

**13. Dos bancos necesitan intercambiar ficheros diarios con movimientos de cuentas bancarias para procesarlos automaticamente. ¿Por que elegirian XML en lugar de HTML?**
- A) Porque XML carga mas rapido las imagenes y estilos visuales en el navegador del banco.
- B) Porque HTML no puede enviarse a traves de Internet entre servidores.
- C) Porque XML permite estructurar y describir el significado de los datos mediante etiquetas propias y validables.
- D) Porque XML corrige automaticamente los importes bancarios erroneos.

**14. Dado el siguiente fragmento XSD, ¿que ocurre si en el XML escribimos `<alumno><edad>20</edad><nombre>Luis</nombre></alumno>`?**
```xml
<xs:element name="alumno">
  <xs:complexType>
    <xs:sequence>
      <xs:element name="nombre" type="xs:string"/>
      <xs:element name="edad" type="xs:integer"/>
    </xs:sequence>
  </xs:complexType>
</xs:element>
```
- A) Es valido: ambos elementos existen y sus tipos son correctos.
- B) Esta mal formado porque `<edad>` nunca puede ir antes que `<nombre>`.
- C) Es invalido: el indicador `<xs:sequence>` obliga a que `<nombre>` aparezca antes que `<edad>`.
- D) Es invalido porque `20` deberia ir entre comillas dentro de `<edad>`.

**15. En un XSD, el elemento `<telefono>` tiene `minOccurs="1"` y `maxOccurs="2"`. Un cliente en el XML no tiene ningun elemento `<telefono>`. ¿Cual es el diagnostico?**
- A) El XML sigue estando bien formado, pero es invalido porque incumple el minimo de ocurrencias (`minOccurs="1"`).
- B) El XML esta mal formado porque falta una etiqueta obligatoria.
- C) El XML es valido porque `minOccurs` es solo una recomendacion.
- D) El XML es valido siempre que el cliente tenga correo electronico.

**16. En un XSD se define `<xs:attribute name="moneda" type="xs:string" use="optional"/>` dentro del elemento `importe`. Si en el XML escribimos `<importe>100</importe>` sin el atributo `moneda`, ¿que sucede?**
- A) Es invalido porque todos los atributos declarados en XSD son obligatorios.
- B) Esta mal formado porque `<importe>` no tiene atributos.
- C) Es tanto bien formado como valido, ya que `use="optional"` permite omitir el atributo.
- D) El validador anade automaticamente `moneda="EUR"` al archivo XML.

**17. Un documento `biblioteca.xml` contiene 3 elementos `<seccion>` (cada uno con un hijo `<titulo>`) y dentro de las secciones hay en total 8 elementos `<libro>` (cada uno con su propio hijo `<titulo>`). ¿Cuantos nodos devuelve la expresion XPath `//titulo`?**
- A) 3 nodos (solo los de las secciones).
- B) 8 nodos (solo los de los libros).
- C) 11 nodos (los 3 titulos de seccion mas los 8 titulos de libro).
- D) 1 nodo (unicamente el primer `<titulo>` del documento).

**18. Dada la estructura `/catalogo/categoria[@codigo='INF']/producto[marca='Logitech']/precio`, ¿que selecciona exactamente esta expresion XPath?**
- A) El precio de los productos cuyo atributo `marca` sea `Logitech` dentro de la categoria con hijo `<codigo>INF</codigo>`.
- B) El precio de los productos que tienen un elemento hijo `<marca>` con valor `'Logitech'`, dentro de la categoria cuyo atributo `codigo` vale `'INF'`.
- C) Todos los productos de la categoria `'INF'` aunque no tengan precio.
- D) El atributo `precio` del elemento `Logitech`.

**19. En un esquema XSD quieres validar que `<fechaAlta>` tenga formato de fecha estandar (AAAA-MM-DD) y `<pagado>` solo acepte `true` o `false`. ¿Que tipos debes usar?**
- A) `type="xs:string"` para ambos.
- B) `type="xs:date"` y `type="xs:boolean"`.
- C) `type="xs:calendar"` y `type="xs:bit"`.
- D) `type="xs:integer"` y `type="xs:string"`.

**20. ¿Cual de los siguientes objetos JSON es sintacticamente valido?**
- A) `{ "codigo": "A12", "disponible": false, "tags": ["oferta", "nuevo"] }`
- B) `{ 'codigo': 'A12', 'disponible': false, 'tags': ['oferta', 'nuevo'] }`
- C) `{ "codigo": "A12", "disponible": False, "tags": ["oferta", "nuevo"] }`
- D) `{ codigo: "A12", "disponible": false, "tags": ["oferta", "nuevo"], }`

**21. En un fichero JSON se guarda `"stock": "0"` en lugar de `"stock": 0`. ¿Que afirmacion es correcta?**
- A) Es un error de sintaxis JSON y VS Code subrayara la linea en rojo.
- B) Es sintacticamente valido, pero el tipo de dato es una cadena de texto (`string`) en lugar de un numero (`number`).
- C) Representa lo mismo que `"stock": null`.
- D) JSON transforma automaticamente `"0"` en el booleano `false`.

**22. Un curso tiene varios modulos, y de cada modulo interesa guardar su `codigo`, `nombre` y `horas`. ¿Cual es la mejor estructura en JSON para la propiedad `"modulos"`?**
- A) Un array de objetos: `"modulos": [ { "codigo": "LM", "nombre": "Lenguajes de marcas", "horas": 96 }, ... ]`
- B) Un texto largo: `"modulos": "LM - Lenguajes de marcas - 96, BD - Bases de datos - 160"`
- C) Un objeto con claves repetidas: `"modulos": { "modulo": "LM", "modulo": "BD" }`
- D) Tres arrays sueltos sin relacion clara en la raiz del documento.

**23. A partir de este JSON, ¿que ruta devuelve `"València"`? (Recuerda que los arrays empiezan en el indice 0)**
```json
{
  "empresa": {
    "sedes": [
      { "ciudad": "Madrid", "oficinas": ["Centro", "Norte"] },
      { "ciudad": "València", "oficinas": ["Puerto", "Ruzafa"] }
    ]
  }
}
```
- A) `empresa.sedes[2].ciudad`
- B) `empresa.sedes[1].ciudad`
- C) `empresa.sedes[0].ciudad`
- D) `empresa.sedes.ciudad[1]`

**24. En un JSON de una tienda tienes un array `pedidos`, donde cada objeto tiene `id`, `clienteId` y `total`. ¿Como obtendrias todos los pedidos realizados por el cliente con `id` `"C05"`?**
- A) Accediendo directamente a `pedidos["C05"]`.
- B) Buscando el pedido que esta en la posicion 5 del array (`pedidos[5]`).
- C) Recorriendo el array `pedidos` y filtrando aquellos objetos cuya propiedad `clienteId` sea igual a `"C05"`.
- D) Buscando los pedidos cuyo atributo `id` del pedido sea `"C05"`.

**25. Si un empleado aun no tiene fecha de baja en la empresa, ¿cual es la forma correcta de representar la ausencia de valor en la propiedad `fechaBaja` en JSON?**
- A) `"fechaBaja": null`
- B) `"fechaBaja": "null"`
- C) `"fechaBaja": undefined`
- D) `"fechaBaja": None`

**26. Quieres pasar a JSON el XML `<aula codigo="A102"><capacidad>30</capacidad><proyector>true</proyector></aula>` manteniendo los tipos de datos mas precisos. ¿Cual es la mejor opcion?**
- A) `{ "codigo": "A102", "capacidad": "30", "proyector": "true" }`
- B) `{ "codigo": "A102", "capacidad": 30, "proyector": true }`
- C) `{ "aula": [ "A102", "30", "true" ] }`
- D) `{ "codigo": 102, "capacidad": 30, "proyector": 1 }`

**27. ¿Por que da error de validacion sintactica este JSON?**
```json
{
  "categorias": [
    "Teclados",
    "Ratones",
    "Monitores",
  ]
}
```
- A) Porque los arrays en JSON solo pueden contener objetos, no textos.
- B) Porque sobra la coma final detras de `"Monitores"` (JSON no permite *trailing commas*).
- C) Porque las palabras del array empiezan por mayuscula.
- D) Porque falta el atributo `id` dentro del array.

---

### Preguntas de respuesta abierta

1. **Un companero utiliza la etiqueta `<b>` para todos los textos importantes de una web y varios `<br><br><br>` seguidos para dejar espacio entre bloques.** Explica por que ambas decisiones son malas practicas en HTML5 y que etiquetas o tecnologias deberia emplear en su lugar.
2. **Explica la diferencia entre un documento XML «bien formado» y uno «valido».** A partir de un archivo `biblioteca.xml`, escribe un ejemplo concreto de error que lo convierta en *mal formado* y otro que lo deje *bien formado pero invalido* frente a su esquema XSD.
3. **Representa tanto en XML como en JSON la ficha de un mismo curso** (`codigo`: `"DAW1"`, `titulo`: `"Lenguajes de Marcas"`, `horas`: `96`, `cuotaMensual`: `120.50`, `online`: `false`) y explica tres diferencias clave entre ambos formatos.

---

## PARTE 2: Evaluacion practica de conocimientos (90 min)

### Enunciado — Caso: Clinica Veterinaria Turia (modelado de datos en JSON)

La **Clinica Veterinaria Turia** va a migrar el registro de sus gabinetes, clientes y consultas a una nueva plataforma web que trabaja con formato JSON. Debes construir el archivo `clinica.json` con todos los datos de las tablas siguientes, aplicando una estructura jerarquica limpia con objetos, arrays, anidaciones y los tipos de datos correctos.

El archivo tendra un objeto raiz con una unica propiedad `clinica` que contendra toda la informacion.

#### Informacion de la clinica

| Bloque | Datos |
| :--- | :--- |
| **Datos generales** | Nombre: Clínica Veterinaria Turia · Urgencias 24h: sí · Número de colegiado centro: 46089 · Apertura: 09:00 · Cierre: 20:30 |
| **Direccion** | Calle Colón 45, Valencia, código postal 46004 · Coordenadas en el mapa: 39.4682 y -0.3719 |
| **Contacto** | Email: info@vetturia.example · Teléfonos: 963001122 y 600112233 · Web: aún no tiene |
| **Especialidades** | cirugía, dermatología, exóticos, diagnóstico por imagen |

#### Gabinetes (Salas de consulta)

| ID | Num. | Nombre | Tarifa base | Capacidad animales | Operativo | Ubicacion | Valoraciones | Equipamiento |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **G01** | 1 | Consulta general | 35,00 EUR | 2 | Sí | Planta 0 · Exterior | 5, 4, 5 | Báscula digital, Otoscopio, Lector microchip |
| **G02** | 2 | Quirófano "Turia" | 120,50 EUR | 1 | Sí | Planta 1 · Interior | 5, 5 | Monitor multiparamétrico, Bisturí eléctrico, Oxígeno |
| **G03** | 3 | Sala de rayos X | 65,00 EUR | 1 | No | Planta -1 · Interior | *(ninguna)* | *(ninguno)* |

#### Clientes (Propietarios)

| ID | Nombre | Fecha alta | Documento | Seguro mascota | Alertas administrativas |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **P001** | Carlos Valor | 2023-05-14 | DNI 23456789M | VetPlus · Póliza 99812 | avisar por SMS, factura detallada |
| **P002** | Elena Bosch | 2024-11-02 | NIE X8765432T | No tiene seguro | *(ninguna)* |
| **P003** | Jorge Marín | 2025-02-19 | Pasaporte PA445566 | MascotaSegura · Póliza 10455 | perro nervioso en sala de espera |

#### Consultas medicas

| ID | Cliente | Gabinete | Fechas (Ingreso / Alta) | Estado | Pagada | Tratamientos extra | Pago y notas |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **M001** | P001 | G01 | 02/11/2026 al 02/11/2026 | Finalizada | Sí | Vacuna rabia 25,00 EUR x 1 · Desparasitación 12,50 EUR x 2 | Tarjeta · gabinete 35,00 · extras 50,00 · impuestos 17,85 · total 102,85 · Nota: Revisar peso en 6 meses |
| **M002** | P002 | G02 | 15/11/2026 al 16/11/2026 | Programada | No | *(ninguno)* | Sin pago todavía · sin notas |
| **M003** | P003 | G01 | 20/11/2026 al 20/11/2026 | Finalizada | Sí | Analítica completa 45,00 EUR x 1 | Efectivo · gabinete 35,00 · extras 45,00 · impuestos 16,80 · total 96,80 · Nota: Ayuno de 12 horas cumplido |
| **M004** | P001 | G02 | 01/12/2026 al 02/12/2026 | Cancelada | No | *(ninguno)* | Sin pago · Nota: Cancelada por mejoría del animal |

---

### Tareas a realizar

- **Tarea 1. Detecta y corrige errores (10 min):** El siguiente fragmento contiene varios errores de sintaxis y de tipo de dato. Guardalo como `fragmento_corregido.json` ya corregido y, en `respuestas.txt`, anota cada error encontrado y por que lo es:
```json
{
  nombre: 'Clínica Veterinaria Turia',
  "colegiadoCentro": "46089",
  "urgencias24h": True,
  "especialidades": ["cirugía", "exóticos",],
  "web": "null"
}
```
- **Tarea 2. Estructura base: objetos y tipos (20 min):** En `clinica.json` crea el objeto raiz y, dentro de `clinica`, los datos generales, la `direccion` y el `contacto`:
  - Usa el tipo de dato adecuado en cada valor (texto, numero, booleano, null) y justificalo en `respuestas.txt` para `colegiadoCentro`, `codigoPostal` y `web`.
  - `direccion` y `contacto` son objetos anidados.
  - `especialidades` y `telefonos` son arrays de textos; `coordenadas` es un array de numeros.
- **Tarea 3. Gabinetes: arrays de objetos y anidacion (20 min):** Anade la propiedad `gabinetes` como array de objetos. Cada gabinete tiene `id`, `numero`, `nombre`, `tarifaBase`, `capacidad`, `operativo` y:
  - un objeto anidado `ubicacion` con `planta` y `zona`;
  - un array `equipamiento` de textos (vacio cuando no hay);
  - un array `valoraciones` de numeros (vacio cuando no hay).
  - Cuida los caracteres especiales del nombre del quirofano y escribe los decimales correctamente.
- **Tarea 4. Clientes y consultas: relaciones y jerarquia profunda (30 min):** Anade `clientes` y `consultas` como arrays de objetos:
  - Cada cliente incluye un objeto `documento` (`tipo` y `numero`), un valor `seguro` (objeto con `compania` y `poliza`, o `null` si no tiene seguro) y un array `alertas`.
  - Cada consulta se relaciona con su cliente y su gabinete mediante identificadores (`clienteId`, `gabineteId`), sin copiar sus datos.
  - Cada consulta contiene un objeto `fechas` (`ingreso` y `alta`), el `estado`, un booleano `pagada` y un array `extras` de objetos (`concepto`, `precioUnidad` y `cantidad`).
  - Cada consulta contiene un objeto `pago` (o `null` si no hay pago) con `metodo`, `total` y un objeto anidado `desglose` (`gabinete`, `extras` e `impuestos`), y una propiedad `notas` (texto o `null`).
  - Escribe las fechas como texto en formato `AAAA-MM-DD`.
- **Tarea 5. Comprobacion y navegacion (10 min):** Da formato al archivo con VS Code y comprueba que no muestra errores en el panel de problemas. Despues, en `respuestas.txt`, escribe:
  - **(a)** la ruta completa para acceder al importe de `impuestos` del desglose del pago de la primera consulta, y la ruta al `precioUnidad` del segundo extra de esa misma consulta;
  - **(b)** como averiguarias que consultas pertenecen al gabinete `G01`;
  - **(c)** como averiguarias que clientes no tienen seguro contratado.

---

## PARTE 3: Defensa individual / argumentacion (3-5 min)

Al finalizar las partes 1 y 2 del examen, realiza la entrega (`clinica.json`, `fragmento_corregido.json`, `respuestas.txt` y `captura_json.png` comprimidos en `Apellido_Nombre_ModeloB.zip`) y espera a que el profesor te llame para responder a tres preguntas sobre la practica realizada.

---
---

# SOLUCIONARIO COMPLETO — MODELO B

## 1. Solucionario Parte 1: Tipo Test

| Pregunta | Respuesta | Pregunta | Respuesta | Pregunta | Respuesta |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **1** | **B** | **10** | **C** | **19** | **B** |
| **2** | **A** | **11** | **A** | **20** | **A** |
| **3** | **B** | **12** | **B** | **21** | **B** |
| **4** | **C** | **13** | **C** | **22** | **A** |
| **5** | **A** | **14** | **C** | **23** | **B** |
| **6** | **B** | **15** | **A** | **24** | **C** |
| **7** | **A** | **16** | **C** | **25** | **A** |
| **8** | **B** | **17** | **C** | **26** | **B** |
| **9** | **C** | **18** | **B** | **27** | **B** |

---

## 2. Solucionario Parte 1: Preguntas Abiertas

### Pregunta 1
- **Por que `<b>` es mala practica para textos importantes:** La etiqueta `<b>` solo aplica estilo visual (negrita) sin aportar significado semantico de relevancia. Para indicar que un texto es importante para lectores de pantalla y buscadores se debe utilizar `<strong>`.
- **Por que `<br><br><br>` es mala practica para espaciar bloques:** `<br>` representa un salto de linea puntual dentro de un mismo bloque de texto (como una direccion o un poema), no una herramienta de maquetacion. Para separar bloques se deben usar etiquetas semanticas de bloque (`<p>`, `<section>`, `<div>`) y controlar los margenes mediante **CSS** (`margin` o `padding`).

### Pregunta 2
- **Diferencia:** Un documento XML **bien formado** cumple las reglas basicas de sintaxis de XML (una sola raiz, etiquetas bien cerradas y anidadas, atributos entre comillas, sensibilidad a mayusculas/minusculas). Un documento XML **valido**, ademas de estar bien formado, cumple todas las reglas de estructura, orden, cardinalidad y tipos de datos definidas en un esquema (como un XSD).
- **Ejemplo mal formado en `biblioteca.xml`:** Abrir `<libro>` y cerrarlo como `</Libro>` (con mayuscula) o cruzar etiquetas como `<libro><titulo>Quijote</libro></titulo>`.
- **Ejemplo bien formado pero invalido frente a su XSD:** Que el XSD declare `<xs:element name="paginas" type="xs:integer"/>` y en el XML se escriba `<paginas>trescientas</paginas>` (sintaxis XML correcta, pero incumple el tipo entero del XSD).

### Pregunta 3
- **En XML:**
```xml
<curso codigo="DAW1">
  <titulo>Lenguajes de Marcas</titulo>
  <horas>96</horas>
  <cuotaMensual>120.50</cuotaMensual>
  <online>false</online>
</curso>
```
- **En JSON:**
```json
{
  "codigo": "DAW1",
  "titulo": "Lenguajes de Marcas",
  "horas": 96,
  "cuotaMensual": 120.50,
  "online": false
}
```
- **Tres diferencias clave:**
  1. **Sintaxis:** XML utiliza etiquetas de apertura y cierre (`<etiqueta>...</etiqueta>`) y atributos, mientras que JSON utiliza pares `"clave": valor` dentro de llaves `{}`.
  2. **Tipos de datos nativos:** JSON distingue nativamente numeros (`96`, `120.50`), booleanos (`false`) y `null` sin comillas; en XML todo contenido es texto plano a menos que se asocie un esquema XSD.
  3. **Verbosidad:** XML es mas verboso al repetir el nombre de cada etiqueta al abrir y cerrar; JSON es mas compacto y ligero para el transporte en APIs web.

---

## 3. Solucionario Parte 2: Practica JSON

### Archivo 1: `fragmento_corregido.json` (Tarea 1)
```json
{
  "nombre": "Clínica Veterinaria Turia",
  "colegiadoCentro": 46089,
  "urgencias24h": true,
  "especialidades": ["cirugía", "exóticos"],
  "web": null
}
```

### Archivo 2: `respuestas.txt` (Tareas 1, 2 y 5)
```text
=== TAREA 1: ERRORES DETECTADOS ===
1. nombre: 'Clínica Veterinaria Turia' -> La clave "nombre" no lleva comillas dobles obligatorias y el valor usa comillas simples (' ') en lugar de comillas dobles (" ").
2. "colegiadoCentro": "46089" -> Error de tipo de dato: el número de colegiado del centro es un valor numérico entero (46089) o identificador numérico, no debe ir como cadena si se representa como número en la ficha.
3. "urgencias24h": True -> Error de sintaxis: en JSON los booleanos se escriben en minúsculas (true / false), no con mayúscula inicial como en Python.
4. "especialidades": ["cirugía", "exóticos",] -> Error de sintaxis: hay una coma final sobrante (trailing comma) después del último elemento del array ("exóticos").
5. "web": "null" -> Error de tipo de dato: al poner "null" entre comillas se guarda el texto literal "null" en lugar del valor especial null que indica ausencia de página web.

=== TAREA 2: JUSTIFICACION DE TIPOS ===
- colegiadoCentro (number -> 46089): Es un valor numérico entero sin ceros a la izquierda ni caracteres alfanuméricos.
- codigoPostal (string -> "46004"): Aunque contiene dígitos, es un código identificador geográfico con formato fijo de 5 caracteres (en algunas provincias empieza por 0, como "03001", que se perdería si fuera number) y no se realizan operaciones matemáticas con él.
- web (null -> null): La clínica aún no tiene página web, por lo que el valor adecuado para representar la ausencia de dato es el literal null (sin comillas).

=== TAREA 5: COMPROBACION Y NAVEGACION ===
(a) Rutas de acceso:
- Importe de impuestos del desglose de la primera consulta:
  clinica.consultas[0].pago.desglose.impuestos
- Precio por unidad del segundo extra de la primera consulta:
  clinica.consultas[0].extras[1].precioUnidad

(b) Cómo averiguar qué consultas pertenecen al gabinete G01:
Recorriendo el array clinica.consultas y filtrando aquellos objetos cuya propiedad gabineteId sea exactamente igual a "G01".

(c) Cómo averiguar qué clientes no tienen seguro contratado:
Recorriendo el array clinica.clientes y comprobando qué objetos tienen la propiedad seguro con valor igual a null.
```

### Archivo 3: `clinica.json` (Tareas 2, 3 y 4 completas)
```json
{
  "clinica": {
    "nombre": "Clínica Veterinaria Turia",
    "urgencias24h": true,
    "colegiadoCentro": 46089,
    "horario": {
      "apertura": "09:00",
      "cierre": "20:30"
    },
    "direccion": {
      "calle": "Calle Colón 45",
      "ciudad": "Valencia",
      "codigoPostal": "46004",
      "coordenadas": [39.4682, -0.3719]
    },
    "contacto": {
      "email": "info@vetturia.example",
      "telefonos": ["963001122", "600112233"],
      "web": null
    },
    "especialidades": [
      "cirugía",
      "dermatología",
      "exóticos",
      "diagnóstico por imagen"
    ],
    "gabinetes": [
      {
        "id": "G01",
        "numero": 1,
        "nombre": "Consulta general",
        "tarifaBase": 35.0,
        "capacidad": 2,
        "operativo": true,
        "ubicacion": {
          "planta": 0,
          "zona": "Exterior"
        },
        "equipamiento": [
          "Báscula digital",
          "Otoscopio",
          "Lector microchip"
        ],
        "valoraciones": [5, 4, 5]
      },
      {
        "id": "G02",
        "numero": 2,
        "nombre": "Quirófano \"Turia\"",
        "tarifaBase": 120.5,
        "capacidad": 1,
        "operativo": true,
        "ubicacion": {
          "planta": 1,
          "zona": "Interior"
        },
        "equipamiento": [
          "Monitor multiparamétrico",
          "Bisturí eléctrico",
          "Oxígeno"
        ],
        "valoraciones": [5, 5]
      },
      {
        "id": "G03",
        "numero": 3,
        "nombre": "Sala de rayos X",
        "tarifaBase": 65.0,
        "capacidad": 1,
        "operativo": false,
        "ubicacion": {
          "planta": -1,
          "zona": "Interior"
        },
        "equipamiento": [],
        "valoraciones": []
      }
    ],
    "clientes": [
      {
        "id": "P001",
        "nombre": "Carlos Valor",
        "fechaAlta": "2023-05-14",
        "documento": {
          "tipo": "DNI",
          "numero": "23456789M"
        },
        "seguro": {
          "compania": "VetPlus",
          "poliza": 99812
        },
        "alertas": ["avisar por SMS", "factura detallada"]
      },
      {
        "id": "P002",
        "nombre": "Elena Bosch",
        "fechaAlta": "2024-11-02",
        "documento": {
          "tipo": "NIE",
          "numero": "X8765432T"
        },
        "seguro": null,
        "alertas": []
      },
      {
        "id": "P003",
        "nombre": "Jorge Marín",
        "fechaAlta": "2025-02-19",
        "documento": {
          "tipo": "Pasaporte",
          "numero": "PA445566"
        },
        "seguro": {
          "compania": "MascotaSegura",
          "poliza": 10455
        },
        "alertas": ["perro nervioso en sala de espera"]
      }
    ],
    "consultas": [
      {
        "id": "M001",
        "clienteId": "P001",
        "gabineteId": "G01",
        "fechas": {
          "ingreso": "2026-11-02",
          "alta": "2026-11-02"
        },
        "estado": "Finalizada",
        "pagada": true,
        "extras": [
          {
            "concepto": "Vacuna rabia",
            "precioUnidad": 25.0,
            "cantidad": 1
          },
          {
            "concepto": "Desparasitación",
            "precioUnidad": 12.5,
            "cantidad": 2
          }
        ],
        "pago": {
          "metodo": "Tarjeta",
          "total": 102.85,
          "desglose": {
            "gabinete": 35.0,
            "extras": 50.0,
            "impuestos": 17.85
          }
        },
        "notas": "Revisar peso en 6 meses"
      },
      {
        "id": "M002",
        "clienteId": "P002",
        "gabineteId": "G02",
        "fechas": {
          "ingreso": "2026-11-15",
          "alta": "2026-11-16"
        },
        "estado": "Programada",
        "pagada": false,
        "extras": [],
        "pago": null,
        "notas": null
      },
      {
        "id": "M003",
        "clienteId": "P003",
        "gabineteId": "G01",
        "fechas": {
          "ingreso": "2026-11-20",
          "alta": "2026-11-20"
        },
        "estado": "Finalizada",
        "pagada": true,
        "extras": [
          {
            "concepto": "Analítica completa",
            "precioUnidad": 45.0,
            "cantidad": 1
          }
        ],
        "pago": {
          "metodo": "Efectivo",
          "total": 96.8,
          "desglose": {
            "gabinete": 35.0,
            "extras": 45.0,
            "impuestos": 16.8
          }
        },
        "notas": "Ayuno de 12 horas cumplido"
      },
      {
        "id": "M004",
        "clienteId": "P001",
        "gabineteId": "G02",
        "fechas": {
          "ingreso": "2026-12-01",
          "alta": "2026-12-02"
        },
        "estado": "Cancelada",
        "pagada": false,
        "extras": [],
        "pago": null,
        "notas": "Cancelada por mejoría del animal"
      }
    ]
  }
}
```