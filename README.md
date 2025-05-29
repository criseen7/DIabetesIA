# 🩺 Predicción de Diabetes con Regresión Logística

Este proyecto realiza un análisis exploratorio de datos (EDA) y aplica un modelo de regresión logística para predecir la presencia de diabetes en pacientes, utilizando el conjunto de datos `diabetes.csv`.

---

## 📁 Estructura del Proyecto

```
DIabetesIA/
├── DiabetesIA.ipynb       # Notebook con análisis y modelado
├── diabetesia.py          # Script con funciones clave
├── diabetes.csv           # Conjunto de datos utilizado
├── README.md              # Documentación del proyecto
└── LICENSE                # Licencia Apache 2.0
```

---

## ⚙️ Requisitos

Instala las siguientes librerías con pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

O usa el archivo `requirements.txt` incluido.

---

## 🚀 Ejecución

### Opción 1: Usando el Notebook

Abre `DiabetesIA.ipynb` en Jupyter y ejecuta las celdas paso a paso.

### Opción 2: Usando el script

Ejecuta desde la terminal:

```bash
python diabetesia.py
```

---

## 📊 Resultados

El análisis incluye:

- Histogramas de variables como `Pregnancies`, `BMI` y `Age`.
- Matriz de correlación.
- Entrenamiento de un modelo de regresión logística con evaluación (accuracy, matriz de confusión).

---

## 📄 Licencia

Este proyecto está bajo la Licencia Apache 2.0. Consulta el archivo `LICENSE` para más detalles.

---