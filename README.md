# credit-risk-analysis
## Descripción del proyecto
Este proyecto tiene como objetivo desarrollar un modelo de machine learning para predecir la probabilidad de incumplimiento de crédito. Se aplica un enfoque orientado al análisis financiero, priorizando la detección de clientes de alto riesgo mediante el uso de métricas adecuadas para datos desbalanceados.
## Objetivo
Construir un modelo de clasificación que permita identificar clientes con alta probabilidad de impago, apoyando la toma de decisiones en procesos de otorgamiento de crédito.
## Tecnologias utilizadas
Python, Pandas, NumPy, Scikit-Learn, Matplotlib
## Metodología
1. Limpieza y Preparación de Datos
  - Tratamiento de valores nulos.
  - Transformación de variables categóricas.
  - Análisis exploratorio de datos (EDA).
2. Análisis del Problema
  - Identificación de desbalance de clases.
  - Evaluación de distribución de variable objetivo.
3. Modelado
  - Implementación de Logistic Regression.
  - Uso de class_weight='balanced' para mitigar desbalance.
4. Evaluación del Modelo
  - Matriz de confusión.
  - Precisión, Recall y F1-score.
  - Análisis de falsos positivos y falsos negativos.
  - Interpretación desde perspectiva financiera.
## Resultados Relevantes
  - Mejora significativa en la detección de clientes de alto riesgo.
  - Recall de la clase minoritaria superior al 60%.
  - Reducción considerable de falsos negativos en comparación con modelo inicial.
  - Modelo orientado a minimizar pérdidas potenciales por incumplimiento.
## Efoque de negocio
En riesgo crediticio, no basta con maximizar la accuracy. El modelo fue optimizado priorizando la reducción de falsos negativos, dado que aprobar un cliente moroso genera mayor impacto financiero que rechazar un cliente solvente.
## Conclusiones
  - Comparación con modelos adicionales (Random Forest, Gradient Boosting).
  - Optimización de umbral de clasificación.
  - Implementación de validación cruzada.
  - Incorporación de análisis de importancia de variables.
