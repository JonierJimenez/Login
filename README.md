Bonus
Enlace página web: http://loginjj.herokuapp.com/


Como inicializar el proyecto

Para inicializar el proyecto es necesario que tenga instalado Laravel en su versión mas resiente, al igual deberá tener instalado Composer y node.js con nmp.

Paso 1: abrimos la carpeta del proyecto en el editor de código Visual Studio.

Paso 2: entramos a la consola de visual Studio y nos ubicamos en la carpeta del proyecto ejemplo: C:\xampp\htdocs\Login>

Paso 3: debe ejecutar la línea de comando ‘composer install’, para instalar cada uno de los componentes que nos falta dentro del proyecto.

Paso 4: creamos el archivo .env, lo podemos hacer de la siguiente manera ‘cp .env.example .env’.

Paso 5: configuramos el archivo .env creando la llave con el siguiente comando ‘php artisan key:generate’.

Paso 6: creamos la base de datos para esto utilizamos el XAMPP y en phpmyadmin definimos el nombre de la base de datos, este nombre debemos ponerlo en el archivo .env, en la parte de DB_DATABASE=”name”.

Paso 7: en la consola de visual studio hacemos el siguiente comando “php artisan migrate”.

Paso 8: hacemos el siguiente comando “npm install”.

Paso 9: hacemos el siguiente comando “npm run dev”.

Luego de todo esto ya tenemos configurado el proyecto para poder inicializarlo.

Paso 10: Una vez estando ubicado en la carpeta del proyecto utilizamos el comando a continuación C:\xampp\htdocs\Login>php artisan serve.

Al ejecutar este comando debe aparecer por ejemplo  http://127.0.0.1:8000 la ruta y el puerto donde esta corriendo nuestro proyecto.
Esto con el fin de inicializar el servidor y poder correr el proyecto en el navegador mostrando el archivo index.php que se encuentra en la carpeta public del proyecto.    

Funcionalidades 

Login
1.cuenta con un login para inicio de sección el cual pide como datos correo y contraseña.

2.puedes recordar usuario, para que sea más fácil el inicio de sección.

3.valida campos vacíos al momento de presionar el botón Login muestra la alerta si es que existen campos vacíos. 

4. validación de correos, si el correo esta mal escrito salta una notificación.

Register

1.Para el proceso de registro se piden los siguientes datos Name, E-Mail, Password y confirm Password.

2.Valida campos vacíos si es que existe algún campo vacío.

3.Validacion de contraseña de 8 caracteres o más.

4.Confirmacion de contraseña para validar si las contraseñas coinciden.

5.Validacion de correo, esto para saber si esta bien escrito el correo.

6.Validacion de correos registrados, si un correo ya esta registrado no deja hacer otro registro con ese mismo correo.

Logout
1.cuando estas registrado puedes hacer un logout y salir del dashboard.




