# 📚 Preparación del Examen — 1.ª Evaluación

![Módulo](https://img.shields.io/badge/M%C3%B3dulo-Lenguajes_de_Marcas-185b83?style=flat-square)
![Curso](https://img.shields.io/badge/Curso-1.%C2%BA_DAW-0f766e?style=flat-square)
![Contenidos](https://img.shields.io/badge/Temario-HTML5_%7C_XML_%7C_XSD_%7C_XPath_%7C_JSON-6d28d9?style=flat-square)
![Modelos](https://img.shields.io/badge/Simulacros-4_Modelos_(A--D)-c2410c?style=flat-square)

Apartado de repaso y simulacros dentro del repositorio de **Lenguajes de marcas y sistemas de gestión de información** para preparar el examen oficial de la primera evaluación.

> [!NOTE]
> **Sobre este apartado del repositorio:** El **Modelo A** y sus archivos de corrección corresponden al material oficial proporcionado por el profesor en clase. Los **Modelos B, C y D** son simulacros adicionales creados con IA siguiendo la misma estructura y rúbrica para practicar, y no sustituyen las indicaciones oficiales del aula.

---

## ⏱️ Estructura y Rúbrica del Examen

| Bloque | Duración | Peso | Formato y condiciones |
| :--- | :---: | :---: | :--- |
| 🧠 **Parte 1: Teoría** | `30 min` | **$30\%$** | **27 preguntas tipo test** (cada 3 errores descuentan 1 acierto) + **3 preguntas abiertas**. Sin apuntes ni dispositivos. |
| 💻 **Parte 2: Práctica** | `90 min` | **$50\%$** | **Modelado completo en JSON** dividido en 5 tareas progresivas en Visual Studio Code. |
| 🗣️ **Parte 3: Defensa** | `3-5 min` | **$20\%$** | **Explicación y justificación oral** individual sin ayuda de pantallas ni IA. |

---

## 🚀 Simulacros Disponibles en esta Carpeta

Cada modelo cuenta con una **aplicación web interactiva** (con temporizador, autocorrección, modo oscuro y validador JSON en vivo) y su **documento Markdown** con el enunciado y el solucionario completo:

| Modelo | Caso Práctico | Origen | Acceso Directo al Material |
| :---: | :--- | :---: | :--- |
| ![Modelo A](https://img.shields.io/badge/MODELO_A-185b83?style=for-the-badge) | 🏨 **Hotel Costa Valencia** (`hotel.json`) | 👨‍🏫 Oficial de clase | [🎮 **Test Interactivo**](./modelo_a_interactivo.html) · [📄 **Enunciado y Solución**](./examen_modelo_a_y_solucionario.md) |
| ![Modelo B](https://img.shields.io/badge/MODELO_B-0f766e?style=for-the-badge) | 🐾 **Clínica Veterinaria Turia** (`clinica.json`) | 🤖 Simulacro IA | [🎮 **Test Interactivo**](./modelo_b_interactivo.html) · [📄 **Enunciado y Solución**](./examen_modelo_b_y_solucionario.md) |
| ![Modelo C](https://img.shields.io/badge/MODELO_C-6d28d9?style=for-the-badge) | 🚗 **Concesionario Albufera Motor** (`concesionario.json`) | 🤖 Simulacro IA | [🎮 **Test Interactivo**](./modelo_c_interactivo.html) · [📄 **Enunciado y Solución**](./examen_modelo_c_y_solucionario.md) |
| ![Modelo D](https://img.shields.io/badge/MODELO_D-c2410c?style=for-the-badge) | 🏋️ **Centro Deportivo Levante Fit** (`gimnasio.json`) | 🤖 Simulacro IA | [🎮 **Test Interactivo**](./modelo_d_interactivo.html) · [📄 **Enunciado y Solución**](./examen_modelo_d_y_solucionario.md) |

---

## 🧭 Cómo aprovechar estos materiales

> [!TIP]
> **Resuelve siempre cada modelo completo antes de desplegar las soluciones.** Así entrenarás tanto el control del tiempo como la detección de errores reales.

1. 📖 **Repasa la base teórica:** Revisa los conceptos clave de `HTML5`, `XML`, `XSD`, `XPath` y `JSON`.
2. 🎯 **Elige un modelo sin mirar las respuestas:** Abre primero la versión interactiva o el enunciado sin consultar el solucionario.
3. ⏲️ **Entrena con tiempo real:** Ponte un cronómetro de **30 minutos** para la teoría y **90 minutos** para la práctica.
4. 🔍 **Analiza tus fallos:** Compara tus respuestas con el solucionario y anota los errores que se repiten (comas finales, tipos de datos entre comillas, rutas de arrays, etc.).
5. 🎙️ **Prepara la defensa oral:** Practica una explicación breve en voz alta para justificar tus decisiones sin depender del código.

---

## 📌 Qué Repasar por Bloques

### 🌐 1. HTML5 y Accesibilidad
- **Estructura semántica:** Uso correcto de `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>` y `<footer>` frente a elementos usados solo para presentación.
- **Jerarquía de encabezados:** Respetar el orden lógico `<h1>` → `<h2>` → `<h3>` sin saltar niveles por motivos visuales.
- **Enlaces, listas y formularios:** Textos descriptivos en enlaces, `target="_blank" rel="noopener noreferrer"`, listas anidadas dentro de `<li>` y agrupación de `<input type="radio">` mediante el atributo `name`.
- **Accesibilidad y codificación:** Texto alternativo (`alt`), etiquetas con valor semántico (`<strong>`, `<em>`) frente a estilo visual (`<b>`, `<i>`), y `<meta charset="UTF-8">`.

### 🗂️ 2. XML, XSD y XPath
- **Buena formación vs. Validez:**
  - **Bien formado:** Un único elemento raíz, etiquetas correctamente anidadas y nombres sensibles a mayúsculas/minúsculas.
  - **Válido:** Además de estar bien formado, cumple las reglas de estructura y tipos de su esquema **XSD**.
- **Esquemas XSD:** Elementos, atributos (`use="required"` / `use="optional"`), orden con `<xs:sequence>`, ocurrencias (`minOccurs`, `maxOccurs`) y tipos de datos (`xs:string`, `xs:integer`, `xs:decimal`, `xs:boolean`, `xs:date`).
- **Relaciones sin redundancia:** Uso de identificadores (`id`) y referencias (`clienteId`, `habitacionId`) para evitar repetir información.
- **Lectura de rutas XPath:** Rutas absolutas (`/`) frente a búsquedas globales (`//`), selección mediante predicados por elemento hijo (`[nombre='Sentadilla']`) o atributo (`[@id='RUT001']`), y recuento de nodos devueltos.

### 🔧 3. JSON y Modelado de Datos
- **Sintaxis estricta:** Comillas dobles obligatorias en claves y textos, comas separadoras entre elementos, sin coma final (*trailing comma*), llaves `{}` y corchetes `[]`.
- **Tipos de datos:** Textos (`string`), números enteros y decimales con punto (`number`), booleanos en minúscula (`true`, `false`) y ausencia de valor con `null` (sin comillas).
- **Jerarquía coherente:** Objetos anidados (`direccion`, `contacto`, `ubicacion`, `pago`, `desglose`) y arrays de objetos.
- **Navegación y relaciones:** Referencias mediante identificadores, formato de fechas `AAAA-MM-DD` y acceso a rutas recordando que los arrays empiezan en el índice `[0]`.

---

## ✅ Lista de Comprobación para la Práctica

- [ ] Puedo detectar y explicar errores de sintaxis y de tipos de datos en JSON (Tarea 1).
- [ ] Sé decidir y justificar cuándo un dato debe ser texto, número, booleano, `null`, objeto o array (Tarea 2).
- [ ] Puedo construir objetos anidados y arrays con varios registros cuidando el escape de comillas `\"` (Tarea 3).
- [ ] Puedo relacionar registros usando identificadores sin duplicar datos innecesariamente (Tarea 4).
- [ ] Puedo interpretar una expresión XPath o una ruta JSON y explicar a qué dato accede (Tarea 5).
- [ ] He validado y formateado el JSON en VS Code (0 problemas) y puedo justificar mi solución con mis propias palabras.

---

## 📂 Material del Profesor para el Modelo A

El examen y los siguientes documentos de respuestas y práctica corresponden al material del **Modelo A** proporcionado por el profesor:

| Recurso | Formato | Descripción |
| :--- | :---: | :--- |
| 📕 [**Examen del Modelo A**](./EXAMEN_TIPO.pdf) | `PDF` | Enunciado oficial en PDF. |
| 📝 [**Respuestas Teóricas**](./01-respuestas-teoricas.md) | `Markdown` | Respuestas tipo test y preguntas abiertas. |
| 📋 [**Respuestas Prácticas**](./02-respuestas-practicas.md) | `Markdown` | Corrección y notas de los ejercicios prácticos. |
| 🧩 [**Fragmento JSON Corregido**](./fragmento_corregido.json) | `JSON` | Ejemplo corregido de la Tarea 1 de la práctica. |
| 🏨 [**Datos del Hotel**](./hotel.json) | `JSON` | Archivo JSON completo utilizado en los ejercicios. |

---

⬅️ [**Volver al índice principal del repositorio**](../README.md)