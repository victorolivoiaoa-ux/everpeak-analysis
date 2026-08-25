# EverPeak Retail: Pipeline de Limpieza, EDA y Segmentación

Este repositorio contiene el análisis integral y pipeline de procesamiento de datos desarrollado para el caso de negocio **EverPeak–SilverBasket**.

El conjunto de datos `everpeak_retail` simula registros reales de comercio minorista (2,000 órdenes), presentando desafíos comunes de calidad de datos como valores centinela, inconsistencias en tipos de datos, valores nulos y registros atípicos.

---

## 🚀 Ejecutar en Google Colab

Puedes abrir y ejecutar el entorno de análisis directamente en la nube haciendo clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1U_9OSUG27l8v-jJy778Z9lh4wZDoxr00)

---

## 📂 Contenido del Repositorio

* `everpeak_analysis.ipynb`: Cuaderno principal estructurado con el pipeline modular de preprocesamiento, análisis exploratorio de datos (EDA), visualizaciones estadísticas, detección de anomalías y segmentación de clientes.
* `README.md`: Documentación técnica del proyecto, contexto del negocio e instrucciones de reproducción.

---

## 🎯 Objetivos y Alcance del Análisis

1. **Diagnóstico de Calidad:** Identificación de nulos, inconsistencias en campos de fecha (año 2026) y cardinalidad de variables categóricas.
2. **Pipeline Modular de Limpieza:**
   * Estandarización de cadenas de texto (`str.strip()`).
   * Tratamiento y aislamiento de valores centinela (`-999, 999, 0, -1`).
   * Conversión robusta de tipos numéricos e imputación estadística.
3. **Análisis Exploratorio (EDA):** Comparación descriptiva de comportamiento de compra por ciudades principales (*New York*, *Los Angeles*, *Chicago*) y categorías de producto.
4. **Detección de Outliers:** Identificación formal de anomalías en gasto (`order_value`) y precio (`price`) mediante **Rango Intercuartílico (IQR)** y **Z-Score** ($|z| > 3$).
5. **Segmentación de Clientes:** Creación de reglas de negocio basadas en volumen de compra, grupos de edad y métodos de pago para optimización comercial.

---

## 🛠️ Tecnologías y Librerías Utilizadas

* **Lenguaje:** Python 3.x
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Entorno:** Google Colab / Jupyter Notebooks

---

## 📘 Instrucciones para Reproducir el Análisis

1. Abre el cuaderno haciendo clic en el badge de **Open in Colab** en la parte superior.
2. En la barra superior de Colab, selecciona **Entorno de ejecución** > **Ejecutar todo** (`Ctrl + F9` o `Cmd + F9`).
3. El script descargará automáticamente el dataset público y ejecutará el pipeline secuencialmente sin requerir configuración adicional.


# everpeak-analysis##

# EverPeak Retail: Pipeline de Limpieza, EDA y Segmentación

Este repositorio contiene el análisis integral y pipeline de procesamiento de datos desarrollado para el caso de negocio **EverPeak–SilverBasket**.

El conjunto de datos `everpeak_retail` simula registros reales de comercio minorista (2,000 órdenes), presentando desafíos comunes de calidad de datos como valores centinela, inconsistencias en tipos de datos, valores nulos y registros atípicos.

---
▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1U_9OSUG27l8v-jJy778Z9lh4wZDoxr00)
