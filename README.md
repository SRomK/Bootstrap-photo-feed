![4Geeks Logo](https://4geeksacademy.com//images/4geeks-logo.png)
# Instagram Photo Feed with Bootstrap
## Owners:
### 	- Sofia Romero
### 	- Orealba Soriano

## Explicación del proceso 

En este proyecto aplicamos el framework Front-end de Bootstrap v5.1. Primero hemos creado un archivo `index.html` y luego pegamos el link de la stylesheet de Bootstrap en el head de nuestro `<html>`. A su vez enlazamos a nuestro `<head>` una stylesheet con nombre de archivo `main.css`
con el que aplicamos los estilos necesarios a todos los `<tags>`.

El proyecto consiste en imitar un feed de fotos de instagram utilizando Bootstrap. Para ello hemos estructurado el html con sus respectivos elementos `<div>` para realizar el "esqueleto" principal y asignamos a esos  `<div>` las clases de Bootstrap de `rows` y `columns`, con un contenedor de todo el contenido usando `<div class="container-fluid">`.

Nuestro proyecto contiene:

1. 		Header con logo y menu desplegable
2. 		Pills (dos cuadrados)
3. 	 	Dentro de cada pill el código de cada vista
4. 		En primera pill: imagenes cuadradas estructuradas por filas y columnas a modo de galeria
5. 		En segunda pill: 4 posts creados a partir de elementos Card de Bootstrap, cada uno con su imagen, texto del post, iconos estaticos y likes

## Compilar el código
Para compilar el código es necesario introducir el siguiente comando en la terminal:
```sh
$ pip3 install flask && python3 server.py
```

