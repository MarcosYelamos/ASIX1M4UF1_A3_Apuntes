# ASIX1M4UF1_A3_Apuntes

Tercer repositorio de ASIX1 2324
Confirmación de lo que sabemos

## Primer cápitulo: MARKDOWN7 (SUBTITULO)

(#) Esto sirve para poner encabezados, hay 6 niveles como en HTML, al poner este encabezado te pone un enlace en el título.


### Poner texto en negrita y en cursiva (todas las formas):

Este texto esta en *cursiva*- * *

Este texto esta en _cursiva_. _ _

Este texto esta en __negrita__. __ __

Este texto esta en **negrita**. ** **

Este texto esta en **_negrita y cursiva_**. ** _ _ ** 

Este texto esta en __*negrita y cursiva*__. __ * * __


1. Primera opción de menu. Esto es una lista ordenada.
2. Segunda opción de menu.
3. Tercera opción de menu.

(La lista desordenada se hace con el - y con *)
* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primera submenú 
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú
    * Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

Hay que dejar un espacio en blanco para que siga en otra linea 

``` 
Las tres tildes(```) sirven para encuadrar.
<html>
    <head> 
    </head>
    <body>
        <p>Esto es un parrrafo</p>
    </body>
</html>
```

[Esto es un enlace](https://www.google.com/url?sa=i&url=https%3A%2F%2Finhispania.com%2Fes%2F15-formas-de-decir-si-sin-decir-si%2F&psig=AOvVaw19IUwh4EM0mAYLZhS421Tp&ust=1696059558183000&source=images&cd=vfe&opi=89978449&ved=0CA8QjRxqFwoTCOik266oz4EDFQAAAAAdAAAAABAD "Enlace a si")

![Esto es una foto](https://inhispania.com/wp-content/uploads/2021/05/1.jpg "Esto es un foton de si")

|Primera Col.|Segnda Col.|3 Col|
|---------------|:------------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX1|M4|

-[ ]Opción A

-[X]Opción B

-[ ]Opción C

## Segundo cápitulo: HTML
```
Etiquetas de apertura y cierre.
apertura --> <p>(contenido visible)</p> <-- cierre

Todo el parrafo incluyendo las etiquets se llama elemento
<p class "valor"> texto a mosrar </p>

Anidar etiquetas: Meter una etiqueta dentro de otra
<p> balala <strong> negrita </strong> adadada <p>

El texto que esta en storng estara en negrita y lo demas no, todo en conjunto sera un parrrafo.

<img href="./imagen">
Para añadir una imagen

<br> --> para dejar un espacio en blanco entre lineas.
```

Hay que especificar el lenguaje que se va a utlizar cuando abrimos un nuevo archivo.

Partes de un documento HTML
Etiqueta por la cual le de

html:5 para añadir al archivo las partes de un documento html.


```
<!DOCTYPE html> (Le decimos al docuemnto que tipo de documento es)

<html lang="en"> Inicio, se vaa poner el codigo a partir de aqui.

</html> Es el cierre de la etiqueta anterior. Despues de esta etiuqeta no se pone codigo.

encabezado --> <head> </head> (Va al principio de la pagina es la parte donde definimos las caracetristicas de la pagina y donde metemos todo el contenido no visible por los visitantes. Enlaces)


<meta charset="UTF-8"> que set de caracteres tiene que cojer la pagina, en este caso coje el que utilizamos, con la ñ añadida por ejemplo.

<meta name="viewport" content="width=device-width, initial-scale=1.0"> Como se ve a ver el ancho de la pantalla.

<title>Document</title> Es el titulo de la pagina. en la pestaña del navegador se vera lo quese ponga

<favicon> para definir el icono de la pagina web que  s eve arriba en la pestaña del navegador.

cuerpo --> <body> </body>
```

Hay dos categorias de etiuqteas:

Etiquetas de bloque: Cuando se caba de renderizar el contenido de etiqueta deja un espacio de linea. Ej: las etiquetas de titulo, parrafo, listas, tablas.

Etiquetas de linea: Cuando se acaba de renderizar la etiqueta __NO__ hace un salto de linea.

```
h1 --> encabezado, tiene 6 niveles, cambian segun el numero, el 1 es el mas grande.

ol --> Lista ordenada
    li --> va dentro de la lista ordenada para definir cada elemento.
Ej:
<ol>
    <li>Primer elemento</li>
    <li>Segundo elemento</li>
    <li>Tercer elemento</li>
</ol>

ul --> Lista desordenada, lo mismo que la orenadda pero que con u.
Ej:
<ul>
    <li>Primer elemento</li>
    <li>Segundo elemento</li>
    <li>Tercer elemento</li>
