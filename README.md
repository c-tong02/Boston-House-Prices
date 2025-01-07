# Boston-House-Prices

### Descripción del proyecto

El objetivo de este proyecto es predecir el valor promedio de viviendas en la ciudad de Boston, Estados Unidos. La data incluye variables demográficas, ambientales y cracterísitcas de las viviendas.

### Fuentes de dato

La base de datos utilizada para este proyecto se encuentra en el archivo "housing.csv", conteniendo registros de viviendas en Boston.

### Herramientas

- Python - EDA y modelamiento

### Limpieza / preparación de datos

En la fase inicial de preparación de datos, se hizo lo siguiente:
1. Carga de data e inspección.
2. Validación de datos nulos.
3. Análisis de correlación de variables.

### Modelamiento de datos

Se probaron diversos escaladores y modelos de Machine Learning para validar el mejor rendimiento para el proyecto.

- Escaladores: Standard Scaler, Min Max Scaler y Robust Scaler.
- Modelos: Regresión Lineal, Regresión Ridge, Regresión Lasso, Árbol de decisión, Random Forest y XGBoost.

### Resultados

Los resultados de este proyecto son:
1. El modelo con mejor rendimiento fue utilizando un escalador Robust Scaler y luego un modelo de XGBoost.
2. Se obtuvo un RMSE = 2.5574.
3. Se obtuvo un R2 = 0.91

