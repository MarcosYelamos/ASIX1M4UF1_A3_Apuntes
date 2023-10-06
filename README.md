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
Las tres tildes sirven para encuadrar.
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

encabezado --> <head> </head> (Va al principio de la pagina es la parte donde definimos las caracetristicas de la pagina y donde metemos todo el contenido no visible por los visitantes.)


<meta charset="UTF-8"> que set de caracteres tiene que cojer la pagina, en este caso coje el que utilizamos, con la ñ añadida por ejemplo.

<meta name="viewport" content="width=device-width, initial-scale=1.0"> Como se ve a ver la pantalla 

<title>Document</title> Es el titulo de la pagina. en la pestaña del navegador se vera lo quese ponga

<favicon> para definir el icono de la pagina web que  s eve arriba en la pestaña del navegador.

cuerpo --> <body> </body>
```

Hay dos categorias de etiuqteas:

Etiquetas de bloque: Cuando se caba de renderizar el contenido de etiqueta deja un espacio de linea. Ej: las etiquetas de titulo, parrafo, listas, tablas.

Etiquetas de linea: Cuando se acaba de renderizar la etiqueta __NO__ hace un salto de linea.

```
h1 --> encabezado, tiene 6 niveles, cambian segun el numero, el 1 es el mas grande.
```