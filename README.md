### **Predicción de la Demanda de Taxis con Aprendizaje Automático**

**Introducción**

Este proyecto tiene como objetivo desarrollar un modelo de predicción capaz de anticipar la demanda de taxis para la empresa Sweet Lift Taxi. Utilizando técnicas de aprendizaje automático y análisis de series temporales, se busca optimizar la asignación de vehículos y mejorar la experiencia del usuario.


**Preprocesamiento de Datos**

* **Remuestreo:** Los datos originales se remuestrearon a intervalos de una hora para facilitar el análisis.
* **Ingeniería de Características:** Se generaron nuevas características como desfases y medias móviles para enriquecer el conjunto de datos.

**Modelado**

Se evaluaron diversos modelos de aprendizaje automático, incluyendo:

* **Regresión Lineal**
* **Árboles de Decisión**
* **Bosque Aleatorio**
* **CatBoost**
* **XGBoost**
* **LightGBM**

**Resultados**

* **Mejor Modelo:** LightGBM obtuvo el mejor rendimiento con un RMSE de 47.9092.
* **Métricas:** Se evaluaron los modelos utilizando métricas como el RMSE para medir la precisión de las predicciones.


**Conclusiones**

El modelo LightGBM demostró ser el más adecuado para predecir la demanda de taxis en este conjunto de datos. Los resultados obtenidos pueden utilizarse para optimizar la asignación de vehículos y mejorar la eficiencia operativa de Sweet Lift Taxi.
