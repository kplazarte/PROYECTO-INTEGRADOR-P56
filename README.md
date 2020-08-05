# PROYECTO-INTEGRADOR-P56 
# Empresas y remuneraciones
El proyecto integrador se podra crear usuarios y cambios de clave , existiran 3 tipos de usuarios: invitados, administrador y un usuario registrado.
Creará reportes con una base de datos multidimensional los reportes se  presentaran en una aplicacion web donde el usuario eligira un tipo de busqueda
para crear el reporte.
El proyecto estará bajo una licencia de software libre y el código será subido a esta plataforma periodicamente.
Para realizar el siguiente proyecto se ingresa a Netbeans y se procede a crear un proyecto Web con el Framework Java Server Faces y el componente 
PrimeFaces

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/p1.png)

Posteriormente se procede a configurar la pantalla del invitado mediante PrimeFaces y estilos css asi como se le asignan direccionamientos para el repositorio
y la wiki del mismo

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/co1.png)

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/1.png)

Posteriormente se procede a realizar la conexion con la base de datos para lo cual ingresamos a la seccion de server databases y seleccionamos una nueva conexion escogemos postgres e ingresamos el nombre de nuestra base el puerto el usuario y la contraseña

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/conexion.png)

Seguido a esto se procede a configurar la seccion para que tanto administradores como Usuarios puedan loguearse para lo cual primero se tiene que exportar desde la base las entidades de la misma asi como crear JSF Pages de las mismas posteriorme se crea una pagina de tipo Manager Bean en la cual se crea nuestro metodo de verificar y posteriormente se lo implementa en nuestra pantalla de login

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/co2.png)
![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/f2.png)

Para realizar la configuracion de nuestro nuestro usuario administrador nos ayudamos de los JSF Pages creados anteriormente con lo cual implementamos en una tabla los usuarios que tiene nuestra base asi como todos los items que posee el usuario adminitrador tambien cada campo se tiene que encontrar verificado
Se procede a realizar la configuracion para que se pueda crear,ver,actualizar y eliminar un usuario

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/c5.png)

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/f3.png)

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/5.png)
![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/6.png)
![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/7.png)

Para realizar la seccion de usuarios se procede a crear la pantalla del mismo asi como se crea un servlet en nuestro proyecto el cual nos va ayudar a implementar
nuestros repositorios en los mismo se procede a crear un metodo dentro del do Get del servlet y implementar nuestros reportes

![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/fin2.png)
![](https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56/blob/master/imagenes/fin.png)


## 🔧 Descarga
Para instalar el proyecto, utilizaremos los comandos básicos de Git.

**Comenzamos**
* Vamos a l perfil en donde se encuentra el proyecto [Github](http://github.com) y seleccionamos el proyecto **"PROYECTO-INTEGRADOR-P56"**.
* Una vez dentro del proyecto, seleccionamos la opcion _Clone o Download_ y copiamos la URL que aparece ahí. Ejemplo: "https://github.com/PROYECTO-INTEGRADOR-P56".
* Después de copiar la URL del proyecto, abrimos la consola de Git y digitaremos:
 ```
 $ git clone https://github.com/kplazarte/PROYECTO-INTEGRADOR-P56
  ```
  y **listo!!** ya tendremos descargado el proyecto en nuestro disco C.
## 🛠️ Herramientas
* Neatbeans
* PostgreSQL
* Pentaho Community
* Power Architect
## ✒️ Autores
* Kevin Plazarte
* Alejandro Marín
* Sebastian Paredes
* Daniela Campoverde
## 📄 Licencia
Este proyecto esta bajo la licencia MIT utilizamos esta [licencia](LICENCIA.md) porque es permisiva y simple con condiciones que solo requieren la
preservacion de los derechos de autor y avisos de licencia. Esta licencia permite reutilizar el software así licenciado tanto para ser software libre como para ser software no libre, y en nuestro proyecto solo queremos conservar los derechos de autor.
