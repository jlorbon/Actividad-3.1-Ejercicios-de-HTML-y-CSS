Jesús Lorenzo Bonilla - jlorbon332

Ejercicio 11
 Etiquetas
 Las únicas etiquetas de bloque utilizadas son <h1>, <p> y <div>.
 Clases
 Cada cita tiene la letra inicial diferente al resto del párrafo. Se podría utilizar una etiqueta
 <span> con clase, pero puesto que se trata del primer carácter, se puede utilizar
 simplemente el pseudo-elemento ::first-letter, que no requiere añadir nada al código
 fuente html.
 Posicionamiento
 Los párrafos tienen forma cuadrada y tienen todos el mismo tamaño, independientemente
 del contenido, lo que se puede conseguir dando el mismo valor a las propiedades width y
 height.
 Las citas se muestran una al lado de la otra formando una trama rectangular. Además, al
 hacer zoom o al estrechar o ensanchar la ventana, el número de citas por fila se ajusta
 automáticamente. Eso se puede conseguir con posicionamiento flotante.
 Si el tamaño del párrafo es suficientemente grande, no es necesario definir la propiedad
 overflow, aunque por precaución se puede incluir en la hoja de estilo.
 Como no hay ningún elemento después de las citas, no hace falta utilizar la propiedad clear
 en ningún elemento.
 La letra inicial de cada párrafo (pseudo-elemento ::first-letter) tiene posicionamiento
 flotante.
 Estilos
 ● Página (body):
 ○ color de fondo: background-color (#33e7ff)
 ○ tipo de letra: font-family (sans-serif)
 ● Título principal (h1):
 ○ margen: margin
 ○ color: color (#005a66)
 ○ tamaño de letra: font-size (4rem)
 ○ separación de letras: letter-spacing (2rem)
 ○ alineación: text-align
 ○ mayúsculas: text-transform
 ● Párrafo (p):
 ○ posicionamiento flotante: float
 ○ ancho: width (16rem)
 ○ alto: height (16rem)
 ○ visibilidad de elementos que no caben: overflow
 ○ borde: border (5px #005a66)
 ○ margen: margin (10px)
 ○ margen interior: padding (10px)
 ○ color de fondo: background-color (#00b4cc)
 ○ tamaño de letra: font-size (1.5rem)
 ○ cursivas: font-style
 ● primer carácter del párrafo (p::first-letter):
 ○ posicionamiento flotante: float
 ○ color: color (#005a66)
 ○ tamañ ode letra: font-size
 ○ cursivas: font-style (5rem)
 ○ interlineado: line-height (3rem)