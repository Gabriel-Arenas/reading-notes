# Introducción a JavaScript

## ¿Qué es JavaScript?

**JavaScript** es un lenguaje de programación utilizado principalmente para crear interactividad en las páginas web. Permite manipular elementos HTML y CSS, responder a eventos como clics o desplazamientos, y trabajar con datos en tiempo real. A menudo se usa en combinación con HTML y CSS para crear aplicaciones web dinámicas y ricas en funciones.

## ¿Por qué usar JavaScript?

JavaScript es esencial para el desarrollo web moderno debido a su capacidad para agregar interactividad y dinamismo a las páginas. Algunos de los usos más comunes de JavaScript incluyen:

- Validación de formularios.
- Creación de animaciones.
- Manejo de eventos de usuario (como clics y desplazamientos).
- Interacción con APIs para obtener y mostrar datos sin recargar la página.

## Sintaxis Básica de JavaScript

Un script de JavaScript generalmente se coloca dentro de una etiqueta `<script>` en un archivo HTML. Aquí tienes un ejemplo básico:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo JavaScript</title>
</head>
<body>
  <h1>Hola, mundo!</h1>
  <button onclick="alert('¡Hola desde JavaScript!')">Haz clic aquí</button>

  <script>
    console.log("Este es un mensaje en la consola.");
  </script>
</body>
</html>

