# CRUD de Usuarios

Este proyecto es una aplicación web para la gestión de usuarios. Permite crear, leer, actualizar y eliminar usuarios. Está desarrollado utilizando PHP y MySQL.

## Características

- Crear nuevos usuarios
- Leer información de usuarios existentes
- Actualizar información de usuarios
- Eliminar usuarios

## Requisitos

- XAMPP (o cualquier otro servidor local que soporte PHP y MySQL)
- Navegador web

## Instalación

1. Clona este repositorio en tu servidor local:
    ```bash
    git clone https://github.com/tu-usuario/CRUD-de-usuarios.git
    ```

2. Mueve el proyecto a la carpeta de tu servidor local (por ejemplo, `C:\xampp\htdocs\CRUD-de-usuarios`).

3. Importa la base de datos MySQL:
    - Abre phpMyAdmin y crea una nueva base de datos llamada `crud_usuarios`.
    - Importa el archivo `database.sql` que se encuentra en la carpeta del proyecto.

4. Configura la conexión a la base de datos:
    - Abre el archivo `config.php` y actualiza los datos de conexión a tu base de datos.

    ```php
    <?php
    $servername = "localhost";
    $username = "root";
    $password = "";
    $dbname = "crud_usuarios";
    ?>
    ```

## Uso

1. Abre tu navegador web y accede a `http://localhost/CRUD-de-usuarios`.

2. Utiliza la interfaz para gestionar los usuarios.

## Estructura del Proyecto

- `index.php`: Página principal que muestra la lista de usuarios.
- `create.php`: Página para crear un nuevo usuario.
- `read.php`: Página para leer la información de un usuario.
- `update.php`: Página para actualizar la información de un usuario.
- `delete.php`: Página para eliminar un usuario.
- `config.php`: Archivo de configuración de la base de datos.
- `database.sql`: Archivo SQL para crear la base de datos y las tablas.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, sigue los pasos a continuación para contribuir:

1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature/nueva-feature`).
3. Realiza tus cambios y haz commit (`git commit -m 'Agregar nueva feature'`).
4. Sube tus cambios (`git push origin feature/nueva-feature`).
5. Abre un Pull Request
