Análisis y Predicción de Precios de Vehículos Usados
Este proyecto tiene como objetivo analizar un dataset de vehículos usados y construir modelos de regresión para predecir sus precios. El proceso incluye la carga y exploración de datos, limpieza y preprocesamiento, análisis exploratorio de datos (EDA), modelado y evaluación de modelos de regresión, y optimización del modelo seleccionado.

Contenido del Notebook
El cuaderno de Google Colab está organizado en las siguientes secciones:

1. Carga y Exploración de Datos:
Descargar y cargar el dataset.
Realizar una exploración inicial para entender la estructura del dataset.
Identificar valores faltantes, duplicados y outliers.
2. Limpieza y Preprocesamiento:
Manejar valores faltantes.
Eliminar duplicados.
Corregir inconsistencias en los datos categóricos.
Escalar las características numéricas.
Realizar transformaciones necesarias para las características categóricas.
3. Exploración de Datos:
Crear visualizaciones univariadas y multivariadas.
Calcular estadísticas descriptivas.
4. Modelado y Evaluación:
Implementar al menos dos modelos de regresión (Linear Regression y Random Forest Regressor).
Evaluar los modelos utilizando MSE, RMSE, y R^2.
Seleccionar el mejor modelo basado en las métricas de evaluación.
5. Optimización del Modelo:
Optimizar el modelo seleccionado utilizando GridSearchCV.
6. Documentación y Entrega:
Documentar todo el proceso en un archivo .ipynb claramente comentado.
Crear visualizaciones con interpretaciones.
Subir el archivo a un repositorio en GitHub con un tag de liberación.
Dataset
El dataset utilizado en este proyecto es vehicles.parquet. Contiene información sobre vehículos usados, incluyendo precio, año, fabricante, modelo, condición, etc.

Modelos Implementados
Se implementaron y evaluaron los siguientes modelos de regresión:

Regresión Lineal: Un modelo lineal simple para establecer una línea base.
Random Forest Regressor: Un modelo de ensamble basado en árboles de decisión, conocido por su buen rendimiento en una variedad de tareas de regresión.
Resultados
Los resultados de la evaluación de los modelos se presentan en las secciones correspondientes del notebook. Se compararon las métricas MSE, RMSE y R² para determinar el mejor modelo.

Optimización
El mejor modelo fue optimizado utilizando GridSearchCV para encontrar los mejores hiperparámetros.

Visualizaciones
El notebook incluye varias visualizaciones para explorar la distribución de las variables, la relación entre el precio y otras características, y la importancia de las características en el modelo final.

Uso
Para ejecutar este cuaderno:

Clona el repositorio de GitHub.
Abre el archivo .ipynb en Google Colab o Jupyter Notebook.
Asegúrate de tener el dataset vehicles.parquet en la ubicación especificada en el código o actualiza la ruta del archivo.
Ejecuta las celdas secuencialmente.
Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request.

Licencia
