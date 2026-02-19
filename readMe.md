#  Traileros - Carreras y Rutas de Trail Running

¡Bienvenido a **Traileros**! Esta es una plataforma web diseñada para los apasionados de las carreras por montaña. Aquí podrás encontrar información detallada sobre las pruebas más exigentes de la geografía española, centrándose especialmente en las zonas de Málaga y Cádiz.

##  Características principales

* **Diseño Responsivo**: La web se adapta perfectamente a móviles, tablets y ordenadores de escritorio.
* **Header Moderno**: Incluye un logotipo circular con un diseño limpio y profesional.
* **Tarjetas Detalladas**: Cada carrera cuenta con su propia tarjeta informativa que incluye:
    * Nivel de dificultad (Media, Alta, Muy Alta).
    * Ubicación y fecha del evento.
    * Estadísticas clave: Distancia total y desnivel positivo.
* **Estilo Montañero**: Interfaz con una paleta de colores verdes y oscuros inspirada en la naturaleza.

##  Tecnologías utilizadas

* **HTML5**: Estructura semántica para mejorar el SEO y la accesibilidad.
* **CSS3**: Estilos personalizados utilizando **Flexbox** y **CSS Grid** para un layout impecable.
* **Imágenes WebP**: Optimización de imágenes para una carga rápida.

##  Requisitos del Entorno

Para el despliegue y correcto funcionamiento de las funcionalidades dinámicas (como el procesamiento de formularios o futuras consultas a bases de datos), se requiere el siguiente entorno:

* **Servidor Local**: [XAMPP](https://www.apachefriends.org/es/index.html) (recomendado) o cualquier servidor Apache.
* **Versión de PHP**: **8.0 o superior**. 
    * *Nota*: Aunque el proyecto actual es principalmente estático, se recomienda esta versión para asegurar la compatibilidad con los scripts de filtrado y procesamiento que se implementarán.
* **Base de Datos**: MySQL/MariaDB (opcional, para futuras versiones con registro de usuarios).

###  Instrucciones de Despliegue en Local
1.  Instala XAMPP y activa los módulos **Apache** y **MySQL**.
2.  Mueve la carpeta del proyecto a la ruta `C:/xampp/htdocs/` (en Windows).
3.  Accede desde tu navegador a `http://localhost/nombre-de-tu-carpeta/`.

##  Estructura del proyecto

```text
/
├── index.html        # Estructura principal de la web
├── style.css         # Todos los estilos y diseño visual
└── images/           # Carpeta con logos y fotos de las carreras
    ├── logo.webp
    ├── genal.jpg
    └── ...

