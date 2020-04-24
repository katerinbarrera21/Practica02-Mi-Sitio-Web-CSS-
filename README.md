# PRÁCTICA DE LABORATORIO
### CARRERA: COMPUTACIÓN ASIGNATURA: HIPERMEDIAL
### NRO. PRÁCTICA: 2 TÍTULO PRÁCTICA: Resolución de problemas sobre CSS
### OBJETIVO ALCANZADO:

- Entender y organizar de una mejor manera los sitios de web en Internet
- Diseñar adecuadamente elementos gráficos en sitios web en Internet.
- Crear sitios web aplicando estándares actuales.
### INSTRUCCIONES:

Se pide tomar como base el sitio web desarrollado en la práctica 01 - Creación de sitio web usando HTML5.
Luego, se pide utilizar estilos CSS con la finalidad de obtener varios diseños como los que se muestran en las
siguientes imágenes

###  ACTIVIDADES DESARROLLADAS
#### 1. En al menos una página HTML, un diseño a dos columnas con cabecera y pie de página, como el que se muestra en la Figura 2. Se pide tomar como base la página home.

![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/dosFig.JPG)
##### Figura 2. Diseño de un sitio web con base a dos columnas


#### 1.1. CABECERA
La cabecera de las paginas muestra imagen con el nombre correspondiente a cada página y también tiene un
menú horizontal con enlaces a las paginas internas del programa.
#### #nav{
#### height: 62 px;
#### background-color:rgb( 32 , 20 , 20 );
#### text-align: center;
#### position: relative;
#### }
#### #nav ul{
#### list-style: none;
#### display: inline-block;
#### }
#### nav ul li{
#### float: left;
#### margin-top: 20 px;
#### }
#### #nav ul li a {
#### color: white;
#### font-weight: bold;
#### text-decoration: none;
#### font-size: 20 px;
#### padding: 20 px;
#### }
#### #nav ul li a:hover{
#### background-color: red;
#### }

#### 1.2. MENÚ
En esta sección se colocó información relevante para cada página debido a que el menú principal ya existía
en la página de forma horizontal.
Importante: Se creo una sección principal que contiene a las dos secciones secundarias:
#### .seccionContenidoTotal {
#### width: 100 %;
#### height: 1000 px;
#### background-color: rgb( 255 , 255 , 255 );
#### position: relative; 
#### }

EL selector por clase. secContenido es la parte que ocupa nuestro “menú” con respecto a la sección principal
#### .secContenido {
#### width: 46 %;
#### height: 100 %;
#### position: relative;
#### float: left;
#### background-color: rgb( 229 , 226 , 226 );
#### padding: 70 px 50 px 70 px 50 px;
#### }

####  1.3. CONTENIDOS
El selector por clase secContendio2 es la parte que ocupara nuestro contenido con respecto a la sección
principal
#### .secContenido2 {
#### width: 40 %;
#### height: 1000 px;
#### position: relative;
#### float: left;
#### background-color: rgb( 255 , 255 , 255 );
#### padding: 50 px 50 px 50 px 50 px;
#### }

#### 1.4. PIE DE PÁGINA
El pie de pagina se ubica con una etiqueta footer al final de nuestro documento html. Y esta estructurado de
manera similar a la siguiente forma y colocado en todas las paginas igual.
El footer principal que contiene todos los elementos esta estructurado de la siguiente forma:

#### .foot {
#### width: 100 %;
#### height: 200 px;
#### position: relative;
#### background-color: black;
#### }
Luego tenemos la parte izquierda de nuestro footer que es en este caso redes sociales, el ocupara solo el 30%
del ancho total que tiene el footer principal.

#### #redes {
#### width: 30 %;
#### height: 100 %;
#### float: left;
#### background-color: black;
#### }

#### .redesS {
#### width: 100 %;
#### height: 23 %;
#### float: right;
#### position: relative;
#### background-color: black;
#### }


Luego tenemos la parte de la mitad de nuestro footer que es en este tiene información sobre nosotros como
empresa. Se utilizo un id para identificar a esta parte que ocupa el 30% de nuestro footer principal.

