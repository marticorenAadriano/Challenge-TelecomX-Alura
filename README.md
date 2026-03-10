# Challenge-TelecomX-Alura
Primera parte telecomX
Telecom X – Predicción de Cancelación de Clientes (Churn)

Este proyecto forma parte del challenge de Data Science de **Alura LATAM**.  
El objetivo es desarrollar modelos de Machine Learning capaces de predecir qué clientes tienen mayor probabilidad de cancelar los servicios de Telecom X.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Objetivo del Proyecto

Construir un modelo predictivo que permita identificar clientes con riesgo de cancelación (churn), permitiendo a la empresa implementar estrategias de retención basadas en datos.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Estructura del Proyecto

TelecomX_Churn_Prediccion/

│

├── TelecomX_LATAM_Alura.ipynb # Parte 1 - Limpieza y análisis exploratorio

├── TelecomX_Modelos.ipynb # Parte 2 - Modelos de Machine Learning

├── telecomx_clean.csv # Dataset limpio utilizado para el modelado

└── README.md # Descripción del proyecto

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Metodología

El proyecto se desarrolló en dos etapas principales:

#Preparación de datos

- Limpieza y estandarización del dataset
- Eliminación de variables irrelevantes
- Codificación de variables categóricas (One Hot Encoding)
- Análisis de correlación entre variables

# Modelado predictivo

Se entrenaron dos modelos de clasificación:

- **Regresión Logística**
- **Random Forest**

Los datos se dividieron en:

- 80% entrenamiento
- 20% prueba

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 Evaluación de Modelos

Los modelos fueron evaluados utilizando las siguientes métricas:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión

#Resultados obtenidos

| Modelo | Accuracy |
|------|------|
| Regresión Logística | 81.27% |
| Random Forest | 78.99% |

El modelo de **Regresión Logística presentó mejor desempeño general**, especialmente en la detección de clientes con riesgo de cancelación.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 Principales factores que influyen en el churn

El análisis identificó algunos factores importantes asociados a la cancelación:

- Tipo de contrato
- Antigüedad del cliente (tenure)
- Cargos mensuales
- Servicios adicionales contratados

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Estrategias de negocio propuestas

A partir de los resultados del modelo se proponen las siguientes estrategias:

- Incentivar contratos de largo plazo
- Programas de fidelización para nuevos clientes
- Optimización de planes y precios
- Promoción de servicios adicionales
- Uso del modelo predictivo para acciones preventivas

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Conclusión

El uso de modelos de Machine Learning permite anticipar la cancelación de clientes y aplicar estrategias de retención de forma proactiva.

La implementación de estas herramientas puede ayudar a **reducir la tasa de churn y mejorar la rentabilidad de la empresa**.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Autor

Proyecto desarrollado por **Adriano** como parte del challenge de Data Science de Alura LATAM.
