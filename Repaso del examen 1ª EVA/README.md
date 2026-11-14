# 📚 Preparación del Examen — 1.ª Evaluación

![Módulo](https://img.shields.io/badge/M%C3%B3dulo-Lenguajes_de_Marcas-185b83?style=flat-square)
![Curso](https://img.shields.io/badge/Curso-1.%C2%BA_DAW-0f766e?style=flat-square)
![Contenidos](https://img.shields.io/badge/Temario-HTML5_%7C_XML_%7C_XSD_%7C_XPath_%7C_JSON-6d28d9?style=flat-square)
![Modelos](https://img.shields.io/badge/Simulacros-4_Modelos_Progresivos_(A--D)-c2410c?style=flat-square)

Apartado de repaso y simulacros dentro del repositorio de **Lenguajes de marcas y sistemas de gestión de información** para preparar el examen oficial de la primera evaluación.

> [!IMPORTANT]
> **¿Quieres empezar un simulacro?** Baja a **Simulacros Disponibles** y haz clic en **🎮 Test Interactivo** junto al modelo que quieras practicar. Se abrirá el examen interactivo completo (Parte 1 + Parte 2 con validador JSON en vivo).

> [!NOTE]
> **100% ajustado a lo estudiado en clase:** El **Modelo A** es el examen tipo inicial proporcionado por el profesor para medir el nivel. Los **Modelos B, C y D** mantienen exactamente las mismas 3 partes y rúbrica oficial, pero contienen **81 preguntas tipo test nuevas, 9 preguntas abiertas nuevas y 3 casos prácticos de JSON con estructuras distintas**, centrados exclusivamente en los bloques impartidos en el aula (`HTML5`, `XML`, `XSD`, `XPath` y `JSON` práctico en VS Code).

---

## ⏱️ Estructura y Rúbrica del Examen

| Bloque | Duración | Peso | Formato y condiciones |
| :--- | :---: | :---: | :--- |
| 🧠 **Parte 1: Teoría** | `30 min` | **30%** | **27 preguntas tipo test** (cada 3 errores descuentan 1 acierto) + **3 preguntas abiertas**. Sin apuntes ni dispositivos. |
| 💻 **Parte 2: Práctica** | `90 min` | **50%** | **Modelado completo en JSON** dividido en 5 tareas progresivas en Visual Studio Code. |
| 🗣️ **Parte 3: Defensa** | `3-5 min` | **20%** | **Explicación y justificación oral** individual sin ayuda de pantallas ni IA. |

---

## 🚀 Simulacros Disponibles en esta Carpeta

Cada modelo incluye su **aplicación web interactiva**, con temporizador de 30 minutos, mapa de preguntas, autocorrección con penalización oficial, preguntas abiertas con solución desplegable, modo oscuro y laboratorio/validador JSON en vivo:

| Modelo | Nivel | Caso Práctico (Parte 2 - JSON) | Contenidos Evaluados (Parte 1 y Parte 2) | Acceso Directo |
| :---: | :---: | :--- | :--- | :---: |
| ![Modelo A](https://img.shields.io/badge/MODELO_A-185b83?style=for-the-badge) | 🟢 **Examen Tipo (Base)** | 🏨 **Hotel Costa Valencia** (`hotel.json`) | 👨‍🏫 **Oficial de clase:** Jerarquía `<h1>`–`<h6>`, `target="_blank"`, `<strong>`/`<em>`, listas, `gimnasio.xml`, predicados XPath y modelado de hotel. | [🎮 **Test Interactivo**](./modelo_a_interactivo.html) |
| ![Modelo B](https://img.shields.io/badge/MODELO_B-0f766e?style=for-the-badge) | 🟡 **Intermedio** | 🛒 **Tienda Online Digitech** (`tienda_online.json`) | 📖 **HTML5, XML/XSD, XPath y Tienda JSON:** DOM/HTTP, `mailto:`/`tel:`/`download`, `<dl>`, tablas con `<caption>`/`scope`/`rowspan`, `<figure>`, `<details>`, `pattern`, XSD `minOccurs`/`maxOccurs`, comodín XPath `*`, `text()`, y modelado completo de tienda online (productos, clientes y pedidos). | [🎮 **Test Interactivo**](./modelo_b_interactivo.html) |
| ![Modelo C](https://img.shields.io/badge/MODELO_C-6d28d9?style=for-the-badge) | 🟠 **Intermedio-Alto** | 🏋️ **Gimnasio Olympia (XML → JSON)** (`gimnasio_rutinas.json`) | 📖 **Profundización en los 4 bloques:** `<kbd>`, `<abbr>`, `<blockquote>`, `<ol reversed type="a">`, `<picture>` y `loading="lazy"`, `<time>`, `<datalist>`, `<progress>`, SEO Open Graph/canonical, ARIA (`role="alert"`, `aria-describedby`), `xs:complexType`/`xs:sequence`/`xs:attribute` y comparativa directa **XPath vs rutas JSON**. | [🎮 **Test Interactivo**](./modelo_c_interactivo.html) |
| ![Modelo D](https://img.shields.io/badge/MODELO_D-c2410c?style=for-the-badge) | 🔴 **Difícil / Avanzado** | 🩺 **Clínica Médica Turia Salud** (`clinica_medica.json`) | 📖 **Dominio completo y casos límite:** Rutas CSS/JS (`defer`), cálculo de columnas con `rowspan`/`colspan`, formatos `SVG`/`PNG`/`WebP` (`srcset`), `<fieldset>`/`<legend>`, `readonly`, `autofocus`, `novalidate`, `aria-expanded`, W3C Validator y modelado de historial clínico de 4 niveles. | [🎮 **Test Interactivo**](./modelo_d_interactivo.html) |

---

## 🧭 Cómo aprovechar estos materiales

> [!TIP]
> **No memorices respuestas: comprende el porqué de cada bloque.** Como cada modelo plantea preguntas distintas sobre los mismos temas de clase, completar los 4 modelos (A, B, C y D) te garantiza haber practicado **todos los apartados teóricos y prácticos** que pueden salir en el examen real.

1. 🎯 **Haz primero el Modelo A** para conocer el punto de partida que entregó el profesor en clase.
2. 📈 **Avanza por orden de dificultad (B → C → D):** Cada modelo recorre apartados de los PDFs que no salían en el Modelo A (tablas, multimedia, formularios HTML5, SEO, ARIA, esquemas XSD, rutas XPath y modelado JSON).
3. 💻 **Practica las 4 estructuras JSON distintas en VS Code:**
   - `hotel.json` (Modelo A): Habitaciones, clientes y reservas.
   - `tienda_online.json` (Modelo B): Productos con ficha técnica, clientes con lista de deseos y pedidos con líneas de compra.
   - `gimnasio_rutinas.json` (Modelo C): Migración del árbol `gimnasio.xml` (rutinas con array de ejercicios, series y repeticiones) + socios con sesiones de entrenamiento.
   - `clinica_medica.json` (Modelo D): Cuadro médico con despachos, pacientes con historial anidado de diagnósticos y tratamientos, y citas médicas.
4. 🎙️ **Prepara la defensa oral (Parte 3):** Practica explicando en voz alta por qué un código postal es `string`, cuándo usar `[]` frente a `null`, cómo se relacionan dos arrays mediante `id` y qué diferencia hay entre un índice `[1]` en XPath y `[0]` en JSON.

---

## 📌 Guía Rápida de Repaso por Bloque de Clase

### 🌐 1. HTML de Cero a Avanzado (`HTML.pdf` · Bloques 1 al 13)
- **Bloques 1 y 2 (Conceptos, Textos y Enlaces):** Estructura `<!DOCTYPE html>`, `<html lang="es">`, `<head>` (invisible) y `<body>` (visible) convertido en el **DOM**. Jerarquía `<h1>`–`<h6>` (un solo `<h1>` por página sin saltar niveles), `<strong>`/`<em>` frente a `<b>`/`<i>`, citas (`<blockquote>`, `<q>`), código y teclado (`<code>`, `<kbd>`, `<pre>`), abreviaturas (`<abbr title="...">`), entidades (`&lt;`, `&amp;`, `&copy;`) y enlaces (`target="_blank" rel="noopener"`, `mailto:`, `tel:`, `download` y anclas internas `#id`).
- **Bloques 3 y 4 (Listas y Tablas):** `<ul>`, `<ol>` (`start`, `reversed`, `type`) con sublistas siempre **dentro** del `<li>` padre, y listas de definición `<dl>` (`<dt>`, `<dd>`). Tablas solo para datos tabulares (`<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<th scope="col|row">`, `colspan` y `rowspan`).
- **Bloques 5 y 6 (Multimedia y Semántica):** `<img>` con `alt`, `width`, `height`, `loading="lazy"`, `<figure>`/`<figcaption>` y `<picture>` (`srcset`, `sizes`). Formatos `JPG`, `PNG`, `SVG` y `WebP`. Etiquetas semánticas: `<header>`, `<nav>`, `<main>` (único), `<article>` (autónomo), `<section>` (con título), `<aside>`, `<footer>`, `<time datetime="...">` y desplegables `<details>` + `<summary>`.
- **Bloques 7 y 8 (Formularios y HTML5):** `<form action="..." method="post|get">`, `<label for="id">`, `<fieldset>` + `<legend>`, `radio` (mismo `name`) vs `checkbox`, `<select>`/`<option>`, `<button type="submit|reset|button">`. Validación y controles HTML5: `required`, `min`, `max`, `minlength`, `pattern`, `placeholder` (no sustituye al `label`), `<datalist>`, `multiple`, `accept`, `readonly`, `disabled`, `autofocus`, `novalidate`, `<progress>` y `<meter>`.
- **Bloques 9 al 13 (SEO, Accesibilidad y Validación):** `charset="UTF-8"`, `viewport`, `title`, `description`, `favicon`, `canonical`, `robots` y Open Graph (`og:*`). Enlace a CSS (`<link rel="stylesheet">`) y JS (`<script defer>`). Accesibilidad: teclado (`Tab`/`Enter`), enlace «Saltar al contenido», `aria-label`, `aria-expanded`, `aria-controls`, `aria-describedby` y `role="alert"`. Validación en **W3C Validator** (0 errores).

### 🗂️ 2. XML, XSD y XPath (`LENGUAJES DE MARCAS _XML.pdf` y `TEORÍA BÁSICA DE XPATH.pdf`)
- **Reglas Básicas de XML (Bien formado):** Declaración `<?xml version="1.0"?>` al inicio, un **único elemento raíz**, etiquetas siempre cerradas, anidamiento correcto y distinción entre mayúsculas y minúsculas (`<Nombre>` ≠ `<nombre>`).
- **Esquemas XSD (Válido):** Define las reglas y tipos de datos que debe cumplir un documento XML (`xs:string`, `xs:decimal`, `xs:integer`), combinando `xs:element`, `xs:complexType`, `xs:sequence` (orden específico y obligatorio de los hijos), número de ocurrencias (`minOccurs`, `maxOccurs="unbounded"`) y `xs:attribute` (`use="required"`).
- **Chuleta de XPath (`gimnasio.xml`):**
  - `/`: Desciende un nivel directo (`/gimnasio/rutina`).
  - `//`: Busca en cualquier nivel de profundidad (`//ejercicio/nombre`).
  - `@`: Selecciona o filtra un atributo (`rutina/@id` o `rutina[@id='RUT001']`).
  - `[ ]`: Predicado para filtrar por condición, elemento hijo (`[nombre='Sentadilla']`), posición empezando en 1 (`ejercicio[1]`) o texto (`nivel[text()='Principiante']`).
  - `*`: Comodín que selecciona todos los elementos hijos de ese nivel (`rutina/*`).

### 🔧 3. JSON y Modelado de Datos (`[UD2] JSON.pdf` · Bloques 1 al 10)
- **Sintaxis y Estructura Básica (Bloques 1–6):** Objetos `{}` formados por pares `"propiedad": valor` separados por comas `,`, y listas en Arrays `[]` (que pueden contener textos, números, booleanos, objetos u otros arrays).
- **Tipos de Datos y Errores Frecuentes (Bloques 3 y 8):** 6 tipos: `String` (entre comillas dobles), `Number` (enteros y decimales con punto `.`, sin comillas), `Boolean` (`true`/`false` siempre en minúscula), `Null` (`null` sin comillas), `Object` `{}` y `Array` `[]`. Errores clásicos: coma final sobrante (*trailing comma*), propiedad sin comillas dobles, booleano con mayúscula (`True`) o falta de coma entre objetos de un array.
- **Comparativa XML vs JSON y Relaciones (Bloques 7, 9 y 10):**
  - En XML se usan etiquetas y atributos (más verboso); en JSON se usan propiedades y valores sin atributos (más compacto).
  - En los proyectos JSON en Visual Studio Code (`hotel.json`, `tienda_online.json`), los registros se relacionan mediante identificadores (`clienteId`, `productoId`, `habitacionId`) sin duplicar información, y el acceso a elementos de un array empieza siempre en el índice `[0]`.

---

⬅️ [**Volver al índice principal del repositorio**](../README.md)