#### #nos{
#### width: 30 %;
#### height: 100 %;
#### float: left;
#### color: rgb( 10 , 0 , 0 );
#### background: currentColor;
#### margin-left: 40 px;
#### margin-right: 40 px;
#### }


Luego tenemos la parte derecha de nuestro footer que es en este tiene información sobre alguna ayuda que
pueda ofrecer nuestro servicio. Se utilizo un id para identificar a esta parte que ocupa el 30% de nuestro footer
principal.

#### #ayu{
#### width: 30 %;
#### height: 100 %;
#### float: left;
#### background-color: black;
#### }

### 2. Así, como también se recomienda utilizar, en al menos una página HTML, un diseño a tres columnas concabecera y pie de página como se muestra en la Figura 3. Se pide tomar como base la página home.
### Importante: La cabecera y el pie de página serán iguales para cualquier tipo de diseño, ya se de dos columnas o de tres en este trabajo.
![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/tresFig.JPG)

##### Figura 3. Diseño de un sitio web con base a tres columnas

#### 1.1. Menú
 Al igual que el anterior caso se crea una sección principal que contiene tanto el menu, el contenido y el lateral
 para luego subdividir para que puede tener el diseño deseado.
 
#### .seccionContenidoTotal3 {
#### width: 100 %;
#### height: 800 px;
#### background-color: rgb( 250 , 250 , 250 );
#### position: relative;
####  }
El selector por clase columna 1 ocupa el 10% del ancho de toda nuestra sección principal.
Se dibujan los bordes y se utiliza float:left para ir ubicando estas sub sección una tras otra.
####  .columna1 {
####  width: 10 %;
####  height: 100 %;;
####  border-style: solid;
####  border: 1 px;
####  position: relative;
####  float: left;
####  background-color: rgb( 209 , 205 , 205 );
####  padding: 50 px 50 px 50 px 50 px;
####  }

####  1.2. Contenidos
El selector columna2 hace referencia al contenido y es el mas ancho debido que en esta parte estará lo mas
relevante para la página.
####  .columna2{
####  width: 50 %;
####  height: 100 %;
####  border-style: solid;
####  border: 1 px;
####  position: relative;
####  float: left;
####  background-color: rgb( 253 , 251 , 251 );
####  padding: 50 px 50 px 50 px 50 px;
####  }
1.3. Lateral
El selector por clase columna 3 hace referencia al contenido y es menos ancho que nuestro contenido.
####  .columna3 {
####  width: 20 %;
####  height: 100 %;
####  border-style: solid;
####  border: 1 px;
####  position: relative;
####  float: left;
####  background-color: rgb( 245 , 241 , 241 );
####  padding: 50 px 50 px 50 px 50 px;
####  }

###  2. De igual manera, se pide que se organice en al menos cuatro archivos CSS los estilos para las diferentes páginas html, estos archivos estarán almacenados en una carpeta llamada css. Un archivo será para el diseño a dos columnas, otro archivo para el diseño a tres columnas, otro archivo para el diseño de la página home. Por último, un archivo para la regla CSS relacionas a textos, colores, tablas, secciones, artículos, imágenes, etc.
![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/carpeta.JPG)
###  1. Contenido de configuración
####  Se mostrará partes del código especificas debido a que el archivo es muy extenso.
####  Para el logo:
Se crea una sección general de logo la cual se divide en tres secciones la primera que será para la imagen del logo, la segunda para el buscador principal y la tercera parte es para las opciones de usuario, para los iconos de acceder, correo y agregar.
Para la seccion logo 

####  .logo{
####  width: 100 %;
####  height: 150 px;
####  position: relative;
####  }
####  .separarLogo {
####  width: 10 %;
####  height: 100 %;
####  float: left;
####  background-color: #020000;
####  }

Para la seccion buscar 

####  .separarBuscar{
####  width: 70 %;
####  height: 100 %;
####  float: left;
####  }

Para la seccion de opciones de usuario 

####  .separarUsuario {
####  width: 20 %;
####  height: 100 %;
####  float: left;
####  background-color: #020000;
####  }

1.1. Para la parte de separar logo, se crea un contenedor que tendrá todo la extensión del usuario. Con el selector de clase botón Acceder, lo vamos a implementar en los tres botones, acceder, correo y agregar de forma que todos tienen el mismo porcentaje.

