# timegian

> v1.0.1 Beta | Javascript puro

Cambia la fecha a segundos, minutos, horas, días, meses y años

## Introduccion

Timegian toma la fecha para convertirla en minutos, horas y dias muy similar a timeago, a direfencia de el timegian esta escrito en javascript puro, en donde una de las grandes ventajas  que tiene es que es totalmente independiente de framework lo que hace que no afecte a la velocidad de tu sitio web o blog.

### Ejemplo

Timegian extrae la fecha para que en vez de mostrarse asi "10, de Junio del 2017" la muestre de la siguiente manera "Hace 10 meses".

### Como usarlo
1. Primero, descarga el archivo ```bygian.timegian.min.js``` que se encuentra en la carpeta source, alojalo en un hosteador y coloca el script despues de </body>

```html
<script src="bygian.timegian.min.js" type="text/javascript"></script>
```
si no tienes donde alojar el archivo ```bygian.timegian.min.js``` puedes usar el siguiente que te damos a disposición:

```html
<script src="//cdn.rawgit.com/giancreativo/timegian/master/source/bygian.timegian.min.js" type="text/javascript"></script>
```

2. Este script funcionara dentro de los elementos time y dentro ella tendra el elemento span con su clase timegian, funcionando asi con un atributo que es el data-time que contendra la fecha y hora de acuerdo con el estándar ISO 8601:

```html
<time><span class='timegian' data-time='2018-03-02 13:50:00'>Loading</span></time>
```

## Versiones

| Version | Notas                                                                                |
|---------|--------------------------------------------------------------------------------------|
|  1.0.1B | Primer lanzamiento de la version beta, analizando futuros problemas para correguir   |
|     ... | ...                                                                                  |

## Author

[Gian Imperiale](https://bygian.com) ([fb](https://fb.com/gianfranco.imperialevivas))

## License

[CCommons License](http://creativecommons.org/licenses/by-nc/4.0/)