</ul>

Tambien se pueden meter listas dentro de otras
Ej:
<ol>
    <li>Primer elemento de nvl 1</li>
    <ul>
        <li>Primer elemento de nivel 2</li>
        <li>Segundo elemento de nivel 2</li>
        <li>Tercer elemento de nivel 2</li>
    </ul>
    <li>Segundo elemento de nvl 1</li>
    <li>Tercer elemento de nvl 1</li>
</ol>

<a href=""></a> --> para hacer links, en href se pone el link de la ruta donde se quiere llegar.
Ej:
<a href="http://google.com" alt ="Texto alternativo" target="_blank">Este es el enlace a google</a>

alt: es el texto alternativo que sale cuand pasas por encima.

target blank: abre una pestaña nueva con el enlace

blockquote --> para poner una cita, te lo escribe a la derecha un poco, el texto.

<!-- Ajajajajajajajaj esto es un coemntario--> --> esto es para poner comentarios jajajajajaja.
Siempre comentar los codigos que escribamos.

<img src="" alt=""> --> para poner -> las imagenes, en src se pone el encale o la ruta y el alt es el texto alternativo. Los nombres de laas imaganes que  no tengan espacios.

<strong> para poner en negrita u texto y <u> para subrayarlo.
```

<br>

## Font awesome
Rellenar con lo de script para poder poner los iconos de Font Awsome. Una vez copiado el script en la cabecera solo habra que copiar el codigo del icono y saldria por pantalla.

<br>

## Estructura de los contenidos

Carpetas para cada tipo de elementos, comouna carpeta img para las fotos, otra para audios...
. --> indica el sitio deonde te encuentras, es decir en el mismo sitio donde estas.
.. Tira para atras, es decir va a la carpeta anterior.
Ej: ./imagenes/planeta.jpg 
.  es la carpeta actual
imagenes es a la primera carpeta a al que nos dirigimos y ./planeta.jpg es el archivo que elegimmos (en este caso una foto).

<br>

## Identificador

```
<h3 id="tercera">Tercera seccion</h3> --> para añadir un identificador y asi por ejemplo poder hacer un elnace a u titulo.
para ir a un titulo y no cambiar a otra pagina hay que añadir anttes del la ruta un #.

```


## Pages

Para hacer que un repositorio de github se transforme en pagina web iremso a configuracion (settings) en el menu de la izqeuirda pages.
Seleccionamos la rama(Branch) Main y le damos a guardar (save)
## HTML tabla
Como se hace una tabla en HTML?

Con la etiqueta <Table>, <Thead>, tbody y <Tfoot>

border es para ponerle borde a la tabla.
<table border="1"> 
        <thead>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1r</td>
                <td>Juan</td>
                <td>2:00</td>
            </tr>
            <tr>
                <td>2rd</td>
                <td>Juan</td>
                <td>3:00</td>
            </tr>
            <tr>
                <td>3th</td>
                <td>Pepe</td>
                <td>4:00</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </tfoot>
</table>
<br>



## Tercer capítulo: CSS

Para organizar y estilar las paginas.
Dos opciones:
Meter directamente el css en la etiqueta, en el head o en un archivo externo enlacado con la página.

Directamente en la etiqueta cuando solamente quereemos afectar a un elemnto en concreto.
EN el head de la pagina para que todos los elementos de un mismo tipo como por ejemplo h5 se pudean estilar.
Y en el archivo externo para cuando se va a utilizar para afectar a todas las paginas del sitio web.
Interno en la misa pagina web, externo uando esta en otra página.

Prioridad: 3. El css de la pagina externa, 2. el css de el head de la pagina, 1. El css en la propia etiqueta
si pusieramos 

color --> para dar color

Colores RGB: es una mezcal entre rojo, verde y azul, mezclando se crean los colores. Los valores van del 0 al 255.
text align --> para alinear el texto, al centro, a la izquierda, a la derecha...


Id para poner un identificador unico, no su puede repetir

Tenemos otro identificador que es class="", es como el id pero se puede repetir y asi se puede hacer servir apra mas de  un elemento.
Para cuando enlazamos la calse hay que poner un . delante: .textoazul

Selector universal, sirve para seleccionar todo, es este: *. si pusieramos un estilo azul se pondria todo el documento en azul.

Hay prioridad tambien en el css, el que esta mas arriba es el que primero lee.

## CSS
Enlacar un css con el html:
Ponemos un link en el html con el tipo de hoja de estilos que apunta a la ruta donde esta situada y  le decimos el tipo de datos que va a haber.
<link rel="stylesheet" href="./css/estilos.css" type ="text/css">

Selector de hijo:
