Jesús Lorenzo Bonilla - jlorbon332

Ejercicio 10
Etiquetas
 ● Una etiqueta de sección <h1> para el título.
 ● Varias etiquetas de párrafo <p>, una para cada cita.
 ● El nombre del escritor en el primer párrafo lleva la etiqueta <strong>.
 ● Los nombres de las obras se ven en cursiva. Podrían utilizarse etiquetas <em>, pero
 para este tipo de información es más adecuado el uso de la etiqueta <cite>, que
 también se ve en cursiva cuando no se aplica ninguna hoja de estilo.
 Clases
 En total, se necesitan tres clases de párrafo <p>:
 ● Clase intro: el párrafo de introducción, que tienen un margen izquierdo y derecho
 mayor que el resto.
 ● Clase latin: los párrafos en latín, que aparecen a la izquierda.
 ● Clase espanol: los párrafos en español, que aparecen a la derecha.
 Los tipos de letra son también diferentes en cada una de estas clases.
 Fuentes
 En este ejercicio se utilizará la regla-arroba @font-face, para enlazar las siguientes fuentes
 en nuestro propio ordenador:
 ● Título: Ribeye Marrow
 ● Citas en latín: Lobster
 ● Citas en español: Just Another Hand
 Estilos
 ● Fuentes web (@font-face)
 ○ nombre: font-family
 ○ ubicación: src
 ● Página (body):
 ○ color de fondo: background-color (#ccac4d)
 ● Título (h1):
 ○ tipo de letra: font-family
 ○ tamaño de letra: font-size (3rem)
 ○ separación entre caracteres: letter-spacing (1.5rem)
 ○ alineación: text-align
 ○ mayúsculas: text-transform
 ● Párrafo de introducción (p.intro):
 ○ márgenes izquierda y derecha: margin-left (30%), margin-right (30%)
 ○ tipo de letra: font-family
 ○ interlineado: line-height (200%)
 ○ alineación: text-align
 ● Nombre del autor (strong):
 ○ ninguna propiedad
 ● Obras(cite):
 ○ subrayado: text-decoration
 ● Citas en latín (p.latin):
 ○ margen: margin
 ○ tipo de letra: font-family
 ○ tamaño de letra: font-size (2.5rem)
 ● Citas en español (p.espanol):
 ○ margen: margin (arriba: 0, horizontal: 0, abajo: 3rem)
 ○ color: color
 ○ tipo de letra: font-family
 ○ tamaño de letra: font-size (3.5rem)
 ○ separación entre caracteres: letter-spacing (1px)
 ○ alineación: text-align