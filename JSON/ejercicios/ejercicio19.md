# Ejercicio 19 — Clínica con historial médico

## Solución

```json
{
  "clinica": {
    "nombre": "Clínica Horizonte",
    "direccion": {
      "calle": "Calle de la Salud, 18",
      "ciudad": "Valencia",
      "codigoPostal": "46004"
    },
    "configuracion": {
      "horarioApertura": "08:00",
      "horarioCierre": "20:00",
      "duracionCitaMinutos": 30
    },
    "medicos": [
      {
        "id": "m1",
        "nombre": "Dra. Alba Ruiz",
        "especialidad": "Medicina general",
        "colegiado": "V-12345",
        "consultas": ["lunes", "miércoles", "viernes"]
      },
      {
        "id": "m2",
        "nombre": "Dr. Bruno Soler",
        "especialidad": "Dermatología",
        "colegiado": "V-23456",
        "consultas": ["martes", "jueves"]
      },
      {
        "id": "m3",
        "nombre": "Dra. Carla Vidal",
        "especialidad": "Pediatría",
        "colegiado": "V-34567",
        "consultas": ["lunes", "martes", "jueves"]
      }
    ],
    "pacientes": [
      {
        "id": "p1",
        "nombre": "Alex",
        "fechaNacimiento": "1992-04-18",
        "seguro": {
          "compania": "Salud Plus",
          "numeroPoliza": "SP-10021"
        },
        "alergias": ["polen"],
        "historial": [
          {
            "fecha": "2026-03-10",
            "diagnostico": "Alergia estacional",
            "tratamiento": {
              "medicamento": "Loratadina",
              "dosis": "10 mg",
              "duracionDias": 7
            }
          }
        ]
      },
      {
        "id": "p2",
        "nombre": "Sam",
        "fechaNacimiento": "1987-11-02",
        "seguro": null,
        "alergias": [],
        "historial": [
          {
            "fecha": "2026-02-14",
            "diagnostico": "Esguince leve",
            "tratamiento": {
              "medicamento": "Ibuprofeno",
              "dosis": "400 mg",
              "duracionDias": 3
            }
          },
          {
            "fecha": "2026-05-22",
            "diagnostico": "Dolor muscular",
            "tratamiento": {
              "medicamento": "Paracetamol",
              "dosis": "500 mg",
              "duracionDias": 2
            }
          }
        ]
      },
      {
        "id": "p3",
        "nombre": "Noa",
        "fechaNacimiento": "2015-08-30",
        "seguro": {
          "compania": "Cobertura Familiar",
          "numeroPoliza": "CF-88402"
        },
        "alergias": ["ácaros"],
        "historial": [
          {
            "fecha": "2026-01-19",
            "diagnostico": "Revisión rutinaria",
            "tratamiento": {
              "medicamento": "Ninguno",
              "dosis": "No aplica",
              "duracionDias": 0
            }
          }
        ]
      }
    ],
    "citas": [
      {
        "id": "c1",
        "pacienteId": "p1",
        "medicoId": "m1",
        "fecha": "2026-10-20T09:00:00",
        "confirmada": true,
        "notas": "Revisión anual"
      },
      {
        "id": "c2",
        "pacienteId": "p2",
        "medicoId": "m2",
        "fecha": "2026-10-20T10:30:00",
        "confirmada": true,
        "notas": null
      },
      {
        "id": "c3",
        "pacienteId": "p3",
        "medicoId": "m3",
        "fecha": "2026-10-21T11:00:00",
        "confirmada": false,
        "notas": "Primera consulta"
      },
      {
        "id": "c4",
        "pacienteId": "p1",
        "medicoId": "m2",
        "fecha": "2026-10-22T14:00:00",
        "confirmada": true,
        "notas": "Consulta dermatológica"
      },
      {
        "id": "c5",
        "pacienteId": "p2",
        "medicoId": "m1",
        "fecha": "2026-10-23T16:30:00",
        "confirmada": false,
        "notas": null
      }
    ]
  }
}
```

## Reto Extra

1. Ruta al medicamento del primer diagnóstico del segundo paciente: `clinica.pacientes[1].historial[0].tratamiento.medicamento`.
2. Para saber qué citas pertenecen a un médico, se buscan en `clinica.citas` las que tengan `medicoId` igual al `id` de ese médico.
3. No tienen seguro los pacientes cuyo campo `seguro` sea `null`. En este ejemplo, es el segundo paciente (**Sam**).

**Objetivo:** Combinar anidación profunda con relaciones por ID y practicar la navegación por un JSON complejo.
