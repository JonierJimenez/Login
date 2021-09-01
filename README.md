Como inicializar el proyecto

Para inicializar el proyecto es necesario que tenga instalado Laravel en su versión mas resiente, al igual deberá tener instalado Composer.

Paso 1: debe entrar a línea de comando (CMD) y ubicarse en la carpeta del proyecto ejemplo: C:\xampp\htdocs\Login>

Paso2: Una vez estando ubicado en la carpeta del proyecto utilizamos el comando a continuación C:\xampp\htdocs\Login>php artisan serve

Al ejecutar este comando debe aparecer por ejemplo http://127.0.0.1:8000 la ruta y el puerto donde esta corriendo nuestro proyecto Esto con el fin de inicializar el servidor y poder correr el proyecto en el navegador mostrando el archivo index.php que se encuentra en la carpeta public del proyecto.

Funcionalidades

Login 

1.Cuenta con un login para inicio de sección el cual pide como datos correo y contraseña.

2.Puede recordar usuario, para que sea más fácil el inicio de sección.

3.Valida campos vacíos al momento de presionar el botón Login muestra la alerta si es que existen campos vacíos.

4.Validación de correos, si el correo esta mal escrito salta una notificación.

Register

1.Para el proceso de registro se piden los siguientes datos Name, E-Mail, Password y confirm Password.

2.Validar campos vacíos si es que existe algún campo vacío.

3.Validacion de contraseña de 8 caracteres o más.

4.Confirmacion de contraseña para validar si las contraseñas coinciden.

5.Validacion de correo, esto para saber si está bien escrito el correo.

6.Validacion de correos registrados, si un correo ya está registrado no deja hacer otro registro con ese mismo correo.

Logout

1.cuando estas registrado puedes hacer un logout y salir del dashboard.

Bonus 

Enlace página web: http://loginjj.herokuapp.com/