####  .separarUsuario .opcionesUsuairo{
####  width: 20 %;
####  height: 100 %;
####  float: left;
####  background-color: #ffffff;
####  }
####  _/*contendor mas pequenio con cada uno */_
####  .separarUsuario .containerUsuario {
####  width: 100 %;
####  }

####  .separarUsuario .containerUsuario .btnAcceder{
####  margin-left: 2 %;
####  width: 26 %;
####  margin-right: 2 %;
####  color: #ff0505;
####  float: left;
####  font-size: 15 px;
####  margin-top: 5 %;
####  /* border-style: outset; */
####  /* border-color: #f7f7f7; */
####  text-align: center;
####  /* background-color: #dddddd; */
####  }

###    2. Contenido de formularios
 Se crea el selector de clase principal como bloque, con un acho de 510px
 
####  .principal {
####  display:block;
####  margin: 0 auto;
####  width: 510 px;
####  color: #d8d7d7;
####  font-family:Arial;
####  }

la etiqueta sección, en la que se encuentra nuestra etiqueta form tiene la siguiente configuración

####  section{
####  margin-left: 450 px;
####  margin-right: 450 px;
####  margin-bottom: 100 px;
####  }

Para la etiqueta form se agrega un acho de 400px
####  form {
####  margin: 0 auto;
####  width: 400 px;
####  }

La configuración de la etiqueta a, el hipervínculo que existe en ese formulario, que es para regresar a nuestra
pagina index.html

####  a:link {
####  color: rgb( 224 , 245 , 38 );
####  }
####  _/* muestra en gris los links visitados */_
####  a:visited {
####  color:rgb( 177 , 14 , 14 );
####  }
####  _/* muestra en rojo los links en hover */_
####  a:hover {
####  color:rgb( 56 , 199 , 0 );
####  }
####  _/* muestra en rojo claro los links activos */_
####  a:active {
####  color:rgb( 243 , 1 , 211 );
####  }

###  3. Contenido de textos
3.1. Importación de algunas fuentes que se utilizaron en la pagina web.
####  @import url( _"https://fonts.googleapis.com/css2?family=Pacifico"_ );
####  @import url( _'https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Parisienne&display=swap'_ );
####  @import url( _'https://fonts.googleapis.com/css2?family=Prata&display=swap'_ );
3.2. Configuración de etiquetas h

####  h1 {
####  font-size: 50 px;
####  color:rgb( 46 , 6 , 6 );
####  font-family: _'Times New Roman'_ , Times, serif;
####  text-transform: uppercase;
####  }

####  h2 {
####  font-size: 30 px;
####  margin-top: 20 px;
####  margin-bottom: 20 px;
####  color: rgb( 255 , 255 , 255 );
####  font-family: Prata;
####  font-weight: lighter;
####  font-style: normal;
####  fill-opacity: inherit;
####  }

####  h4 {
####  color: white;
####  font-size: 100 %;
####  font-family: Georgia, _'Times New Roman'_ , Times, serif;
####  }

####  h7 {
####  color:rgb( 46 , 6 , 6 );
####  font-family: _'Times New Roman'_ , Times, serif;
####  text-align: center;
####  }

####  h6 {
####  color:rgb( 46 , 6 , 6 );
####  font-family: _'Times New Roman'_ , Times, serif;
####  text-align: center;
####  }

3.3. Utilizamos un selector de clase para los atributos como centrar o justificar un texto

####  .centrado{
####  text-align:center;
####  width: 100 %;
####  float: left;
####  }
####  .justificado {
####  text-align: justify;
####  }

3.4. El selector separador es útil para cuando vamos a cambiar de sección y se debe volver a calcular los
porcentajes de división.

####  .separador{
####  width: 100 %;
####  background-color: rgb( 26 , 2 , 2 );
####  clear: both;
####  }

### 4.Utilice selectores por etiquetas, selectores descendentes, selectores por clase y selectores por id.
####  Se mostraran algunos ejemplos de partes en los que se utilizaron estos selectores.

1. Por etiquetas
    Solo para la etiqueta a hiperviculo
    
