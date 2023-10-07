# App
FUNDAMENTOS DE LA PROGRAMACION WEB

WIREFRAME - mockup
https://wireframe.cc/hvFPas


![Descripción de la imagen](/public/imagen/Myblog.png)

# EJERCICIO 1
### A partir de la página web que se te proporciona, debes emplear el atributo style para crear una página web que tenga el mismo aspecto que la siguiente imagen:

Tienes que tener en cuenta los siguientes requisitos
* Texto Principal <main>
  * El color del texto es azul: #00F.
  * El color de fondo de la etiqueta <main></main> es verde claro: #CFC.
  * El tipo de letra es la secuencia: Georgia, 'Times New Roman', Times, serif;
  * El tamaño del texto: 16px.
  * Tiene un tamaño de alto de la caja: min-height: 80vh;
* El imagen principal
  * El ancho de la imagen es: 50%
  * El alto de la imagen es: 50%
  * Para poder poner la imagen el centro utilizamos: display: block; margin: 0 auto;
* El encabezado nivel 1
  * El color del texto es rojo claro: #F00.
  * El tipo de letra es la secuencia: Verdana, Calibri, sans-serif.
  * El tamaño del texto: 32px.
* El encabezado nivel 2
  * El color del texto es rojo claro: #A00.
  * El tipo de letra es la secuencia: Verdana, Calibri, sans-serif.
  * El tamaño del texto: 24px.
* El color de los campos de los "Datos del libro" es verde oscuro: #060.
* El texto "Internet" y la "Web" cuando actúan como sustantivos:
  * El tamaño del texto: 20px.
  * Color del texto blanco: color:white.
  * Texto en negrita - "font-weight:bold".
  * El color del fondo es: #6b6060;
* El texto "Hypertext Markup Language", "Cascading Style Sheets" y los acrónimos "HTML" y "CSS":
  * Utiliza etiqueta <em>
  * El color del texto es blanco: #FFF.
  * El color de fondo del texto es negro: #000.
  * Texto en cursiva.
    
Consejo: puedes utilizar la etiqueta de HTML <span> para aplicar un estilo CSS a cualquier parte del texto.

```
<main>
        <div class="contenedor-main">
            <div class="">
                <img src="https://i.ytimg.com/vi/rr2H086z16s/maxresdefault.jpg" alt="Imagenes de CSS y HTML">
            </div>
            <hr>
            <h1 class="titlePrincipal">HTML &amp; CSS: Curso práctico avanzado</h1>
            <h2 class="subTitulos">Datos del libro</h2>
            <ol class="datLista">
                <li><span>Título:</span></li>
                <li><span>Autor:</span></li>
                <li><span>Editorial:</span></li>
                <li><span>Año de publicación:</span></li>
                <li><span>ISBN:</span></li>
            </ol>
            <h2 class="subTitulos">Descripción del libro</h2>
            <p></p>
            <p></p>
            <h2 class="subTitulos">Contenido del libro</h2>
            <p></p>
            <ul>
                <li><em>HTML</em></li>
                <li></li>
                <li></li>
            </ul>
        </div>
        <div class="box-model">
            <div class="caja1">
                    GABRIEL OJITOS LANDA
            </div>
        </div>
        </div>
</main>
```
