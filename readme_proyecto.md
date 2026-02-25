# Sistema de Inventario SENA (Django)
![Imagen del proyecto](IMAGEN-DEL-PROYECTO.jpg)

## Ejemplo en vivo
- [Repositorio en GitHub](https://github.com/Reaper2719/Sena_Inventario_Desarrollo)
- [Demo en producción](URL-de-la-demo-si-la-tienes)

## Descripción 📑

Sistema de inventario desarrollado como parte de mi formación en el SENA Centro ASTIN, dentro del proceso de Técnico en Sistemas y Tecnólogo en Análisis y Desarrollo de Software.

Permite gestionar productos, categorías, proveedores y movimientos de stock (entradas y salidas), manteniendo el control de las existencias en bodegas. Incluye autenticación básica de usuarios y una interfaz web sencilla para registrar operaciones de inventario, consultar listados y visualizar el estado actual del stock.

Este proyecto se complementa con otros desarrollos relacionados:

- [Inventario](https://github.com/JuanRuiz0822/Inventario): otra implementación de sistema de inventario.
- [MODELSIA](https://github.com/JuanRuiz0822/MODELSIA): modelos de IA y ML para futuros módulos inteligentes.
- [Stylish](https://github.com/JuanRuiz0822/Stylish): ecommerce de ropa elegante.
- [CursosOnline](https://github.com/JuanRuiz0822/CursosOnline): plataforma demo de cursos online.
- [CEAI-WEB](https://github.com/Reaper2719/CEAI-WEB): proyecto fullstack web.

## ¿Qué he aprendido en este proyecto? 🙇🏻 

- Modelado de bases de datos para sistemas de inventario (productos, movimientos, usuarios).
- Uso de Django para construir aplicaciones web con autenticación y panel de gestión.
- Importancia de la integridad de datos en operaciones de stock (evitar stock negativo, registrar cada movimiento).
- Separar lógica de negocio de la capa de presentación para facilitar el mantenimiento y poder aplicar pruebas.
- Uso de Git y GitHub para versionar el código y documentar el proyecto de forma profesional.

## Tecnologías 🛠
<!-- Iconos sacados de: https://github.com/hendrasob/badges/blob/master/README.md y https://github.com/alexandresanlim/Badges4-README.md-Profile -->
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://es.wikipedia.org/wiki/HTML5)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://es.wikipedia.org/wiki/CSS)
[![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://es.wikipedia.org/wiki/JavaScript)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

## Vista previa del proyecto
Si quieres echar un vistazo al proyecto, te recomiendo:

![Captura del proyecto](CAPTURA-DEL-PROYECTO.jpg)

## Autor ✒️
**Juan David Ruiz Anturi**

* [tu-correo-real@dominio.com](mailto:tu-correo-real@dominio.com)
* [LinkedIn](https://www.linkedin.com/in/tu-url-de-linkedin/)
* [Portafolio web](https://juanruiz0822.github.io/Reaper2719.github.io)

## Instalación 

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Reaper2719/Sena_Inventario_Desarrollo.git
   ```
2. Crea y activa un entorno virtual de Python.
3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Realiza las migraciones de la base de datos:
   ```bash
   python manage.py migrate
   ```
5. Crea un superusuario para acceder al panel de administración:
   ```bash
   python manage.py createsuperuser
   ```
6. Levanta el servidor de desarrollo:
   ```bash
   python manage.py runserver
   ```
7. Accede a la aplicación en `http://localhost:8000`.
  
## Licencia 📄
MIT Public License v3.0
No puede usarse comencialmente.
