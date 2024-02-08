## Hoja de estilo del catálogo: style2.css

*{

margin:0;

padding: 0;

font-family:Verdana, Geneva, Tahoma, sans-serif;

}

Da margen y padding de 0 a todo el documento, además de darle la fuente de Verdana.

.container{

display: grid;

height: auto;

width: 100vw;

margin: 0 auto;

border-color: black;

grid-template-rows: 70px 750px 800px 800px 800px 200px;

}

Al haber declarado grid al comienzo, se asigna el tamaño de las filas, se le dio un color negro al borde y un máximo de pantalla.

.cont-foto1:hover .foto-peque1{

background-image: url('/../images/foto1.png');

position: relative;

width: 550px;

height: 500px;

top:80px;

left:240px;

}

se llama a una imagen, se le coloca posición relativa con un top de 80px y un left de 240px.

y sus dimensiones las cuales son 550x500px.

nav ul{

 position: relative;

 width: 350;

 height: 300px;

 background: coral;

 top: 23px;

 left: -160%;

 display: block;

 z-index: 1;

 text-align: center;

 transition: all 0.5s;

 overflow-y: scroll;

 scroll-behavior: smooth;

}

Se le asigna una posición relativa de top:23px y left -160px. el z-index hace que la imagen se coloque encima de las otras que estén abajo. Se alineó el texto centrado. la transition durará 0.5s. scroll es para que hubiera una barra lateral con la cual se pueda hacer scroll.

.descripcion-pro{

 padding-top: 10%;

 grid-column-start: 1;

 grid-column-end: 3;

 padding: 0px;

 text-align: justify;

}

En la descripción de los productos se le dio un padding-top de 10%. El contenedor va a ocupar la fila 3 y columna 1. Tendrá un padding de 0 y el párrafo estará justificado.