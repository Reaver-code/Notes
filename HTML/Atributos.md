
# Atributos en HTML

```markdown
Los **atributos** en HTML proporcionan información adicional sobre los elementos y suelen aparecer dentro de la etiqueta de apertura. Algunos atributos son globales (pueden aplicarse a cualquier elemento), mientras que otros son específicos de ciertos elementos.

## Atributos Globales

Los **atributos globales** pueden ser utilizados en cualquier elemento HTML y añaden funcionalidad o comportamiento adicional.

### Principales atributos globales

- **`id`**: Proporciona un identificador único a un elemento. 
  ```html
  <div id="principal">Contenido principal</div>
  ```

- **`class`**: Agrupa elementos en una clase, permitiendo aplicar estilos comunes a varios elementos.
  ```html
  <p class="destacado">Este es un texto destacado.</p>
  ```

- **`style`**: Permite aplicar estilos CSS en línea directamente al elemento.
  ```html
  <h1 style="color: blue;">Título azul</h1>
  ```

- **`title`**: Proporciona información adicional sobre el elemento, que se muestra como una sugerencia emergente (tooltip) al pasar el cursor por encima.
  ```html
  <a href="https://example.com" title="Visitar ejemplo">Enlace</a>
  ```

- **`data-*`**: Permite almacenar datos personalizados dentro de los elementos, útiles para aplicaciones JavaScript.
  ```html
  <div data-user-id="123">Usuario</div>
  ```

## Atributos Específicos

Algunos atributos solo pueden aplicarse a tipos específicos de elementos HTML.

### Atributos comunes en imágenes

- **`src`**: Define la fuente de una imagen.
  ```html
  <img src="imagen.jpg" alt="Descripción de la imagen">
  ```

- **`alt`**: Proporciona un texto alternativo a la imagen en caso de que no se pueda cargar.
  ```html
  <img src="imagen.jpg" alt="Descripción de la imagen">
  ```

### Atributos comunes en enlaces

- **`href`**: Especifica la URL a la que apunta un enlace.
  ```html
  <a href="https://example.com">Ir a ejemplo.com</a>
  ```

- **`target`**: Indica cómo abrir el enlace. Por ejemplo, `_blank` para abrir en una nueva pestaña.
  ```html
  <a href="https://example.com" target="_blank">Abrir en una nueva pestaña</a>
  ```

### Atributos comunes en formularios

- **`action`**: Define la URL a la que se enviarán los datos del formulario.
  ```html
  <form action="/enviar-datos" method="POST">
    <input type="text" name="nombre">
  </form>
  ```

- **`method`**: Especifica el método HTTP utilizado para enviar los datos del formulario (`GET` o `POST`).
  ```html
  <form action="/enviar-datos" method="POST">
    <input type="submit" value="Enviar">
  </form>
  ```

### Atributos comunes en campos de entrada

- **`type`**: Define el tipo de dato que acepta el campo de entrada (`text`, `email`, `password`, etc.).
  ```html
  <input type="email" name="correo">
  ```

- **`placeholder`**: Muestra un texto de ejemplo dentro del campo antes de que el usuario escriba.
  ```html
  <input type="text" placeholder="Introduce tu nombre">
  ```

- **`required`**: Hace que el campo sea obligatorio para el envío del formulario.
  ```html
  <input type="text" name="nombre" required>
  ```

## Resumen de Atributos Comunes

| Atributo     | Descripción                                                  | Ejemplo                                           |
|--------------|--------------------------------------------------------------|---------------------------------------------------|
| `id`         | Identificador único para un elemento                         | `<div id="header"></div>`                         |
| `class`      | Agrupa elementos bajo una clase común                        | `<p class="destacado"></p>`                       |
| `style`      | Aplica estilos CSS en línea                                  | `<h1 style="color:red;"></h1>`                    |
| `href`       | URL de destino de un enlace                                  | `<a href="https://example.com"></a>`              |
| `src`        | Fuente de una imagen o multimedia                            | `<img src="imagen.jpg">`                          |
| `alt`        | Texto alternativo para imágenes                              | `<img alt="Descripción de la imagen">`            |
| `placeholder`| Texto de ejemplo dentro de campos de entrada                 | `<input placeholder="Introduce tu nombre">`       |
| `target`     | Define cómo abrir un enlace (p. ej., en nueva pestaña)        | `<a href="..." target="_blank"></a>`              |
| `data-*`     | Almacena datos personalizados dentro de los elementos        | `<div data-product-id="123"></div>`               |

## Buenas Prácticas con Atributos

- **Accesibilidad**: Usa atributos como `alt` en imágenes para mejorar la accesibilidad.
- **Identificadores únicos**: Asegúrate de que los valores de `id` sean únicos en cada página.
- **Usar `class` para estilos**: Evita usar `style` en línea; es mejor usar `class` para estilos consistentes a través de CSS.
```
Este apartado cubre los atributos más usados en HTML, tanto los globales como los específicos de ciertos elementos.