
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

La implementación del CRUD en PHP junto con bases de datos nos brinda una poderosa herramienta para gestionar datos en aplicaciones web. Mediante la combinación de HTML y PHP, podemos crear formularios de entrada, mostrar datos, actualizar registros y eliminar información de manera eficiente y segura.

Es fundamental comprender y aplicar adecuadamente estas operaciones básicas para desarrollar aplicaciones web robustas y funcionales. Al dominar el CRUD en PHP, los desarrolladores pueden construir aplicaciones web dinámicas que interactúan con bases de datos de manera efectiva, mejorando así la experiencia del usuario y la eficiencia en el manejo de datos.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

Una página de inicio sirve como la puerta de entrada principal a un sitio web. Su propósito principal es proporcionar una visión general y orientación rápida sobre el contenido y las funciones que ofrece el sitio web. Una página de inicio es esencial para proporcionar una experiencia de usuario intuitiva y satisfactoria, ayudando a los visitantes a orientarse en tu sitio web, descubrir contenido relevante y tomar acciones específicas que contribuyan a tus objetivos comerciales. 

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.
  - Modelo de datos.
  - Presentación de contenido destacado.
  - Branding y reconocimiento.
  - Facitilar búsqueda de información.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

Agregar usuarios a una aplicación proporciona una serie de beneficios, desde gestionar el acceso y la seguridad hasta mejorar la personalización y la experiencia del usuario. Además, permite una comunicación efectiva, facilita la colaboración y brinda oportunidades para estrategias de marketing dirigidas y la retención de clientes.

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.
  - Gestión de acceso y autenticación.
  - Personalización y experiencia del usuario.
  - Seguimiento y registro de actividades.
  - Marketing y fidelización de clientes.

### 3. Editar Usuario (`edit.php`)

La funcionalidad de editar usuarios en una aplicación CRUD de PHP implica crear un formulario para editar los detalles del usuario, procesar los datos ingresados, actualizar los detalles del usuario en la base de datos y proporcionar retroalimentación al usuario sobre el resultado de la operación de edición.

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.
  - Feedback al usuario.
  - Seguridad.
  - Gestión de errores.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.


