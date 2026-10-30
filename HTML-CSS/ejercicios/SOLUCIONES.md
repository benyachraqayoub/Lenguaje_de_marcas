# Soluciones de ejercicios HTML

Las siguientes soluciones son documentos HTML completos. Cada bloque puede
guardarse en un archivo `.html` independiente y abrirse directamente en un
navegador.

## Ejercicio 1: Mi primera página HTML

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi primera web</title>
  </head>
  <body>
    <h1>Hola, mundo</h1>
    <p>Me llamo Ayoub.</p>
    <p>
      Espero aprender a crear páginas web con HTML y a estructurar su contenido
      correctamente.
    </p>
  </body>
</html>
```

## Ejercicio 2: Presentación personal

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Presentación personal</title>
  </head>
  <body>
    <h1>Ayoub</h1>

    <h2>Sobre mí</h2>
    <p>
      Soy estudiante de Desarrollo de Aplicaciones Web y estoy aprendiendo a
      crear páginas web.
    </p>
    <p>
      Me interesa la tecnología y quiero mejorar mis conocimientos de
      programación y diseño web.
    </p>

    <h2>Mis aficiones</h2>
    <p>
      <p>la programación</p>
      <p>los videojuegos</p>
      <p>la música</p>
    </p>
  </body>
</html>
```

## Ejercicio 3: Enlaces y atributos

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mis sitios favoritos</title>
  </head>
  <body>
    <h1>Mis sitios favoritos</h1>


    <p>
      Estos son algunos sitios web que consulto para buscar información y
      aprender.
    </p>

    
    <p><a href="https://www.google.com/" target="_blank">Buscar información en Google</a></p>
    <p><a href="https://es.wikipedia.org/wiki/HTML">Consultar el artículo de HTML en Wikipedia</a></p>
    <p><a href="https://digitechfp.com/">Visitar la web de Digitech FP</a></p>
   

  </body>
</html>
```

**Respuesta a la pregunta adicional:** En `<a href="...">Google</a>`, el
atributo `href` especifica la dirección a la que lleva el enlace, por lo que
se puede hacer clic para navegar a ese destino. En `<a>Google</a>` falta
`href`: sigue siendo un elemento `<a>`, pero no tiene un destino y no funciona
como un enlace navegable.

## Ejercicio 4: Estructura de una página

```html
<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CodeAcademy</title>
</head>

<body>
  <h1>CodeAcademy</h1>

  <p>lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna
    aliqua.</p>

  <h2>Cursos</h2>
  <ul>
    <li>
      <h3>html</h3>
    </li>
    <li>
      <h3>css</h3>
    </li>
    <li>
      <h3>javascript</h3>
    </li>
  </ul>

  <h2>Sobre nosotros</h2>
  <p>
    CodeAcademy es una academia ficticia que ofrece cursos para aprender
    los fundamentos del desarrollo web.
  </p>

  <h2>Contacto</h2>
  <p>
    <a href="mailto:info@codeacademy.example">
      Escribir a CodeAcademy por correo electrónico
    </a>
  </p>

  </main>
</body>

</html>
```

## Ejercicio 5: Página web completa

```html
<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Granada: historia y lugares de interés</title>
</head>

<body>

  <h1>Granada</h1>
  <p>
    Granada es una ciudad andaluza conocida por su patrimonio histórico,
    sus barrios tradicionales y sus vistas a Sierra Nevada.
  </p>



  <h2>¿Por qué visitar este lugar?</h2>
  <p>
    Granada reúne monumentos de distintas épocas y una marcada herencia
    cultural. Sus calles y plazas permiten descubrir la historia de la
    ciudad mientras se pasea por sus barrios.
  </p>
  <p>
    También ofrece paisajes variados: desde miradores con vistas a la
    Alhambra hasta las montañas de Sierra Nevada en el horizonte. Es un
    destino interesante para quienes disfrutan de la historia, la
    arquitectura y la naturaleza.
  </p>



  <h2>Lugares de interés</h2>

  <h3>La Alhambra</h3>
  <p>
    La Alhambra es un conjunto monumental de palacios, patios y jardines
    que refleja la historia de Granada.
  </p>

  <h3>El Albaicín</h3>
  <p>
    El Albaicín es un barrio histórico de calles estrechas y miradores,
    situado frente a la Alhambra.
  </p>

  <h3>El Generalife</h3>
  <p>
    El Generalife fue una residencia de descanso con jardines y espacios
    al aire libre vinculados a la Alhambra.
  </p>



  <h2>Información útil</h2>
  <p>
    Para planificar una visita y consultar información turística,
    <a href="https://www.spain.info/es/destino/granada/" target="_blank">
      visita la página de Granada en Spain.info
    </a>.
  </p>

</body>

</html>
```
