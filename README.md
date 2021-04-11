1. [Intro ](#schema1)

<hr>

<a name="schema1"></a>

# 1. Intro

En este curso vamos aprender desde 0, todos los secretos de `Bootstrap 4`. Conocerás las nuevas actualizaciones, las ventajas de este Framework y porque es uno de los más usados para construir páginas web profesionales. Ademas, crearemos una proyecto web utilizando los componentes más populares que incluye.
![img](./images/002.png)
![img](./images/003.png)

<hr>

<a name="schema2"></a>

# 2. Todo incluido

![img](./images/001.png)
<hr>

<a name="schema3"></a>

# 3. Instalación Koala
[Koala](http://koala-app.com/)

Si no me funciona, lo hacemos por terminal
~~~bash
sass scss:css --watch
~~~

<hr>

<a name="schema4"></a>

# 4. ¿Por qué Bootstrap? y novedades

Rápida y gran comunidad de usuarios 

![img](./images/004.png)
![img](./images/005.png)

<hr>

<a name="schema5"></a>

# 5. Instalación con CDN
Ir a la página [Bootstrap Started](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
Y copiar y pegar el siguiente código:
Esta en la sección `Starter template`
~~~html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js" integrity="sha384-SR1sx49pcuLnqZUnnPwx6FCym0wLsk5JZuNx2bPPENzswTNFaQU1RDvt3wT4gWFG" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.min.js" integrity="sha384-j0CNLUeiqtyaRmlzUHCPZ+Gy5fQu0dQ6eZ/xAww941Ai1SxSY+0EQqNXNE6DZiVc" crossorigin="anonymous"></script>
    -->
  </body>
</html>
~~~

<hr>

<a name="schema6"></a>

# 6. Instalación en local
Descargar los archivos css y js de: https://getbootstrap.com/docs/5.0/getting-started/download/

![img](./images/006.png)

Crear las carpetas CSS y JS en nuestro proyecto y guardar en la carpeta CSS el archivo, `bootstrap.min.css`
~~~html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
~~~


~~~html
<link href="./css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
~~~


Descargamos el jqueryde : https://jquery.com/download/ y lo guardamos el carpeta js

Descargamos el poper : https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js y lo guardamos en la carpeta js

Cargando el archivo en desde mi red local
~~~html
<script src="./js/popper.min.js"></script>
~~~
Cargando el archivo desde CDN
~~~html  
<!-- <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js" integrity="sha384-SR1sx49pcuLnqZUnnPwx6FCym0wLsk5JZuNx2bPPENzswTNFaQU1RDvt3wT4gWFG" crossorigin="anonymous"></script> -->
~~~

Cargamos el archivo `bootstrap.min.js` desde nuestra red local
~~~html
<script src="./js/bootstrap.min.js"></script>
~~~






## Recursos
https://hackerthemes.com/bootstrap-cheatsheet/