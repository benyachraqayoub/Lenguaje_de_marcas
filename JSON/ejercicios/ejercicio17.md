# Ejercicio 17 — Centro de formación

## Solución

```json
{
  "academia": {
    "nombre": "Centro de Formación Horizonte",
    "fundacion": 2012,
    "sede": {
      "ciudad": "Valencia",
      "pais": "España",
      "coordenadas": {
        "lat": 39.4699,
        "lng": -0.3763
      }
    },
    "cursos": [
      {
        "codigo": "DAW-01",
        "titulo": "Desarrollo web",
        "profesor": {
          "nombre": "Elena Torres",
          "especialidades": ["HTML", "CSS", "JavaScript"],
          "contacto": {
            "email": "elena.torres@example.com",
            "telefono": "+34 600 111 222"
          }
        },
        "horario": {
          "dia": "Lunes",
          "inicio": "09:00",
          "fin": "11:00"
        },
        "alumnos": [
          {
            "nombre": "Nora",
            "activo": true,
            "notas": [8, 9, 7],
            "notaFinal": 8
          },
          {
            "nombre": "Hugo",
            "activo": true,
            "notas": [6, 7, 8],
            "notaFinal": 7
          },
          {
            "nombre": "Inés",
            "activo": false,
            "notas": [7, 8],
            "notaFinal": null
          }
        ]
      },
      {
        "codigo": "BD-02",
        "titulo": "Bases de datos",
        "profesor": {
          "nombre": "Pablo Martín",
          "especialidades": ["SQL", "Modelado de datos"],
          "contacto": {
            "email": "pablo.martin@example.com",
            "telefono": "+34 600 333 444"
          }
        },
        "horario": {
          "dia": "Martes",
          "inicio": "11:30",
          "fin": "13:30"
        },
        "alumnos": [
          {
            "nombre": "Leo",
            "activo": true,
            "notas": [9, 8, 10],
            "notaFinal": 9
          },
          {
            "nombre": "Vera",
            "activo": true,
            "notas": [7, 8, 8],
            "notaFinal": 8
          },
          {
            "nombre": "Eric",
            "activo": true,
            "notas": [6, 7, 7],
            "notaFinal": 7
          }
        ]
      },
      {
        "codigo": "UX-03",
        "titulo": "Diseño de interfaces",
        "profesor": {
          "nombre": "Sara Gil",
          "especialidades": ["UX", "Accesibilidad"],
          "contacto": {
            "email": "sara.gil@example.com",
            "telefono": "+34 600 555 666"
          }
        },
        "horario": {
          "dia": "Miércoles",
          "inicio": "15:00",
          "fin": "17:00"
        },
        "alumnos": [
          {
            "nombre": "Mara",
            "activo": true,
            "notas": [8, 9, 9],
            "notaFinal": 9
          },
          {
            "nombre": "Adrián",
            "activo": true,
            "notas": [7, 6, 8],
            "notaFinal": 7
          },
          {
            "nombre": "Clara",
            "activo": true,
            "notas": [9, 10, 9],
            "notaFinal": 9
          }
        ]
      }
    ]
  }
}
```

## Tipos de Datos Utilizados
* **academia**, **sede**, **coordenadas**, **profesor**, **contacto** y **horario:** Object.
* **cursos**, **alumnos**, **especialidades** y **notas:** Array.
* **nombre**, **codigo**, **titulo**, los datos de contacto y el horario: String.
* **fundacion**, **lat**, **lng**, las notas y **notaFinal**: Number; **notaFinal** también puede ser `null`.
* **activo:** Boolean. Al menos un alumno tiene **notaFinal** igual a `null`.

**Objetivo:** Trabajar con varios niveles de profundidad y usar `null` correctamente.
