ENTREGAR EL EN AULA VIRTUAL LOS DOS ALUMNOS EL ENLACE AL REPOSITORIO. DEBE SER PUBLICO
# GUIA DE INSTALACIÓN DEL CINE
## DEBEMOS INSTALAR DOCKER Y ABRIR UN CONTAINER NGINX
### Nosotros utilizamos el puerto 8081 porque ya tenemos en uso el 8080.
### Este comando realizarlo en vuestra consola de comandos windows.

````bash
docker run -d -p 8081:80 nginx
````

## COGEMOS EL REPOSITORIO Y LO COLOCAMOS EN:
### usr/share/nginx y encontraras la carpeta "html", puedes acceder a ella desde terminal con:
```bash
cd usr
cd share
cd nginx
```
## BORRAMOS LA CARPETA "html", METEMOS NUESTRO REPOSITORIO Y CAMBIAMOS SU NOMBRE A "html" puedes cambiar el nombre del repositorio con este comando en la terminal:

```bash
mv CinePractica html
```
