# Convertir Formatos a GeoJSON
Hemos visto el procedimiento para cargar datos vectoriales directamente al código, sin embargo, te habrás dado cuenta que puede llegar a ser tedioso, debido a que, ante el más mínimo error en el código, la información no se actualizará en el mapa. 

## Para cantidades de información mayores, o geometrías más complejas, lo mejor será utilizar un programa especializado en Sistemas de Información Geográfica para hacer el tratamiento de los datos, y posteriormente, añadirlos a nuestro código. 

Para empezar será necesario convertir todos nuestros datos a un formato compatible con Leaflet, esto será posible con el formato GeoJSON. Hay que recalcar que esto sólo aplica para datos vectoriales, por ejemplo archivos tipo shape (.shp)
A continuación describiremos el procedimiento para convertir al formato GeoJSON

#### 1. Con la información que deseamos convertir cargada en Qgis activaremos la capa a convertir.
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen1.png )
#### 2. Al hacer click derecho sobre la capa seleccionaremos la opción de exportar y posteriormente la opcion de guardar como o Save features as
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen2.png )
#### 3. En la pestaña de FORMATO elegiremos GeoJSON. IMPORTANTE. Es necesario reproyectar la capa a coordenadas geográficas, ya que Leaflet unicamente trabaja con dicho sitema de referencia. Guardamos en la carpeta seleccionada.
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen3.png )
#### 4. En la carpeta que seleccionaste, da click derecho en el archivo, y elege la opción de abrir con notepad, o abre el archivo en el editor de texto de tu preferencia
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen4.png )
#### 5. Haremos el procedimiento usual para declarar una variable, recuerda usar un nombre que te sea familiar para futuros procedimientos.
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen5.png )
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen6.png )
#### 6. cambiaremos el lenguaje del codigo, como se ve en la imagen, posteriormente guardaremos el archivo con extension js, en una carpeta distinta de preferencia.
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen7.png )
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen8.png )
#### 7. Al abrir nuevamente el archivo en Notepad, deberán haberse aplicado cambios sutiles como el cambio de color en algunas líneas del código como en la variable y los paréntesis
![screenshot](https://raw.githubusercontent.com/sampach95/ConvertirFormatosAGeoJSON/master/img/Imagen9.png )
#### 8. Para verificar que se haya realizado correctamente el procedimiento, habrá que cargar la información al mapa. Como lo veremos en el siguiente tutorial.

Siguiente Tutorial https://github.com/sampach95/CargarGeoJSON

Haz click en el siguiente enlace para volver a la pagina inicial
https://github.com/sampach95/ComoCrearMapasEnLaWebConLeaflet



