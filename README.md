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


## Proceso de análisis
1. **Carga y limpieza de datos:** eliminación de columnas irrelevantes y tratamiento de valores faltantes.  
2. **Codificación de variables categóricas:** uso de one-hot encoding y conversión de booleanos a enteros.  
3. **Análisis exploratorio:** visualización de distribuciones, boxplots y matriz de correlación.  
4. **Preparación de datos para modelos:** división en entrenamiento y prueba, normalización de variables cuando es necesario.  
5. **Entrenamiento de modelos predictivos:** Random Forest y Regresión Logística.  
6. **Evaluación de modelos:** exactitud, precisión, recall, F1-score y matriz de confusión.  
7. **Análisis de importancia de variables:** identificación de factores clave que influyen en la cancelación.  
8. **Conclusiones y recomendaciones:** estrategias de retención basadas en los resultados del modelo.

## Resultados clave
- Exactitud de los modelos: ~78-79%.
- Variables más influyentes: `Tenure`, `TotalCharges`, `Contract`, `NumServicios`, `PaymentMethod`.
- Estrategias de retención sugeridas:
  - Incentivar contratos más largos.
  - Programas de bienvenida y seguimiento para clientes nuevos.
  - Promover métodos de pago automáticos.
  - Soporte proactivo para clientes con servicios de fibra óptica.
  - Paquetes personalizados para clientes de alto valor.

## Cómo ejecutar el proyecto
1. Clonar el repositorio:
```bash
git clone https://github.com/tu-usuario/telecom-x-churn.git

