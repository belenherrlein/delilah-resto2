Delilah-Resto-Project:

Delilah Resto Project es una API para realizar pedidos, registrar clientes de Restaurants y administrar a gusto los productos que se van a ofrecer.

Pasos para la inicialización del servidor:

Clona o descarga el repositorio.
1- Descarga e instala "Node.js". Si no lo tienes instalado lo puedes descargar en: 'https://nodejs.org/es/download/'

2- Descarga e inicia "XAMPP" en tu computadora. Lo puedes descargar en: "https://www.apachefriends.org/". 
    Inicia los servidores de Apache y MySQL.
    Ingresa a la siguiente url desde tu navegador: localhost/phpmyadmin
    Importa la base de datos que se encuenta en la carpeta BD/'DatabaseDelilahResto.sql'

3 Abrir la terminal ubicados en el archivo principal que se encuenta en src/'app.js' 
    Ejecutar el comando 'npm i' para instalar las dependencias utilizadas
    Ejecutar el comando 'node app.js' o 'nodemon app.js' para inicializar el servidor

4 Utilizaremos POSTMAN para probar nuestros endpoints con sus respectivos métodos. a. Puedes importar el archivo 'Delilah Resto Endpoints.postman_collection.json' a Postman y empezar a probar los Endpoints

5- a. Para realizar cualquier acción como ADMIN debera utilizar las credenciales proporcionadas al iniciar sesión como: nombre: admin contrasena: admin

b. O puede crear su propio usuario ADMINISTRADOR indicando lo siguiente al crear su cuenta: admin: 1