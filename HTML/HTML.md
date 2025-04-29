# HTML: Lenguaje de Marcado de Hipertexto

```markdown
HTML (Hypertext Markup Language) es el estándar para crear sitios web. Utiliza etiquetas (tags) para estructurar el contenido de las páginas.

## Estructura básica de un documento HTML
```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título de la página</title>
  </head>
  <body>
    <!-- Contenido de la página -->
  </body>
</html>
```

## Principales etiquetas HTML

### 1. Metaetiquetas
- `<meta>`: Proporciona metadatos sobre la página.
  ```html
  <meta charset="UTF-8">
  <meta name="description" content="Descripción del sitio web">
  <meta name="author" content="Autor">
  ```

### 2. Titulares y párrafos
- `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`: Encabezados de nivel 1 a 6.
  ```html
  <h1>Título principal</h1>
  <h2>Subtítulo</h2>
  ```

- `<p>`: Párrafo.
  ```html
  <p>Este es un párrafo.</p>
  ```

### 3. Enlaces
- `<a>`: Hipervínculo.
  ```html
  <a href="https://example.com">Enlace a otra página</a>
  ```

### 4. Imágenes
- `<img>`: Imagen.
  ```html
  <img src="imagen.jpg" alt="Descripción de la imagen">
  ```

### 5. Listas
- `<ul>`: Lista desordenada.
  ```html
  <ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
  </ul>
  ```

- `<ol>`: Lista ordenada.
  ```html
  <ol>
    <li>Primer elemento</li>
    <li>Segundo elemento</li>
  </ol>
  ```

### 6. Tablas
- `<table>`: Define una tabla.
- `<tr>`: Fila de la tabla.
- `<th>`: Encabezado de la tabla.
- `<td>`: Celda de la tabla.
  ```html
  <table>
    <tr>
      <th>Encabezado 1</th>
      <th>Encabezado 2</th>
    </tr>
    <tr>
      <td>Dato 1</td>
      <td>Dato 2</td>
    </tr>
  </table>
  ```

### 7. Formularios
- `<form>`: Crea un formulario.
  ```html
  <form action="/enviar" method="POST">
    <input type="text" name="nombre" placeholder="Nombre">
    <input type="submit" value="Enviar">
  </form>
  ```

- `<input>`: Campo de entrada.
  ```html
  <input type="text" name="nombre" placeholder="Nombre">
  ```

- `<textarea>`: Área de texto.
  ```html
  <textarea name="comentario"></textarea>
  ```

- `<button>`: Botón interactivo.
  ```html
  <button>Enviar</button>
  ```

### 8. Multimedia
- `<audio>`: Inserta audio.
  ```html
  <audio controls>
    <source src="audio.mp3" type="audio/mpeg">
  </audio>
  ```

- `<video>`: Inserta video.
  ```html
  <video controls>
    <source src="video.mp4" type="video/mp4">
  </video>
  ```

### 9. Etiquetas de estilo y semánticas
- `<div>`: Contenedor genérico.
  ```html
  <div>
    <p>Este es un bloque de contenido.</p>
  </div>
  ```

- `<span>`: Contenedor en línea.
  ```html
  <span>Texto en línea.</span>
  ```

- `<section>`, `<article>`, `<aside>`, `<header>`, `<footer>`: Etiquetas semánticas para estructurar el contenido.
  ```html
  <section>
    <h2>Sección</h2>
    <p>Contenido de la sección.</p>
  </section>
  ```

### 10. Comentarios
- Comentarios en HTML no visibles en el navegador.
  ```html
  <!-- Este es un comentario -->
  ```

## Atributos comunes
- `id`: Identificador único.
  ```html
  <div id="identificador">Contenido</div>
  ```

- `class`: Agrupa elementos.
  ```html
  <div class="clase">Contenido</div>
  ```

- `style`: Aplicar estilos en línea.
  ```html
  <p style="color: red;">Texto en rojo</p>
  ```

- `src`: Fuente del recurso (imágenes, videos, audio).
  ```html
  <img src="imagen.jpg" alt="Imagen">
  ```

- `href`: Enlaces.
  ```html
  <a href="https://example.com">Ir a ejemplo.com</a>
  ```

- `alt`: Texto alternativo para imágenes.
  ```html
  <img src="imagen.jpg" alt="Descripción de la imagen">
  ```

## Buenas prácticas
- Usar etiquetas semánticas como `<header>`, `<footer>`, `<article>`, `<section>` para mejorar la accesibilidad y SEO.
- Evitar el uso excesivo de `<div>` y `<span>`.
- Añadir texto alternativo en las imágenes con el atributo `alt`.

## Enlaces útiles
- [Documentación oficial de HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Guía de buenas prácticas en HTML](https://www.w3schools.com/html/)

```
Este resumen abarca los elementos más importantes de HTML que necesitarás para estructurar una página web.