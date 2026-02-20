# 📡 Telecom X – Análisis de Churn (ETL + EDA)

## 📌 Descripción del Proyecto

Este proyecto corresponde al Challenge de Ciencia de Datos enfocado en el análisis de evasión de clientes (**Churn**) para Telecom X.

El objetivo principal fue desarrollar un proceso completo de **ETL (Extract, Transform, Load)** utilizando Python, para limpiar, estructurar y analizar datos provenientes de una API.  

El análisis tiene como finalidad identificar patrones asociados al abandono de clientes y preparar los datos para un futuro modelo predictivo.

---

## 🎯 Objetivos

- Extraer datos desde una API en formato JSON.
- Normalizar estructuras anidadas.
- Limpiar y transformar variables.
- Realizar análisis exploratorio de datos (EDA).
- Identificar factores asociados al churn.
- Elaborar conclusiones estratégicas basadas en datos.

---

## 🛠️ Tecnologías Utilizadas

- **Python**
- **Pandas**
- **Requests**
- **Seaborn**
- **Matplotlib**
- **Google Colab**
- **Git / GitHub**

---

## 🔄 Proceso ETL

### 📌 Extracción
Los datos fueron obtenidos desde una API en formato JSON y convertidos a un DataFrame utilizando `requests` y `pandas`.

### 🔧 Transformación
- Normalización de estructuras anidadas con `json_normalize()`.
- Limpieza de nombres de columnas.
- Conversión de tipos de datos.
- Tratamiento de valores nulos.
- Creación de nuevas variables (feature engineering).
- Codificación de variables binarias.

### 📊 Carga y Análisis Exploratorio

Se realizaron análisis descriptivos y visualizaciones para:

- Calcular tasa general de churn.
- Analizar cargos totales según churn.
- Evaluar meses de servicio.
- Comparar tipo de contrato y método de pago.
- Analizar correlaciones entre variables numéricas.

---

## 📈 Principales Hallazgos

- El churn se concentra principalmente en clientes recientes.
- Los contratos mensuales presentan mayor tasa de abandono.
- Clientes con menor gasto acumulado muestran mayor probabilidad de evasión.
- La antigüedad del cliente es un factor determinante en la retención.

---

## 🚀 Conclusión

El análisis permitió identificar patrones claros asociados al abandono de clientes, proporcionando una base sólida para el desarrollo de modelos predictivos que permitan anticipar el churn y diseñar estrategias de retención más efectivas.
