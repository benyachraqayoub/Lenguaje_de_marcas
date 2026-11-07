# Respuestas teóricas

## Preguntas tipo test

| Pregunta | Respuesta | Pregunta | Respuesta | Pregunta | Respuesta |
|---:|:---:|---:|:---:|---:|:---:|
| 1 | B | 10 | B | 19 | D |
| 2 | D | 11 | D | 20 | B |
| 3 | A | 12 | C | 21 | A |
| 4 | C | 13 | A | 22 | D |
| 5 | B | 14 | B | 23 | C |
| 6 | A | 15 | D | 24 | A |
| 7 | D | 16 | A | 25 | D |
| 8 | C | 17 | B | 26 | B |
| 9 | A | 18 | C | 27 | C |

## Preguntas de respuesta abierta

### 1. Uso de los encabezados

Los encabezados sirven para organizar el contenido, no solo para cambiar el tamaño del texto. Si necesito cambiar su aspecto, lo hago con CSS (`font-size`).

### 2. XML bien formado y XML válido

**Bien formado** significa que el XML está escrito correctamente: las etiquetas están cerradas y ordenadas. **Válido** significa que, además, cumple las reglas del XSD.

- **Mal formado:** escribir `<nombre>Press banca</ejercicio>`, porque las etiquetas no coinciden.
- **Bien formado pero inválido:** si el XSD pide un número en `<series>`, escribir `<series>cuatro</series>`. Las etiquetas están bien, pero el valor no cumple el tipo indicado.

### 3. Representación de un producto en XML y JSON

**XML**

```xml
<producto id="P001">
  <nombre>Ratón</nombre>
  <precio>19.99</precio>
  <stock>20</stock>
  <activo>true</activo>
</producto>
```

**JSON**

```json
{
  "id": "P001",
  "nombre": "Ratón",
  "precio": 19.99,
  "stock": 20,
  "activo": true
}
```

**Tres diferencias:**

- XML usa etiquetas; JSON usa claves y valores.
- XML necesita un elemento raíz; JSON puede empezar directamente con un objeto.
- En JSON se indican tipos como número y booleano; en XML los valores se escriben como texto, salvo que se definan sus tipos con un esquema.
