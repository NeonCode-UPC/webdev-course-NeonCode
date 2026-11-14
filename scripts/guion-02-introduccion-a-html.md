# Nivel 2: Introducción a HTML (guion previsto de 10 min)

Editor para la práctica: CodePen. El video muestra los ejemplos en diapositivas. El Pen inicial incluye un título y dos párrafos.

## 1. Portada (0:00 a 0:10)

PANTALLA: portada del nivel 2 con el ícono </>.

VOZ: "Nivel 2. Hoy aprendes el lenguaje con el que se escribe el contenido de cualquier página: HTML."

## 2. Pregunta gancho (0:10 a 0:35)

PANTALLA: "¿Cómo le dices al navegador qué es un título y qué es un párrafo?".

VOZ: "¿Cómo le dices al navegador qué es un título y qué es un párrafo? Con etiquetas. Vamos a aprenderlas."

## 3. Misión (0:35 a 1:00)

PANTALLA: "MISIÓN 02".

VOZ: "Tu misión: entender qué es una etiqueta, conocer el esqueleto de una página y crear títulos, párrafos y atributos. La recompensa: una página bien estructurada."

## 4. Anatomía de una etiqueta (1:00 a 1:50)

PANTALLA: tres cajas: Apertura `<p>`, Contenido "Hola", Cierre `</p>`. Haz que aparezcan una por una.

VOZ: "Una etiqueta es una instrucción para el navegador. Tiene una apertura, el contenido y un cierre. Fíjate que el cierre lleva una barra. Las tres partes juntas forman un elemento."

## 5. El esqueleto de toda página (1:50 a 2:40)

PANTALLA: diagrama con `<html>` y, dentro, `<head>` y `<body>`.

VOZ: "Toda página tiene el mismo esqueleto. Head es la configuración: por ejemplo, el título de la pestaña. Body es el cuerpo: todo lo que se ve en la página."

## 6. El esqueleto en código (2:40 a 3:20)

PANTALLA: diapositiva con el esqueleto completo.

VOZ: "Así se ve el esqueleto en código. No tienes que escribirlo: CodePen ya lo prepara por ti. Nosotros vamos a escribir dentro del body. La línea title es el nombre que aparece en la pestaña del navegador."

EDITOR (opcional, 10 s): abre en CodePen el menú del panel HTML y muestra la opción de ver el código compilado, solo para que vean que el esqueleto existe.

## 7. Títulos y párrafos (3:20 a 4:30)

EDITOR: en el panel HTML escribe:

```html
<h1>Mi primera página</h1>
<p>Hola, me llamo Ana.</p>
<p>Estoy aprendiendo HTML.</p>
```

La vista previa muestra un título grande y dos párrafos.

VOZ: "h1 es el título principal. Cada p es un párrafo nuevo. Mira cómo el navegador los separa automáticamente."

## 8. Niveles de títulos (4:30 a 5:40)

EDITOR: borra lo anterior y escribe:

```html
<h1>Mi videojuego favorito</h1>
<h2>Historia</h2>
<p>Un héroe cruza el bosque.</p>
<h2>Personajes</h2>
<p>Hay un zorro y un robot.</p>
```

La vista previa muestra un título grande y dos subtítulos más pequeños.

VOZ: "Los títulos van de h1 a h6, del más grande al más pequeño. Funcionan como el índice de un libro: h1 es el nombre del libro y h2 son los capítulos." Cambia un h2 por h3 para mostrar la diferencia de tamaño.

## 9. Atributos: datos extra (5:40 a 6:40)

EDITOR: borra lo anterior y escribe:

```html
<p title="¡Hola, soy un atributo!">  Pasa el mouse por aquí.</p>
```

Pasa el mouse sobre el párrafo: aparece el mensaje.

VOZ: "Un atributo es un dato extra para la etiqueta. Va dentro de la apertura y tiene un nombre y un valor entre comillas. Aquí, title muestra un mensaje cuando pasas el mouse."

## 10. Quiz: ¿qué etiqueta crea el título más grande? (6:40 a 7:00)

PANTALLA: opciones A: `<h6>`, B: `<h1>`, C: `<p>`.

VOZ: "¿Qué etiqueta crea el título más grande?" (4 segundos) "Respuesta: B, h1."

## 11. Pausa y tu turno (7:00 a 7:40)

PANTALLA: "PAUSA · TU TURNO".

VOZ: "Pausa el video. Crea un h1 con tu nombre y agrega dos párrafos sobre ti. Un consejo: cierra siempre cada etiqueta."

## 12. Resumen (7:40 a 8:10)

VOZ: "Una etiqueta tiene apertura y cierre. Head configura y body muestra. Y los atributos dan datos extra."

## 13. Reto final (8:10 a 8:40)

VOZ: "Tu reto: crea la página de tu serie o videojuego favorito. Un h1 con el nombre, dos h2 con secciones y un párrafo en cada una. En el siguiente nivel agregas listas, imágenes y enlaces."
