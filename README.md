# Bootstrap

[Bootstrap](https://getbootstrap.com/) es un kit de herramientas de código abierto para la implementación de diseño "[responsive](https://es.wikipedia.org/wiki/Dise%C3%B1o_web_adaptable)" y "[mobile-first](https://en.ryte.com/wiki/Mobile_First)" de sitios y aplicaciones web. 

[Bootstrap](https://getbootstrap.com/) fue desarrollado por [Twitter](https://twitter.com/getbootstrap), como un marco de trabajo ([framework](https://es.wikipedia.org/wiki/Framework)) para fomentar, en las herramientas internas, la consistencia en la producción de la visualidad de la interfaz gráfica de usuario ([Front-End](https://es.wikipedia.org/wiki/Front-end_y_back-end)). Desde su origen ha avanzado en distintas versiones. Su versión estable más reciente es la 4.

Con [Bootstrap](https://getbootstrap.com/) puedes implementar tanto prototipos rápidos como productos acabados, esto mediante el uso de los lenguajes habituales de Front-End para Web: Elementos de HTML5 relacionados con reglas de CSS3 traducidas de [Sass](https://sass-lang.com/) ([Less](http://lesscss.org/) en versiones anteriores a la 4), además de Javascript simplificado por la biblioteca [jQuery](https://jquery.com/).

Hay distintas maneras para comenzar a trabajar con Boostrap. Un grupo de opciones está en su [descarga](https://getbootstrap.com/docs/4.0/getting-started/download/), pero una opción mucho más rápida es Bootstrap[CDN](https://es.wikipedia.org/wiki/Red_de_entrega_de_contenidos). Para usar esta última opción, el documento HTML debe verse de la siguiente manera: 

```<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- CSS de BootstrapCDN  -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <title>Hola mundo!</title>
  </head>
  <body>
    <h1>Hola mundo!</h1>
    <!-- JS de BootstrapCDN -->    
    <!-- primero jQuery, luego Popper.js, después Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>```
