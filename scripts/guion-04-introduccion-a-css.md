# Nivel 4: Introducción a CSS

## Locución del video

- **00:00 a 00:06** — Nivel cuatro. Hoy le das estilo a tu página con CSS.
- **00:06 a 00:16.3** — ¿Cómo haces que tu página se vea como tú quieres? Con CSS cambias colores, fuentes y diseño. Vamos a probarlo.
- **00:16.3 a 00:27.7** — Tu misión: entender una regla CSS, cambiar colores y fuentes, y centrar y poner bordes. La recompensa: una página con estilo propio.
- **00:27.7 a 00:42** — Una regla de CSS tiene tres partes. El selector dice a quién quiero cambiar: aquí, a los títulos h1. La propiedad dice qué voy a cambiar: el color.
- **00:42 a 00:55** — Y el valor dice cómo queda: tomato. Todo va entre llaves, separado con dos puntos, y recuerda terminar siempre cada línea con un punto y coma.
- **00:55 a 01:11.3** — Para que el CSS funcione, hay que conectarlo con el HTML. En una página normal se hace con la etiqueta link. Pero en CodePen no hace falta: el panel CSS ya está conectado.
- **01:11.3 a 01:22.7** — Empecemos cambiando el color del título h1. El selector h1 elige todos los títulos principales y terminamos cada línea con punto y coma.
- **01:22.7 a 01:34.8** — Ya en CodePen tenemos el HTML listo arriba y el panel CSS vacío debajo. Hago clic en CSS y escribo: selector h1, abro llaves.
- **01:34.8 a 01:46.9** — Adentro pongo propiedad color, dos puntos, valor tomato, y punto y coma al final. Mira la vista previa a la derecha: cambia al instante.
- **01:46.9 a 01:58.3** — Si cambio tomato por dodgerblue, se pinta de azul al momento. Lo dejamos en tomato, verificando siempre el punto y coma, y seguimos.
- **01:58.3 a 02:10.2** — Ahora vamos con el fondo y la fuente de toda la página. Con body elegimos el fondo, el color del texto y la tipografía.
- **02:10.2 a 02:23.4** — Debajo de la regla del h1, escribo body. Agrego background-color con el código uno a cero b tres b, y todo el fondo se vuelve morado oscuro.
- **02:23.4 a 02:37** — Después ponemos color: white; para que el texto se lea en blanco, y font-family: Arial, sans-serif; para cambiar la fuente. El título sigue en color tomate.
- **02:37 a 02:46.8** — Mira el cambio: una sola regla transforma toda la página. Ya tenemos fondo oscuro, texto blanco y tipografía limpia.
- **02:46.8 a 02:58.7** — Ahora centramos el título y le dibujamos un borde. Usaremos text-align center para centrar, border para el recuadro y padding para el aire interno.
- **02:58.7 a 03:11.8** — Dentro de la regla del h1 que ya tenemos, agregamos debajo de color: text-align: center;, border: tres px solid tomato;, y padding: diez px;.
- **03:11.8 a 03:24.1** — Fíjate: text-align center centra el texto. Border dibuja un recuadro con grosor, tipo de línea y color. Y padding le da aire por dentro.
- **03:24.1 a 03:36.4** — Si cambio tres px por ocho px y diez px por treinta px, el recuadro se agranda al instante. Volvamos a tres y diez píxeles.
- **03:36.4 a 03:48.3** — ¿Y si queremos resaltar solo un párrafo y no todos? Para eso usamos el atributo class, que le da un nombre propio al elemento.
- **03:48.3 a 04:00.8** — En el panel HTML, agregamos al final dos párrafos: el primero con class igual destacado y ¡Texto especial!, y debajo otro párrafo con Texto normal.
- **04:00.8 a 04:14.2** — Los dos párrafos se ven iguales por ahora. Es como un uniforme de equipo: solo quienes lo llevan se verán distintos cuando creemos su regla en CSS.
- **04:14.2 a 04:26.3** — Ahora vamos a darle estilo a esa clase en CSS. Recuerda dos reglas clave: el punto elige una clase y font-size cambia el tamaño.
- **04:26.3 a 04:40.3** — En el panel CSS agregamos punto destacado, abrimos llaves, y escribimos color: gold; junto con font-size: veinticuatro px;. Para elegir una clase usamos siempre el punto antes.
- **04:40.3 a 04:52.8** — Mira el resultado: solo el párrafo ¡Texto especial! cambia a dorado y más grande, mientras Texto normal y el primer saludo mantienen su estilo normal.
- **04:52.8 a 05:00.2** — Hagamos una prueba rápida. En esta regla, p, color blue, ¿cuál es el selector?
- **05:04.2 a 05:10.2** — Respuesta: la A, p, porque indica a qué elemento aplicamos estilo.
- **05:10.2 a 05:23.6** — Ahora es tu turno. Pausa el video. Cambia el fondo y el color del texto, centra el título y ponle un borde. Pista: body y h1.
- **05:28.6 a 05:41.3** — En resumen: una regla tiene selector, propiedad y valor. Color, fondo, fuente y borde cambian el estilo. Y las clases dan estilo a elementos específicos.
- **05:41.3 a 05:57** — Tu reto: dale una identidad visual a tu página. Elige dos colores y úsalos, centra el título y crea una clase nueva. En el siguiente nivel armas tu página de perfil.
