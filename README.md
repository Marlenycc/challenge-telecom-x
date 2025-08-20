# Telecom X - Análisis de Evasión de Clientes

## 📌 Descripción

Este proyecto analiza los datos de clientes de **Telecom X** para entender los factores asociados a la evasión (churn).  
El objetivo es identificar patrones que ayuden a la empresa a reducir la pérdida de clientes.

## 📂 Contenido del proyecto

- **TelecomX_Analisis.ipynb**: cuaderno con todo el proceso de análisis.
- **Datos**: los datos se cargan automáticamente desde la API pública de GitHub en formato JSON.

## 🛠️ Tecnologías utilizadas

- Python 3
- Pandas
- Matplotlib / Seaborn

## 📊 Flujo de trabajo

1. Importación de datos desde la API.
2. Exploración y comprensión del dataset.
3. Limpieza y tratamiento de datos (valores nulos, duplicados, categorías).
4. Creación de nuevas variables (ej. `Cuentas_Diarias`).
5. Análisis descriptivo (métricas estadísticas).
6. Distribución de evasión (`churn`).
7. Relación de `churn` con variables categóricas y numéricas.
8. Informe con conclusiones y recomendaciones.

## ▶️ Cómo ejecutar

1. Abrir el archivo `TelecomX_Analisis.ipynb` en Google Colab o Jupyter Notebook.
2. Ejecutar las celdas en orden.
3. Los datos se descargarán automáticamente desde la API.

## 📝 Conclusión

El análisis ofrece insights sobre los factores que influyen en la cancelación del servicio, lo cual puede servir como base para el desarrollo de modelos predictivos y estrategias de retención.
