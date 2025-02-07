# ¿Qué es el DOM y Cómo Se Relaciona con los Proyectos Web?

El **DOM** (Document Object Model) es una interfaz de programación que representa la estructura de un documento HTML o XML como un árbol de nodos. A través del DOM, los desarrolladores pueden acceder, modificar y manipular el contenido y la estructura de una página web de forma dinámica utilizando JavaScript.

## Introducción al DOM

El DOM convierte cada elemento HTML en un objeto que puede ser accedido y modificado a través de JavaScript. Esto permite a los desarrolladores interactuar con el contenido de la página web en tiempo real, como cambiar el texto, agregar nuevos elementos o responder a eventos del usuario.

### Ejemplo básico de manipulación del DOM:
```javascript
// Cambiar el texto de un encabezado
document.getElementById("titulo").innerText = "Nuevo Título";

