🟦 Proyecto : Análisis SQL de Libros, Autores y Editoriales

Análisis de Base de Datos de Libros con SQL

📊 Descripción del Proyecto En este proyecto, analizamos una base de datos de un servicio digital de lectura que surgió durante la pandemia de COVID-19. El objetivo es comprender el comportamiento de los usuarios, identificar editoriales y autores destacados, y generar información de valor para diseñar un nuevo producto digital enfocado en libros y reseñas.

🧠 Objetivos Contar libros publicados desde el año 2000.

Calcular calificación promedio y cantidad de reseñas por libro.

Identificar la editorial con más libros de más de 50 páginas.

Encontrar al autor con mejor calificación (con mínimo 50 valoraciones).

Analizar el comportamiento de usuarios activos con muchas calificaciones.

🧰 Herramientas y Tecnologías SQL (PostgreSQL), Python (pandas para visualización de resultados), Jupyter Notebook

📁 Tablas de la Base de Datos books: Información general de los libros.

authors: Datos de los autores.

publishers: Información de editoriales.

ratings: Calificaciones de usuarios por libro.

reviews: Reseñas escritas por los usuarios.

📌 Resultados Clave Se identificó la cantidad de libros publicados después del 1 de enero de 2000.

Se calculó el número de reseñas y calificaciones promedio por título.

Se determinó la editorial con mayor volumen de libros "relevantes" (más de 50 páginas).

Se identificó al autor con mejor promedio de calificaciones, considerando un mínimo de 50 ratings.

Se observó que los usuarios más activos escriben más reseñas de texto que el promedio.

🧪 Consultas SQL Realizadas Filtrado por fecha de publicación (publication_date).

Agregaciones por libro (COUNT, AVG) para calificaciones y reseñas.

Uso de JOIN entre tablas (books, ratings, reviews, etc.).

Agrupamiento y ordenamiento por author, publisher y username.
