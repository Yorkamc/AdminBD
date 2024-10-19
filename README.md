# 🚀 Administración de Base de Datos Oracle 21c XE 📊

**¡Bienvenido!** Este proyecto es una aplicación web para la **administración de bases de datos Oracle 21c XE**, creada con **PHP**, **HTML**, **CSS** y **JavaScript**. La aplicación permite gestionar respaldos, administración de tablespaces, monitoreo de rendimiento, auditoría y seguridad de usuarios, todo dentro de una interfaz fácil de usar y responsiva.

## 📋 Características

### 🔐 **Gestión de Usuarios**
- Creación, modificación y eliminación de usuarios de la base de datos.
- Gestión de roles y permisos para asegurar una correcta distribución de privilegios.

### 🗂️ **Administración de Tablespaces**
- Visualización de los tablespaces disponibles en la base de datos.
- Opciones para gestionar el tamaño y estado de los tablespaces.

### 📦 **Respaldos y Restauración**
- Creación de respaldos completos, por esquema o por tabla usando `expdp`.
- Restauración de respaldos a partir de archivos `.dmp`.
- Gestión de los archivos de respaldo.

### ⚙️ **Tuning de Consultas**
- Monitoreo de los planes de ejecución de las consultas.
- Gestión de índices y estadísticas para mejorar el rendimiento de las consultas.

### 📈 **Monitoreo de Performance**
- Información en tiempo real sobre el uso de CPU, memoria y estado general de la base de datos.
- Análisis de consultas pesadas para identificar cuellos de botella.

### 🔍 **Auditoría de la Base de Datos**
- Registro de eventos relevantes dentro de la base de datos.
- Herramientas para auditar el acceso de usuarios y las operaciones realizadas en la BD.

## 🎨 Diseño

La aplicación tiene un diseño **moderno y responsivo** utilizando la tipografía **Poppins** y una paleta de colores en tonos azules para una apariencia limpia y profesional. 

### Capturas de Pantalla

| Pantalla Principal | Módulo de Respaldos |
| --- | --- |
|En proceso |En proceso|

## 🛠️ Tecnologías Usadas

- **Lenguajes**: PHP, HTML, CSS, JavaScript
- **Base de datos**: Oracle 21c XE
- **Estilos**: CSS3 (Diseño Responsivo, Animaciones)
- **Herramientas**: Shell (`expdp` y `impdp` para respaldos)

## ⚙️ Instalación

Sigue los pasos a continuación para configurar y ejecutar este proyecto en tu entorno local:

1. **Clona el repositorio** en tu máquina:

    ```bash
    git clone https://github.com/usuario/repo-db-admin.git
    cd repo-db-admin
    ```

2. **Configura la base de datos Oracle 21c XE**: 
    - Asegúrate de tener Oracle 21c XE instalado y configurado.
    - Crea un usuario con los permisos necesarios para gestionar la base de datos.

3. **Configura el acceso a la base de datos en PHP**:
    - Modifica las credenciales de conexión en el archivo `functions.php`:

    ```php
    // functions.php
    $username = 'tu_usuario';
    $password = 'tu_contraseña';
    $host = 'localhost';
    $service_name = 'XE';
    ```

4. **Configura el servidor web** (puedes usar Apache o cualquier otro servidor compatible con PHP).
   
5. **Ejecuta la aplicación** abriendo el archivo `index.php` en tu navegador o apuntando tu servidor web al directorio del proyecto.

## 📂 Estructura del Proyecto

