#Responsive Design Platzi

## ¿Qué es Responsive Design?

> Son todas las técnicas y patrones que usamos para adaptar nuestras aplicaciones web a la mayor cantidad de dispositivos.

## Motivación

* La adopción del móvil
* Múltiples tipos de pantalla
* Avances tecnológicos.
* Problemas con SEO y desarrollo en sitios
* Internet Móvil

## Patrones de Diseño

**Mostly Fluid**
    :  Cuadricula fluida autoajustable al tamaño de la pantalla, los elementos se desplazan hacía abajo en la medida que la pantalla se reduce.

Ejemplo: <http://www.antarcticstation.org/>

**Column Drop**
    : Es la Colocación de columnas de forma vertical, a medida que se va reduciendo la pantalla, las columnas va a tomar el 100% del espacio para adaptarse.

Ejemplo: <http://www.modernizr.com>

**Layout Shifter**
    : Es el reajuste del diseño del sitio de acuerdo al ancho de la pantalla, requiere diseños más pulidos y detallados.

Ejemplo: <http://foodsense.is/>

**Tiny Tweaks**
    : Pequeños cambios en el diseño, como ajustar el tamaño de la fuente, cambiar el tamaño de las imágenes o desplazar el contenido de diferentes maneras.

Ejemplo: <http://futurefriendlyweb.com/>

**Off Canvas**
    :  El contenido menos usado se coloca fuera de la pantalla y solo se muestra cuando el tamaño de la pantalla es lo suficientemente grande; en las pantallas más pequeñas, el contenido está solo a un clic de distancia.

Ejemplo: <https://getbootstrap.com/examples/offcanvas/>

## Consideraciones cómo Desarrolladores

A la hora de crear aplicaciones web responsive debemos tener claros los siguientes conceptos:

1.  Para Smartphone trabajar en Portrait - Landscape (En vertical, en horizontal)
2. Viewport (área visible del navegador) [Ver los diferentes tamaños](http://viewportsize.com/)
3. Unidades de Medida **absolutas** y **relativas**
    - **Absolutas**
       - Pixeles _px_
    - **Relativas**
       - Porcentaje = _%_
       - Altura de Fuente = _em_ - Root-em = _rem_
       - Viewport Height = _vh_ - Viewport Width = _vw_
4. Retina Display - Densidad de Pixel.
5. Touch Events.
6. Estrategias
    - Graceful Degradation (Desktop First)
    - Progressive Enhancement (Mobile Fisrt)
7. Que el sitio cargue rápido.