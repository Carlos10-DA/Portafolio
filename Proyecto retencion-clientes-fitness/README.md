🟦 Proyecto : Predicción de Cancelación y Segmentación de Clientes


Análisis de Pérdida de Clientes en Gimnasios


📊 Descripción del Proyecto
En este proyecto, analizamos los perfiles de clientes de la cadena de gimnasios Model Fitness para entender los factores detrás de la pérdida de clientes (churn) y predecir qué clientes tienen mayor probabilidad de cancelar su membresía. También segmentamos a los usuarios en grupos mediante clustering para diseñar estrategias personalizadas de retención.

🧠 Objetivos
Predecir la probabilidad de cancelación de cada cliente en el próximo mes.

Identificar patrones comunes en clientes que se quedan o se van.

Analizar los factores que más influyen en la cancelación.

Agrupar clientes en clústeres con características similares para guiar acciones de marketing.

🧰 Herramientas y Tecnologías
Python (pandas, matplotlib, seaborn, scikit-learn, scipy), Jupyter Notebook

📁 Dataset
gym_churn_us.csv: Datos demográficos, comportamiento de uso y gasto de clientes del gimnasio.

📌 Resultados Clave
El modelo de bosque aleatorio tuvo mejor desempeño que la regresión logística (mayor precisión y recall).

Se identificaron características clave como lifetime, contract_period, frequency y gastos adicionales como determinantes de la cancelación.

Los clústeres permitieron identificar grupos con alto riesgo de abandono, como usuarios con baja frecuencia y contratos mensuales.

Se formularon recomendaciones específicas de retención para cada segmento de cliente.

🧪 Prueba de Modelado y Clustering
Se entrenaron modelos de clasificación binaria para predecir la variable Churn.

Se evaluaron mediante precisión, recall y accuracy.

Se aplicó K-means para crear 5 clústeres de usuarios y analizar su comportamiento.

Se identificaron los clústeres con mayor y menor tasa de cancelación para priorizar acciones.
