# Ejercicio 1 - Extra

## Objetivo

Crear un objeto JSON que almacene la información de un coche y de su conductor.

## Datos que debe incluir el objeto

### Información del coche
- Marca
- Modelo
- Matrícula
- Kilómetros

### Información del conductor
- Nombre
- Apellido
- Email

## Requisitos

- El archivo debe contener un JSON válido.
- Debe estar bien estructurado y con formato legible.
- Los datos del conductor deben incluirse dentro del mismo objeto JSON.
- Se recomienda usar nombres claros y consistentes para cada propiedad.

## Ejemplo de estructura

```json
{
  "marca": "Toyota",
  "modelo": "Corolla",
  "matricula": "1234-BCD",
  "kilometros": 25000,
  "conductor": {
    "nombre": "Ana",
    "apellido": "García",
    "email": "ana.garcia@email.com"
  }
}
```

## Resultado esperado

Se debe entregar un JSON completo y correcto que represente un coche con sus datos principales y la información del conductor.