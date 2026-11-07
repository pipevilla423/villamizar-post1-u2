
# Laboratorio POST1-U2

**Estudiante:** William Felipe Villamizar Soler  
**Código:** 1152498  
**Programa:** Ingeniería de Sistemas

## Descripción

Repositorio correspondiente al laboratorio POST1-U2.

El proyecto se divide en dos partes, organizadas en carpetas independientes dentro de un único repositorio Git.

## Estructura

- parte-1-pagina-semantica/: Página web con HTML semántico.
- Parte 2: Se incorporará posteriormente.

## Tecnologías

- HTML5
- Git
- GitHub


## Decisiones de diseño

### Estructura semántica de logros y certificaciones

Se eligió la opción B, utilizando una lista no ordenada
(`<ul>`) con elementos `<li>` para representar los logros.

Según el criterio de la guía teórica, sección 2.3,
un contenido debe representarse mediante `<article>`
cuando tiene sentido por sí solo fuera del sitio.

En este caso, los logros son descripciones breves
que adquieren mayor sentido como parte del conjunto
de la trayectoria académica del estudiante.
Por esta razón, se utiliza una lista simple
sin artículos independientes.


### Decisión de formato multimedia

Se eligió la opción B, audio con transcripción,
porque permite presentar una introducción personal
utilizando archivos más ligeros y fáciles de gestionar.

El elemento `<audio>` incorpora controles nativos
y dos formatos compatibles: MP3 y OGG.

La transcripción literal se incluye mediante
`<details>` y `<summary>` para garantizar el acceso
a la información sin necesidad de escuchar el audio.

Esta decisión aplica el principio "Perceptible"
de las WCAG, permitiendo acceder al contenido
mediante una alternativa textual equivalente.
