# Nivel 6: Consejos y próximos pasos (guion previsto de 10 min)

Editor para la práctica: CodePen. El video muestra el error en una diapositiva. El Pen incluye el CSS con el error y este HTML de prueba:

```html
<h1>Mi página</h1>
<p>Texto de prueba.</p>
```

En este nivel el editor también sirve para mostrar errores a propósito. Pruébalos antes de grabar para confirmar que se ven como se describe aquí.

## 1. Portada (0:00 a 0:10)

PANTALLA: portada del nivel 6 con el ícono del cohete.

VOZ: "Nivel 6, el último. Hoy aprendes a corregir errores y a seguir creciendo como desarrollador o desarrolladora web."

## 2. Pregunta gancho (0:10 a 0:35)

PANTALLA: "Tu página no se ve como esperabas. ¿Qué haces?".

VOZ: "Escribiste tu código y la página no se ve como esperabas. ¿Qué haces? Los profesionales también se equivocan a diario. Lo importante es saber encontrar el error."

## 3. Misión (0:35 a 1:00)

PANTALLA: "MISIÓN 06".

VOZ: "Tu misión: reconocer errores comunes, revisar tu código con calma y planear tus próximos pasos. La recompensa: el superpoder de depurar, que significa encontrar y corregir errores."

## 4. Tres errores comunes (1:00 a 2:20)

PANTALLA: tres tarjetas: Falta cerrar (etiqueta sin cierre), Falta ; o } (CSS incompleto), Ruta mala (la imagen no aparece).

EDITOR (demostración rápida):

En el panel HTML escribe `<h1>`Mi página sin la etiqueta de cierre, y debajo `<p>`Texto de prueba.`</p>`. El párrafo se ve del tamaño del título. Agrega `</h1>` y vuelve a la normalidad.

Escribe una imagen con el src mal escrito: no aparece y se ve el texto alt. Corrígelo.

VOZ: "Error uno: no cerrar una etiqueta. Mira: el párrafo se ve enorme porque quedó dentro del título. Error dos: una dirección de imagen mal escrita; la imagen no aparece, pero queda el texto alt. Y el tercero, el más común en CSS, lo vemos ahora."

## 5. Un error en el CSS (2:20 a 3:30)

PANTALLA: diapositiva con el código que falla (10 s) y corte al editor.

EDITOR: en el panel CSS escribe, sin el punto y coma tras tomato:

```css
h1 {
  color: tomato
  text-align: center;
}
```

La vista previa: el título no es tomate ni está centrado.

VOZ: "Aquí falta un punto y coma después de tomato. Sin él, el navegador no entiende esa instrucción y la ignora, junto con la siguiente. Mira: ni el color ni el centrado se aplican. Sin ningún mensaje de error: por eso hay que revisar con atención."

## 6. Arreglado (3:30 a 4:10)

EDITOR: agrega el punto y coma:

```css
h1 {
  color: tomato;
  text-align: center;
}
```

La vista previa muestra el título tomate y centrado.

VOZ: "Agrego el punto y coma y listo: color y centrado funcionan. Cada propiedad termina en punto y coma, y cada regla se cierra con su llave."

## 7. Inspecciona cualquier página (4:10 a 5:30)

PANTALLA: tres cajas: Clic derecho, Inspeccionar, Ver el HTML y el CSS.

EDITOR / NAVEGADOR:

Haz clic derecho sobre el título en la vista previa y elige Inspeccionar (o presiona F12).

Se abre el panel de herramientas con el HTML y el CSS de ese elemento.

Haz lo mismo en una página real, por ejemplo un sitio de documentación que se vea sencillo.

Cambia un color en el panel de estilos para mostrar que el cambio es solo temporal.

VOZ: "Con clic derecho e inspeccionar puedes ver cómo está hecha cualquier página del mundo. Aquí veo el HTML y el CSS de este título. Si cambio el color, solo cambia en mi pantalla, y desaparece al recargar. Es la mejor forma de aprender y de encontrar errores."

## 8. Buenas prácticas (5:30 a 6:30)

PANTALLA: tres tarjetas: Ordena, Describe, Valida.

VOZ: "Tres hábitos de quienes programan bien. Ordena: usa sangría para que tu código se lea fácil. Describe: escribe siempre alt en tus imágenes. Y valida: puedes revisar tu HTML con el validador de W3C."

EDITOR (opcional, 30 s): abre el validador de W3C, pega un código HTML completo y muestra el resultado.

## 9. Quiz (6:30 a 6:55)

PANTALLA: "Tu CSS no funciona. ¿Qué revisas primero?" con las opciones A: ; y }, B: Un computador nuevo, C: Borrar todo.

VOZ: "Tu CSS no funciona. ¿Qué revisas primero?" (4 segundos) "Respuesta: A, los puntos y coma y las llaves."

## 10. Pausa y tu turno (6:55 a 7:35)

PANTALLA: "PAUSA · TU TURNO".

VOZ: "Pausa el video. Quita un punto y coma a propósito, mira qué pasa, encuentra el error y arréglalo. Provocar errores quita el miedo."

## 11. ¿Y ahora qué? (7:35 a 8:30)

PANTALLA: tres tarjetas: Practica, Aprende, Comparte.

VOZ: "¿Y ahora qué? Practica con un reto pequeño cada semana. Aprende con la documentación web de MDN. Y comparte tu página con tus amigos. Los ejemplos resueltos están en la carpeta completed-examples del repositorio del curso."

## 12. Resumen (8:30 a 9:00)

VOZ: "Los errores se encuentran y se corrigen. Inspeccionar te muestra cómo se hace cualquier página. Y ordena, describe y valida tu código."

## 13. Reto final y cierre (9:00 a 9:30)

PANTALLA: tarjeta "Reto final" y luego "¡Curso completado!".

VOZ: "Tu reto: termina tu página de perfil, pruébala con un amigo y comparte tu creación. Pasaste de no saber qué es HTML a publicar tu propia página. Felicitaciones, completaste el curso."
