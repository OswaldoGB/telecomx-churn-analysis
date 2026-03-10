📊 TelecomX LATAM — Análisis de Evasión de Clientes (Churn)
📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar el fenómeno de evasión de clientes (Churn) en la empresa ficticia TelecomX, utilizando técnicas de análisis de datos con Python.

El análisis busca identificar patrones en el comportamiento de los clientes que permitan comprender por qué algunos deciden cancelar el servicio. Estos insights pueden ayudar a la empresa a diseñar estrategias de retención más efectivas.

El proyecto forma parte de un desafío de análisis de datos, donde se aplican procesos de extracción, limpieza, exploración y visualización de datos.

🎯 Objetivos

Analizar la distribución de clientes que abandonan el servicio.

Identificar factores asociados al churn.

Explorar patrones relacionados con contratos, métodos de pago y cargos mensuales.

Generar visualizaciones claras que permitan interpretar los resultados.

🔗 Fuente de los Datos

Los datos fueron obtenidos desde una API en formato JSON:

Dataset:
https://github.com/ingridcristh/challenge2-data-science-LATAM

Los datos contienen información sobre:

Datos demográficos de clientes

Servicios contratados

Tipo de contrato

Método de pago

Facturación

Estado de churn

⚙️ Tecnologías Utilizadas

El análisis fue realizado utilizando:

Python

Pandas → manipulación y análisis de datos

Matplotlib → visualización de datos

Seaborn → gráficos estadísticos

Jupyter Notebook → desarrollo del análisis

🧹 Limpieza y Preparación de Datos

Antes de realizar el análisis se aplicaron varias etapas de tratamiento de datos:

Importación de datos desde la API en formato JSON.

Normalización de la estructura del JSON para convertirlo en un DataFrame.

Revisión de valores nulos y duplicados.

Conversión de variables a tipos de datos adecuados.

Corrección de inconsistencias en columnas numéricas.

Creación de la variable Cuentas_Diarias a partir de la facturación mensual.

Estas transformaciones permitieron preparar los datos para el análisis exploratorio.

📊 Análisis Exploratorio de Datos

Durante el análisis se exploraron diferentes variables para comprender su relación con la evasión de clientes.

Se realizaron visualizaciones para analizar:

Distribución de churn

Churn según género

Churn según tipo de contrato

Churn según método de pago

Churn según tipo de servicio de internet

Relación entre cargos mensuales y churn

Estas visualizaciones ayudaron a identificar patrones relevantes en el comportamiento de los clientes.

🔎 Principales Hallazgos

Entre los insights más relevantes se identificó que:

Los clientes con contratos mensuales presentan una mayor tasa de evasión.

Algunos métodos de pago concentran más clientes que abandonan el servicio.

Los clientes con cargos mensuales más altos tienden a presentar mayor probabilidad de churn.

El tipo de servicio contratado puede influir en la permanencia del cliente.

💡 Recomendaciones

A partir del análisis realizado se sugieren las siguientes acciones:

Incentivar contratos de mayor duración para mejorar la retención.

Analizar estrategias de precios para clientes con cargos elevados.

Diseñar campañas de fidelización dirigidas a clientes con mayor riesgo de abandono.

Evaluar los métodos de pago asociados a mayor churn.

🚀 Posibles Mejoras Futuras

Este análisis podría ampliarse mediante:

Modelos de Machine Learning para predicción de churn.

Análisis de correlación entre variables.

Segmentación de clientes mediante clustering.

Creación de dashboards interactivos con Power BI o Tableau.

👨‍💻 Autor
Proyecto desarrollado por Oswaldo Guevara como parte de un desafío de Análisis de Datos con Python.
