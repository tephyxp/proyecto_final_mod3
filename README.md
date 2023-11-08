# proyecto-final-módulo 3 (descripción)

El presente proyecto consiste en una aplicación web que permite obtener datos de una película procedente de la API "THE MOVIE DATABASE" : https://developer.themoviedb.org/reference/intro/getting-started.

Y que a su vez sea capaz de guardar estos datos obtenidos de la API, de la película elegida y grabarlos en nuestra base de datos local MySQL.

# instrucciones de instalación:

clonar el repositorio:

* Abrir la terminal y ubicarnos la carpeta local donde queremos guardar el proyecto
* Ejecutar el comando: 
git clone https://github.com/tephyxp/proyecto_final_mod3.git
* acceder dentro de la carpeta clonada con el comando cd nombre-del-repositorio
* abrir en visual code  con el comando code .
* Instalar las dependencias con npm install
* crear una base de datos en MySQL con el nombre "peliculas"
* Volver a vs code y modificar los datos referentes a la base de datos en el archivo src/config.js (DB_HOST ,DB_USER,DB_PASSWORD Y DB_NAME) y que coincida con los de nuestra propia base de datos.

# Puesta en marcha

Ejecutar npm run dev