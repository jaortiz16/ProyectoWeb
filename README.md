# ProyectoWeb
Proyecto sobre inventarios en angular 
aca se suben los cambios que se hagan en el proyecto

INSTRUCCIONES AL EXTRAER EL REPOSITORIO

Al extraer el repositorio en una maquina 
cambiar el password dentro de la carpeta keys.js en la carpeta server para conectar con la base de datos local


Ejecutar el proyecto los siguentes comandos dentro de las carpetas indicadas para el correcto funcionamiento del proyecto

--dentro de la carpeta server 
al iniciar la creacion de las rutas en la rest API 

npm instal -g typescript   
//este es el modulo para poder ejecutar los comandos de typescript y los modulos 


npm run build   
// activa el coando para la vijilancia de los cambios en los archivos .js

npm run dev  
//en nueva terminal 
//activa el comando para transformar los archivos .ts en .js e inicia el servidor en el puerto 3000

npm i @types/express -D 
//instalar los modulos para usar express 

--dentro de la carpeta client 

ng serve 
// inciar el servidor de angular en el puerto 4000 para poder observar los cambios que se realizan en el cliente 