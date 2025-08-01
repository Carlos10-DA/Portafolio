🟦 Proyecto 8: Embudo de Conversión y Test A/A/B

Embudo de Conversión y Test A/A/B

📊 Descripción del Proyecto
Este proyecto tiene como objetivo comprender el comportamiento de los usuarios en una aplicación de venta de productos alimenticios. Se estudia el embudo de conversión y se analiza un experimento A/A/B para evaluar el impacto del rediseño de tipografías en la experiencia del usuario.

🧠 Objetivos
Analizar los eventos generados por los usuarios dentro de la app.

Construir el embudo de conversión completo y detectar puntos de pérdida.

Evaluar la consistencia de los grupos A/A y el efecto del nuevo diseño tipográfico (grupo B).

🧰 Herramientas y Tecnologías
Python (pandas, matplotlib, seaborn, scipy), Jupyter Notebook

📁 Dataset
logs_exp_us.csv: Registro de eventos con identificador de usuario, timestamp, nombre de evento y grupo experimental.

📌 Resultados Clave
Se identificó el embudo de conversión y la etapa con mayor abandono.

Se confirmó que los grupos A/A eran consistentes estadísticamente.

No se observaron mejoras significativas en el grupo con el nuevo diseño (fuente), lo que sugiere que el cambio no afecta la conversión.

🧪 Prueba A/A/B
Se realizaron pruebas estadísticas por evento para cada grupo (control-control y control-experimental).

Se ajustó el nivel de significancia (corrección por múltiples pruebas).

Se validó la consistencia del experimento y la neutralidad del rediseño.
