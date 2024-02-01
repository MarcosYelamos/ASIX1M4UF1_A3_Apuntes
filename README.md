# ASIX1M4UF1_A3_Apuntes

Tercer repositorio de ASIX1 2324
Confirmación de lo que sabemos

## Primer capítulo: MARKDOWN7 (SUBTITULO)

(#) Esto sirve para poner encabezados, hay 6 niveles como en HTML, al poner este encabezado te pone un enlace en el título.
<br>
<br>

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
<br>
<br>
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
<br>

[Esto es un enlace](https://www.google.com/url?sa=i&url=https%3A%2F%2Finhispania.com%2Fes%2F15-formas-de-decir-si-sin-decir-si%2F&psig=AOvVaw19IUwh4EM0mAYLZhS421Tp&ust=1696059558183000&source=images&cd=vfe&opi=89978449&ved=0CA8QjRxqFwoTCOik266oz4EDFQAAAAAdAAAAABAD "Enlace a si")
<br>

Una foto:
![Esto es una foto](https://inhispania.com/wp-content/uploads/2021/05/1.jpg "Esto es un foton de si")

Una tabla:

|Primera Col.|Segnda Col.|3 Col|
|---------------|:------------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX1|M4|

-[ ]Opción A

-[X]Opción B

-[ ]Opción C
<br>
<br>

## Segundo capítulo: HTML

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
<br>
Hay que especificar el lenguaje que se va a utlizar cuando abrimos un nuevo archivo.

Partes de un documento HTML
Etiqueta por la cual le de

html:5 para añadir al archivo las partes de un documento html.
<br>
<br>


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
EN HTML existen muchas algunos elementos que hacen de conetenedores:
Tenemos el div, section, article.
Luegopodemos diivdir la pagina en header(encabezado), footer(pie de pagina)...

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

<br>
<br>

## Tercer capítulo: GITHUB Y PAGES
AL crear un repositorio en Github siempre hay que inicializarlo añadiendo el "READE.md".

"IMPORTANTE": Debemos estar en un cmd para ejecutar los comandos y tener en cuenta la ruta de donde estamos, preferiblemente en la ruta donde se va a aetar e reposiorio o donde ya esta.

__Para clonar el repositorio de github y poder trabaarlo en local:__
```
"git clone" (ruta del repositorio a clonar).
```
Para añadir toof lo que hemos modificado habra que ejecutar estos 3 comandos:
```
git add.
git commit -m "(Nombre del commit)"
git push origin main
```
Una vez ejecutados si fueramos al github veriamos que todo lo que hemos hecho en local se habría subido.
<br>
<br>

#### PAGES
Para hacer que un repositorio de github se transforme en pagina web iremos a configuración (settings), en el menú de la izquierda seleccionaremos pages.
Seleccionamos la rama(Branch) Main y le damos a guardar (save). Al hacer esto y esperar un poco se nos creará un enlace a nuestra página.
<br>
<br>

## Continuación HTML: tabla
Como se hace una tabla en HTML?

Con la etiqueta ```<Table>```.

En el interior de la etiqueta ```<table>``` tenemos estas etiquetas para estructura la tabla: ```<thead>```, ```<tbody>``` y ```<tfoot>```.
Dentro de estas etiquetas debemos poner ```<tr>``` y dentro del ```<tr>``` pondremos ```<td>``` si queremso rellenar un campo de la tabla o ```<th>``` si queremos rellenar un encabezado o pie de la tabla.

Aqui podemos ver un ejemplo:

Codigo:

__Border es para ponerle borde a la tabla.__

```
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
```

Quedaria tal que así:
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



## Cuarto capítulo: CSS

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

Si ponemos el css en el head de la misa pagina van dentrode una etiqueta style:

h1,h2 {
    color: Blueviolet
}


<br>

## CSS
Enlacar un css con el html:
Ponemos un link en el html con el tipo de hoja de estilos que apunta a la ruta donde esta situada y  le decimos el tipo de datos que va a haber.
```
<link rel="stylesheet" href="./css/estilos.css" type ="text/css">
```


Selector de hijo: Podemos afectar a un elemento que esta dentro de otro, pero solo un nivel por debajo.

    li > strong {
            color: blueviolet;
    }
<style>
    li > strong {
            color: blueviolet;
    }
</style>

El codigo de arriba afectaria al texto de debajo:
<ol>
    <li><strong>200g</strong> de chocolate negro</li>
    <li><strong>150g</strong> de mantequilla</li>
    <li><strong>150g</strong> de azúcar</li>
    <li>3 huevos</li>
    <li>150g de harina</li>
    <li>1 cucharadita de polvo de hornear</li>
    <li>Una pizca de sal</li>
</ol>

<br>
<br>



<br>
<br>

Selector de descendientes:
Esto afectaria a cualquier strong que se encuentre dentro de un parrafo, da igual si es un hijo o no.

    p strong {
        color: blueviolet;
    }



Cambiar la letra del texto:
Para cambiar la letra del texto iremos a la pagina web de google fonts y una vez hemos escojido la fuente que queremos deberemos copiar el link que se vera algo asi:
```
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Edu+TAS+Beginner&display=swap" rel="stylesheet">
```
<br>
Y una vez puesto el link, habra que poner o en el head del html o en una hoja externa, la linia que ponga en el google fonts.

Por ejemplo:

    <style>
        p {
            font-family: 'Edu TAS Beginner', cursive;
        }
    </style>
<br>


En CSS tenemos más cosas como:

A las filas que seran divs que engloben avrias cosas les pondremos:
```
.row:after {
    content: "";
    display: table;
    clear: both;
}
```
<br>
Cuando hagamos columnas les pondremos:

```
.column-1{
    width: 100%;
    float: left;
}
```

Podemos utilizar el flex por ejemplo para que una foto ocupe todo el ancho y el alto de la página y poner el texto en medio:
```
.flex{
    display: flex;
    align-items: center;
    justify-content: center;
}
```

Siempre que utilizemos el display:flex pondremos a todo:

```
* {
    box-sizing: border-box;
}
```

## Quinto capítulo: RESPONSIVE

EL responsive lo utlizamos para que cuando una página web hecha para ordenador sea abierta en un móvil se siga vieno bien y/o cambie el fromato para adecuarse mas al espacio que tiene.
Resumiendo básicamente es para cambiar el formato de la página cuando se cambie de dispositivo, asi depediendo de si visitas la página en el movil o en el ordenador cambiará y se adecuará.

Lo que se utiliza para esto es:
```
@media only screen and (max-width: 700px) {
    .column-3{
        width: 100%;
    }
    /* column-4 pasará de tener 25% a 50% */
    .column-4{
        width: 50%;
    }
}
```
Está diciendo que cuando la pantalla se haga más pequeña de 700px en vez de haber 3 columnas habrá 1 y en vez de 4 habra 2.