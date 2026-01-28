# 📊 Telecom X LATAM — Análisis de Churn (Evasión de Clientes)

Este repositorio contiene un **proyecto completo de análisis exploratorio de datos (EDA)**, limpieza, estandarización y preparación de datos para estudiar la **evasión de clientes (Churn)** en la empresa ficticia **Telecom X**.

El objetivo es **identificar los factores que influyen en la cancelación de servicios**, generar **insights estratégicos** y dejar el dataset **listo para un futuro modelo predictivo**.

---

## 🧠 Objetivo del proyecto

- Extraer datos desde una fuente en formato **JSON (API)**
- Normalizar (aplanar) un JSON anidado a formato tabular
- Limpiar y tratar:
  - valores nulos
  - valores vacíos
  - errores de formato
  - inconsistencias en categorías
- Estandarizar y traducir variables categóricas
- Crear nuevas variables (feature engineering), por ejemplo:
  - **Cuentas_Diarias** = valor mensual / 30
- Realizar **Análisis Exploratorio de Datos (EDA)** con visualizaciones
- Identificar **patrones asociados al Churn**
- Generar **conclusiones y recomendaciones de negocio**

---

## 📦 Dataset

- Fuente: JSON alojado en GitHub (consumido directamente desde el notebook).
- El dataset contiene información sobre:
  - Datos del cliente
  - Servicios de internet y telefonía
  - Tipo de contrato
  - Método de pago
  - Facturación
  - Variable objetivo: **Churn (cancelación del servicio)**

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab

---

## 📁 Contenido del repositorio

- `TelecomX_LATAM.ipynb`  
  → Notebook principal que contiene:
  - Extracción de datos
  - Normalización del JSON
  - Limpieza y estandarización
  - Análisis exploratorio de datos (EDA)
  - Visualizaciones
  - Conclusiones y recomendaciones
