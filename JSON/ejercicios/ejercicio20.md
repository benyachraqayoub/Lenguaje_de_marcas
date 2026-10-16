# Ejercicio 20 — Simulación de respuesta de una API

La solución contiene los dos archivos JSON solicitados:

* [Respuesta correcta de la API](./ejercicio20_respuesta_correcta.json)
* [Respuesta con error de la API](./ejercicio20_respuesta_error.json)

La respuesta correcta incluye cuatro series, datos de paginación, disponibilidad por código de país, temporadas y episodios anidados. La respuesta de error devuelve el estado 404, `ok` igual a `false`, `data` igual a `null` y dos objetos de error.

## Reto Extra

1. Título del segundo episodio de la primera temporada de la tercera serie: `data[2].temporadas[0].episodios[1].titulo`.
2. Actor principal de la primera serie: `data[0].reparto[0].actor`.
3. Disponibilidad de la segunda serie en México: `data[1].disponibleEn.MX`.

**Objetivo:** Reproducir una estructura realista de API con claves dinámicas, valores `null` y arrays anidados.
