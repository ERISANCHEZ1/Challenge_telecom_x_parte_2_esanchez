# Challenge_telecom_x_parte_2_esanchez
# Telecom X – Predicción de Cancelación de Clientes (Churn)

## Descripción del proyecto
Este proyecto tiene como objetivo desarrollar un modelo de Machine Learning capaz de predecir la probabilidad de que un cliente cancele sus servicios (**Churn**) en la empresa Telecom X. La predicción temprana de cancelaciones permite a la empresa implementar estrategias de retención y mejorar la fidelización de clientes.

El análisis incluye:
- Preparación y limpieza de datos.
- Transformación de variables categóricas a formato numérico.
- Análisis exploratorio de datos (EDA) y visualización.
- Entrenamiento y evaluación de modelos predictivos.
- Identificación de las variables más importantes que afectan la cancelación.

## Dataset
El dataset utilizado contiene información histórica de clientes de Telecom X, incluyendo:
- Datos demográficos (edad, género, estado civil, etc.).
- Información de contratos y servicios.
- Cargos y consumos (`TotalCharges`, `DailyCharges`).
- Variable objetivo: `Churn` (1 = cliente canceló, 0 = cliente activo).

> Nota: Antes de entrenar los modelos, se realizó limpieza de datos, manejo de valores faltantes y codificación de variables categóricas.

## Tecnologías y librerías utilizadas
- **Python 3.x**
- **pandas** y **numpy** para manipulación de datos.
- **matplotlib** y **seaborn** para visualización.
- **scikit-learn** para modelos de Machine Learning:
  - Random Forest
  - Regresión Logística
  - Preprocesamiento: StandardScaler, SimpleImputer, train_test_split
- **Jupyter Notebook / Google Colab** para la ejecución del proyecto.

## Estructura del proyecto
