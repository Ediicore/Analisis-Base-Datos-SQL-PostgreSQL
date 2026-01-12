# 📚 Análisis de Base de Datos SQL - Estrategia de Lanzamiento
Este proyecto utiliza SQL para extraer información estratégica de una base de datos sobre libros, editoriales y reseñas, con el fin de fundamentar el lanzamiento de una nueva plataforma.

## 🎯 Objetivos del Proyecto
* Conectar y consultar una base de datos PostgreSQL mediante SQLAlchemy.
* Identificar los libros con mejores calificaciones y mayor volumen de reseñas.
* Analizar el rendimiento de las editoriales para definir el catálogo inicial de la plataforma.

## 🛠️ Tecnologías Utilizadas
* **SQL (PostgreSQL)**: Consultas complejas con JOINS, subconsultas y funciones de agregación.
* **Python**: Para la conexión a la base de datos y visualización rápida de resultados.
* **SQLAlchemy**: Como puente entre el código y la base de datos.

## 📊 Resultados Clave
* Se filtraron libros con más de 50 reseñas para garantizar la relevancia estadística.
* Se identificaron las 5 editoriales más exitosas por promedio de calificación.
* El análisis permitió segmentar los libros por "popularidad" vs "calidad", optimizando la selección de títulos para la nueva app.
