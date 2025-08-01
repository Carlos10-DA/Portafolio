🧪 Análisis A/B: Sistema de Recomendaciones

📊 Descripción del Proyecto
Este proyecto consiste en analizar los resultados de una prueba A/B llamada recommender_system_test, realizada por una tienda en línea internacional. La prueba tenía como objetivo evaluar un nuevo sistema de recomendaciones y su impacto en la conversión de los usuarios durante los primeros 14 días después del registro.

🧠 Objetivos
Evaluar la calidad de la prueba A/B y verificar si se realizó correctamente.

Medir la conversión en cada etapa del embudo: product_page → product_cart → purchase.

Comparar el desempeño entre el grupo de control (A) y el grupo experimental (B).

Determinar si hubo un aumento de al menos el 10% en cada etapa del embudo en el grupo B.

Usar pruebas estadísticas (z-test) para validar diferencias significativas.

🧰 Herramientas y Tecnologías
Python (pandas, numpy, matplotlib, seaborn, scipy), Jupyter Notebook

📁 Datasets
ab_project_marketing_events_us.csv: calendario de eventos de marketing.

final_ab_new_users_upd_us.csv: nuevos usuarios registrados del 7 al 21 de diciembre.

final_ab_events_upd_us.csv: eventos realizados por estos usuarios hasta el 1 de enero.

final_ab_participants_upd_us.csv: asignación de usuarios a grupos de prueba.

📌 Resultados Clave
Se verificó la integridad de la prueba A/B (participación, superposición, distribución).

Se analizó la conversión por etapa del embudo para cada grupo.

Se aplicaron pruebas estadísticas para evaluar diferencias en proporciones.



🧪 Pruebas de Hipótesis
H₀: No hay diferencia significativa entre las tasas de conversión de los grupos A y B.

H₁: Hay una diferencia significativa en la conversión a favor del grupo B.

Se utilizó prueba z para comparar proporciones entre grupos.