####  a {
####  list-style: none;
####  color:rgb( 250 , 249 , 249 );
####  text-align: center;
####  font-size: 30 px;
####  font-family: initiaL ;
####  }

2. Selectores descendentes
Se aplica solo para el hipervínculo que esta dentro de la etiqueta li que a su vez esta dentro de la etiqueta
ul y debe haber utilizado un id nav.

####  #nav ul li a:hover{
####  background-color: red;
####  }

3. Por clase

Utilizado por lo general en la pagina web para darle el fondo a toda la pagina y luego sobreponer las
siguientes secciones.

####  .fondoEntero{
####  width: 100 %;
####  height: 100 %;
####  background-color: black;
####  position: relative;
####  }

4. Por id
 Para la etiqueta nav se creo un id #nav, que atributos que se van aplicar solo cuando la etiqueta tenga el  id #nav
 
####  #nav{
####  height: 62 px;
####  background-color:rgb( 32 , 20 , 20 );
####  text-align: center;
####  position: relative;
####  }

5. También, se pide que se cree un menú horizontal (navegación) para todas las páginas. Como se puede
observar en la Figura 1.
Con este código se crea el menu que tiene un fondo rojo, un ancho de 100% de la pagina y un alto de 62px.
Se elimina el estilo por defecto con list-style:none
Tenemos un margen top de 20px para que las opciones que vamos a poner en el menú se vean alineados y
estéticos.

####  #nav{
####  height: 62 px;
####  background-color:rgb( 32 , 20 , 20 );
####  text-align: center;
####  position: relative;
####  }

####  #nav ul{
####  list-style: none;
####  display: inline-block;
####  }

####  #nav ul li{
####  float: left;
####  margin-top: 20 px;
####  }

####  #nav ul li a {
####  color: white;
####  font-weight: bold;
####  text-decoration: none;
####  font-size: 20 px;
####  padding: 20 px;
####  }

####  #nav ul li a:hover{
####  background-color: red;
####  }

###  6. La evidencia de la validación de cada página HTML.
###    1. ANIME
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/animeVal.JPG)
###    2. COMIDA
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/comidaVal.JPG)
###    3.FORMULARIO
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/formularioVal.JPG)
###    4.INDEX
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/indexVal.JPG)
###    5.SOBRE JAPON
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/sobreJaponVal.JPG)
###    6.LUGARES
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/lugaresVal.JPG)
###    7.MUSEO DIGITAL
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/museoDitalVal.JPG)
###    8.MUSICA
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/musicaVal.JPG)
###    9.TRADICIONES
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/tradicionVal.JPG)


###  7. La evidencia de la validación de cada página css.
El programa emite tres errores, debido a que espera un documento html.
###    1. Configuración.css
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/configuracionVal.JPG)
###    2. Diseño de dos columnas.css
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/dosColumnasVal.JPG)
###    3. Diseño de tres columnas.css
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/tresColumnasVal.JPG)
###    4. Estrellas.css
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/estrellasVal.JPG)
###    5. Textos.css
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/textoVal.JPG)
###    6. Formulario.css
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/formularioCSSVal.JPG)

###  RESULTADO(S) OBTENIDO(S):
Se va mostrar como quedaron la paginas después de haber aplicados css sobre cada una de ellas.
1.1. INDEX

### FORMULARIO
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/formulario.JPG)
### INDEX
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/index.JPG)
### ANIME
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/anime.JPG)
### COMIDA
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/comida.JPG)
### SOBRE JAPON
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/3Columnas.JPG)
### LUGARES
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/lugares.JPG)
### MUSEO DIGITAL
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/museo.JPG)
### MUSICA
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/musica.JPG)
### TRADICIONES
   ![](https://github.com/katerinbarrera21/Practica02-Mi-Sitio-Web-CSS-/blob/master/Imagenes/readme/tradiciones.JPG)

####  CONCLUSIONES:
Se realizo la practica con éxito. Las paginas fueron mejoradas con el código de css.
Se siguieron los estándares predeterminados por el docente.
Se realizaron las paginas con el fin de llamar la atención de un cliente en un futuro, las paginas pueden ser
mejoras.
Se reforzaron los conocimientos adquiridos durante las clases.
