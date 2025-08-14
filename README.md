# 🎓 Portafolio de Proyectos: Gestión de Datos de Estudiantes

Este repositorio contiene una colección de proyectos desarrollados en **Jupyter Notebooks**, que demuestran la aplicación de habilidades clave en el análisis y la gestión de datos. Estos trabajos forman parte de mi portafolio como analista de datos y se centran en la administración de registros de estudiantes, utilizando diferentes tecnologías y enfoques para el almacenamiento y procesamiento de la información.

## 📁 Proyectos Incluidos

### 1. Gestión de Estudiantes con Pandas y NumPy

* **`Estudiantes_csv.ipynb`**: Este proyecto implementa un sistema de gestión académica en Python. Se utiliza la librería **Pandas** para la manipulación de datos y **NumPy** para la generación condicional de valores. El objetivo es registrar estudiantes, calcular promedios, generar reportes de aprobación/reprobación y guardar los resultados en archivos **CSV**. El sistema maneja datos de manera local y estructurada, siendo un excelente ejemplo de análisis de datos a pequeña escala.

### 2. Gestión de Estudiantes con MongoDB

* **`Gestion_estudiantes_MONGODB.ipynb`**: Este notebook presenta un sistema de registro de estudiantes que se integra con una base de datos **NoSQL** de **MongoDB Atlas**. El proyecto se enfoca en las operaciones básicas **CRUD** (Crear, Leer, Actualizar, Eliminar). Demuestra cómo conectar Python con MongoDB usando la librería `pymongo` y cómo gestionar datos en un entorno distribuido en la nube, incluyendo un patrón para generar IDs secuenciales.

### 3. Gestión de Estudiantes con SQL Server

* **`Gestion_estudiantes_SQL.ipynb`**: Similar al proyecto anterior, este cuaderno desarrolla un sistema de registro que se conecta a una base de datos **relacional**, en este caso **SQL Server**. Se utiliza la librería `pyodbc` para establecer la conexión. El proyecto muestra la implementación de funciones CRUD y buenas prácticas como el uso de *placeholders* para prevenir inyecciones SQL, destacando la gestión de datos en un entorno de base de datos estructurada.

## 💻 Habilidades y Tecnologías Demostradas

* **Análisis de Datos y Manejo de Datos:** Manipulación y procesamiento de datos con **Pandas** y **NumPy**.
* **Programación en Python:** Creación de funciones, validación de entradas de usuario, manejo de errores (`try-except`) y estructuras de control (`while`).
* **Bases de Datos:** Conexión y gestión de datos en diferentes tipos de bases de datos:
    * **CSV (datos planos):** Persistencia de datos locales.
    * **NoSQL:** Conexión a **MongoDB Atlas** y operaciones CRUD usando `pymongo`.
    * **SQL:** Conexión a **SQL Server** y operaciones CRUD usando `pyodbc`.
* **Buenas Prácticas:** Manejo de credenciales de conexión, prevención de inyecciones SQL y uso de variables de entorno (conceptualmente).

## 🚀 Cómo Empezar

Para explorar los proyectos, simplemente navega por los archivos `.ipynb`. Puedes abrirlos en un entorno como **Jupyter Notebook** o **VS Code** para ver el código, las explicaciones y los resultados de cada celda.
