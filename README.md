# Mi Proyecto Ejemplo
# API de Gestión de Películas con FastAPI

Este proyecto es una API simple de Gestión de Películas construida con FastAPI, que permite a los usuarios interactuar con una base de datos PostgreSQL para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre registros de películas. La API permite recuperar, agregar, actualizar y eliminar películas de una base de datos.

## Requisitos

Antes de comenzar el proyecto, asegúrate de tener las siguientes dependencias instaladas:

- Python 3.7+
- Base de datos PostgreSQL
- FastAPI
- psycopg2
- SQLAlchemy

Puedes instalar los paquetes de Python necesarios con pip:

```bash
pip install fastapi psycopg2 sqlalchemy

Estructura del Proyecto
El proyecto contiene los siguientes componentes clave:

main.py: El archivo principal de Python que define la app de FastAPI y los endpoints de la API.
Base de datos PostgreSQL: La base de datos utilizada para almacenar los datos de las películas. Puedes usar tu configuración local de PostgreSQL.
Configuración de la Base de Datos
Esta API está diseñada para funcionar con una base de datos PostgreSQL. Asegúrate de tener PostgreSQL instalado y configurado con los siguientes parámetros de la base de datos:

Base de datos: postgres
Usuario: postgres
Contraseña: mysecretpassword
Host: localhost
Puerto: 5432

Registro del proceso API

1. Crear una carpeta en el sistema para poder subirla a visual studio code
2. empezar con la configuración de entorno Python -m venv venv
3. venv\Scripts\activate # para levantar el entorno
importar flask con pip install flask
4. en este caso utilizaremos un Docker pull postgres para conectar la API a una base de datos, se debe copiar desde el mismo Docker 
5. con esta conexión podemos ingresar al Docker desktop y visualizar el archivo cargado
