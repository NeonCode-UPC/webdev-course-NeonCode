# Nivel 5: Crea tu página de perfil (guion previsto de 15 min)

Video publicado: [Nivel 5 en YouTube · 7 min 25 s](https://youtu.be/fdP6gZyev0o). Los tiempos de este guion corresponden a la planificación original.

En la demostración se construye el perfil por pasos. Para practicar en CodePen, completa la plantilla de HTML y después personaliza los estilos en CSS.

## 1. Portada (0:00 a 0:10)

PANTALLA: portada del nivel 5 con el ícono de perfil.

VOZ: "Nivel 5. Hoy juntas todo lo que aprendiste para crear tu propia página de perfil."

## 2. Pregunta gancho (0:10 a 0:35)

PANTALLA: "¿Y si crearas tu propia página de perfil?".

VOZ: "¿Y si crearas tu propia página de perfil, con tu foto, tus hobbies y tu enlace favorito? Con lo que ya sabes, puedes. Vamos a construirla."

## 3. Misión (0:35 a 1:00)

PANTALLA: "MISIÓN 05".

VOZ: "Tu misión: armar la estructura con HTML, darle estilo con CSS y corregir errores. La recompensa: tu página de perfil."

## 4. Plan del proyecto (1:00 a 1:40)

PANTALLA: tres cajas: Paso 1 estructura HTML, Paso 2 estilo CSS, Paso 3 revisar y corregir.

VOZ: "Trabajamos como en un proyecto real: primero el contenido, después la decoración y al final revisamos. Empecemos con el HTML."

## 5. Paso 1: cabecera (1:40 a 3:20)

PANTALLA: diapositiva (10 s) y corte al editor.

EDITOR: en el panel HTML escribe:

```html
<h1>Ana Torres</h1>
<img src="https://picsum.photos/id/237/200/200"
     alt="Mi foto de perfil" class="foto">
<h2>Sobre mí</h2>
<p>Tengo 15 años y amo los videojuegos.</p>
```

La vista previa muestra el nombre, una foto y un párrafo, todavía sin estilo.

VOZ: "Empiezo con mi nombre en un h1. Luego mi foto con img, usando src y alt, y le pongo una clase llamada foto para darle estilo después. Sigo con un h2 y un párrafo para presentarme. Tú usa tu nombre y escribe lo que quieras contar de ti."

## 6. Paso 1: hobbies y enlace (3:20 a 4:50)

EDITOR: debajo de lo anterior, escribe:

```html
<h2>Mis hobbies</h2>
<ul>
  <li>Videojuegos</li>
  <li>Música</li>
  <li>Dibujar</li>
</ul>
<a href="https://developer.mozilla.org/es/">  Mi sitio favorito para aprender</a>
```

La vista previa muestra una lista y un enlace, todavía sin estilo.

VOZ: "Ahora una lista con mis hobbies, usando ul y li, y un enlace con a a mi sitio favorito. El contenido ya está completo. Se ve sencillo, pero toda la información está ahí. Ahora viene la parte divertida: el estilo."

## 7. Paso 2: base de la página (4:50 a 6:30)

EDITOR: en el panel CSS escribe:

```css
body {
  background-color: #f5f3ff;
  font-family: Arial, sans-serif;
  text-align: center;
}

h1 {
  color: #5b3fd6;
}
```

La página tiene fondo claro, todo centrado y el nombre en color morado.

VOZ: "Con body doy estilo a toda la página: un fondo claro, la fuente y el texto centrado. Y con h1 cambio solo el color del título. Mira cómo la página ya se ve distinta."

## 8. Paso 2: la foto (6:30 a 8:20)

EDITOR: debajo, escribe:

```css
.foto {
  width: 150px;
  border-radius: 50%;
  border: 4px solid #5b3fd6;
}
```

La foto se vuelve un círculo con borde morado. Cambia 50% por 0% para mostrar que vuelve a ser un cuadrado y devuélvelo a 50%.

VOZ: "El punto antes de foto elige la clase que le puse a la imagen. Width fija el ancho. Border-radius con 50 por ciento redondea las esquinas hasta volver la foto un círculo. Y border le pone un borde del mismo morado."

## 9. Paso 2: lista y enlace (8:20 a 9:50)

EDITOR: debajo, escribe:

```css
ul {
  list-style: none;
  padding: 0;
}

a {
  color: #5b3fd6;
}
```

La lista queda sin viñetas y el enlace en color morado.

VOZ: "Con list-style none quito las viñetas de la lista, y con a cambio el color del enlace para que combine con el resto. Y listo: ya tienes tu página de perfil."

## 10. Quiz: tu texto no cambia de color (9:50 a 10:20)

PANTALLA: opciones A: El selector y el punto y coma, B: Cambiar de navegador, C: Borrar todo el código.

VOZ: "Tu texto no cambia de color. ¿Qué revisas primero?" (5 segundos) "Respuesta: A. Casi siempre es el selector o un punto y coma que falta."

## 11. Pausa: tu proyecto (10:20 a 12:20)

PANTALLA: "PAUSA · TU TURNO".

VOZ: "Esta es una pausa larga, porque es el proyecto del curso. Crea tu propia página de perfil. Cambia los colores, escribe tus datos y agrega algo que sea solo tuyo."

## 12. Resumen (12:20 a 13:10)

VOZ: "HTML arma la estructura. CSS le da estilo. Y revisar errores es parte del proceso."

## 13. Reto final (13:10 a 15:00)

VOZ: "Tu reto: mejora tu perfil y compártelo. Agrega una sección llamada Mis metas, cambia la paleta de colores y comparte el enlace con un amigo. En el último nivel aprendes a corregir errores y a seguir aprendiendo."
