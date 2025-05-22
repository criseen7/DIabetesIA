Análisis exploratorio de datos (EDA) y prueba de modelo con regresión logística.
Histogramas

Los histogramas de variables como Pregnancies, BMI, Age muestran la distribución y ayudan a identificar sesgos o valores atípicos.


📈 Matriz de Correlación

Visualización de variables se relacionan más con el resultado (Outcome). 


⚙️ Preprocesamiento

✅ División de datos:

train_test_split() con 20% para prueba.


✅ Escalamiento:

Escalar x antes de entrenar el modelo es esencial para que las variables estén en la misma escala.

✅ Entrenamiento:


Intercepto y coeficientes te ayudan a interpretar la influencia de cada variable.


📊 Evaluación del Modelo

✅ Predicción:

y_pred generado sin errores.


✅ Matriz de Confusión:

Visualización clara con sns.heatmap.


✅ Clasificación:

Precisión global del 76%.


Observaciones:

Clase 0 (no diabético): 82% de F1.


Clase 1 (diabético): solo 62% de F1.
