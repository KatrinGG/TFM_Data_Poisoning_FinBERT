# TFM_Data_Poisoning_FinBERT

Este repositorio contiene el código desarrollado para el Trabajo Fin de Máster sobre "Evaluación de la robustez de modelos de lenguaje de gran tamaño frente a ataques de envenenamiento de datos en la detección de fraude financiero".  

El objetivo es analizar la robustez de **FinBERT Pretrain** frente a distintos ataques de envenenamiento de datos (label flipping aleatorio y dirigido, feature poisoning y backdoor triggers) en un escenario realista de detección de fraude financiero con fuerte desbalance de clases.

Se incluyen scripts y notebooks para:
- Preparación y limpieza de datos.  
- Entrenamiento del modelo base y escenarios envenenados.  
- Evaluación mediante métricas (F1, precisión, recall, PR-AUC, ROC-AUC, Brier, Recall@5%).
- Balanceo de la clase minoritaria con SMOTE y aplicación de los ataques sobre el dataset balanceado.  
- Generación de gráficos y tablas de resultados.  

Librerías principales utilizadas:
- transformers
- torch
- scikit-learn
- imblearn
- pandas
- matplotlib
