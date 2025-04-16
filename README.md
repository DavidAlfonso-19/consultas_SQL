# 📚 Análisis de base de datos de libros electrónicos

Este proyecto consiste en la exploración y análisis de una base de datos relacional de una aplicación de libros electrónicos. El objetivo es responder preguntas clave sobre publicaciones, autores, editoriales y comportamiento de los usuarios a partir de consultas SQL.

## 🎯 Objetivo

- Responder preguntas relevantes del negocio.
- Identificar a los autores y editoriales más importantes.
- Analizar el comportamiento de los usuarios respecto a calificaciones y reseñas.

## 🧰 Tecnologías utilizadas

- SQL (PostgreSQL)
- Python (para conexión y visualización)
- SQLAlchemy
- Jupyter Notebook
- Pandas, Seaborn, Matplotlib

## 🔍 Consultas realizadas

- Número de libros publicados después del año 2000.
- Número de reseñas de usuarios y calificación promedio por libro.
- Editorial con mayor cantidad de libros (más de 50 páginas).
- Autor con mejor calificación promedio (mínimo 50 reseñas).
- Promedio de reseñas entre usuarios más activos.

## 📌 Conclusiones

- Desde el 1 de enero del 2000 se publicaron 819 libros.
- La correlación entre número de reseñas y calificación promedio es prácticamente nula, lo que indica que ambas variables son independientes.
- ‘Penguin Books’ es la editorial con más libros de más de 50 páginas, con un total de 42 publicaciones.
- Los autores J.K. Rowling y Mary GrandPré tienen el libro con la mejor calificación promedio: *Harry Potter and the Prisoner of Azkaban*.
- Los usuarios más activos generan en promedio 24 reseñas.

## 📎 Cómo ejecutarlo

1. Clonar este repositorio.
2. Abrir el notebook en Jupyter o Google Colab.
3. Tener acceso a la base de datos PostgreSQL indicada.
4. Ejecutar las celdas secuencialmente para reproducir el análisis.

## 🧠 Autor

David Gustavo Alfonso Torres  
[LinkedIn](https://www.linkedin.com/in/david-alfonso-24a197321/) | [GitHub](https://github.com/DavidAlfonso-19)
