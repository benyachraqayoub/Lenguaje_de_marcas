# Ejercicio 18 — Red social con relaciones por ID

## Solución

```json
{
  "redSocial": {
    "usuarios": [
      {
        "id": "u1",
        "usuario": "luna.dev",
        "perfil": {
          "bio": "Desarrollo web y café.",
          "ubicacion": "Valencia",
          "verificado": true
        },
        "siguiendo": ["u2", "u3"]
      },
      {
        "id": "u2",
        "usuario": "marcos.codes",
        "perfil": {
          "bio": "Aprendiendo algo nuevo cada día.",
          "ubicacion": "Madrid",
          "verificado": false
        },
        "siguiendo": ["u1"]
      },
      {
        "id": "u3",
        "usuario": "ines.design",
        "perfil": {
          "bio": "Diseño, ilustración y tecnología.",
          "ubicacion": "Sevilla",
          "verificado": false
        },
        "siguiendo": ["u1", "u2"]
      }
    ],
    "publicaciones": [
      {
        "id": "p1",
        "autorId": "u1",
        "texto": "Hoy terminé mi primer proyecto web.",
        "fecha": "2026-10-09T14:30:00",
        "reacciones": {
          "meGusta": 12,
          "risa": 1,
          "sorpresa": 2
        },
        "hashtags": ["desarrollo", "web"]
      },
      {
        "id": "p2",
        "autorId": "u2",
        "texto": "Un buen diseño empieza por escuchar.",
        "fecha": "2026-10-10T09:15:00",
        "reacciones": {
          "meGusta": 8,
          "risa": 0,
          "sorpresa": 1
        },
        "hashtags": ["diseño", "ux"]
      },
      {
        "id": "p3",
        "autorId": "u3",
        "texto": "Compartiendo inspiración para el fin de semana.",
        "fecha": "2026-10-11T18:45:00",
        "reacciones": {
          "meGusta": 15,
          "risa": 3,
          "sorpresa": 0
        },
        "hashtags": []
      },
      {
        "id": "p4",
        "autorId": "u1",
        "texto": "Pequeños avances, grandes resultados.",
        "fecha": "2026-10-12T12:00:00",
        "reacciones": {
          "meGusta": 6,
          "risa": 0,
          "sorpresa": 1
        },
        "hashtags": ["motivacion"]
      }
    ],
    "comentarios": [
      {
        "id": "c1",
        "publicacionId": "p1",
        "autorId": "u2",
        "texto": "¡Enhorabuena!",
        "editado": false
      },
      {
        "id": "c2",
        "publicacionId": "p1",
        "autorId": "u3",
        "texto": "Me encanta el resultado.",
        "editado": false
      },
      {
        "id": "c3",
        "publicacionId": "p2",
        "autorId": "u1",
        "texto": "Totalmente de acuerdo.",
        "editado": true
      },
      {
        "id": "c4",
        "publicacionId": "p3",
        "autorId": "u2",
        "texto": "Gracias por compartirlo.",
        "editado": false
      },
      {
        "id": "c5",
        "publicacionId": "p4",
        "autorId": "u3",
        "texto": "¡A seguir así!",
        "editado": false
      }
    ]
  }
}
```

## Tipos de Datos Utilizados
* **usuarios**, **publicaciones** y **comentarios:** Arrays al mismo nivel dentro de **redSocial**.
* **perfil** y **reacciones:** Objects anidados.
* **siguiendo**, **hashtags** y **comentarios:** Arrays.
* Los identificadores son String y las relaciones se establecen mediante `autorId`, `publicacionId` y los IDs de **siguiendo**.
* **verificado** y **editado:** Boolean; los contadores de reacciones son Number.
* Ningún usuario se sigue a sí mismo y una publicación tiene **hashtags** vacío.

**Objetivo:** Entender la diferencia entre anidar datos y relacionarlos mediante identificadores.
