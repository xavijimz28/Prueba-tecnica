1. Crear una base de datos en SQL derver
CREATE DATABASE Test;

2. Dentro de la carpeta Test buscar archivo Program.cs para descomentar el codigo para realizar las migraciones de las tablas de la base de datos.

    ![image](https://user-images.githubusercontent.com/110143623/208115084-53c8d05a-dfb0-47a5-b72d-577d7d7d9015.png)


3. En el archivo appsetiings.json en la conexion con la base de datos cambiar el nombre del servidor

    ![image](https://user-images.githubusercontent.com/110143623/208115217-3ad7e464-eee2-468e-b9b2-1052cae009aa.png)


4. Establecer como proyecto de inicio El proyecto Test

5. Abrir la Consola de administracion de paquetes seleccionar como proyecto predeterminado TestDB y ejecutar el comando Add-Migration InitDB

    ![image](https://user-images.githubusercontent.com/110143623/208115290-0adc9242-bffd-42b2-8079-ae7bab73602a.png)


6. Se crean las migraciones y verificar en SQL server que se hayan creado las tablas

    ![image](https://user-images.githubusercontent.com/110143623/208115338-b13d32ad-527d-486e-b97c-db8f83e5e36a.png)


7. Ejecutamos el programa para realizar las pruebas con Swagger

    ![image](https://user-images.githubusercontent.com/110143623/208115453-280ecc3d-dc16-4c0f-b1b6-06e59db8a6f2.png)


