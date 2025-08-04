# 📊 Telecom X – Análisis de Evasión de Clientes (Churn Analysis)

Este proyecto forma parte del desafío de especialización en Ciencia de Datos, donde se analiza la tasa de evasión de clientes de la empresa **Telecom X**. El objetivo es identificar los factores que influyen en la cancelación de servicios por parte de los usuarios, para aportar estrategias que mejoren la retención.

---

## 🧠 Objetivo

Analizar el comportamiento de los clientes de Telecom X para detectar patrones y variables relacionadas con la **evasión (churn)** y proponer soluciones basadas en datos.

---

## 📁 Estructura del Proyecto

- `Challenge_TelecomX_Latam.ipynb`: notebook principal con todo el flujo de trabajo.
- `TelecomX_Data.json`: archivo original con los datos en formato anidado.
- `TelecomX_diccionario.md`: diccionario de datos oficial con la descripción de cada columna.

---

## 🧪 Instrucciones de uso

1. Clona o descarga este repositorio en tu equipo.
2. Abre el archivo `Challenge_TelecomX_Latam.ipynb` en Google Colab.
3. Ejecuta las celdas del notebook en orden, desde la carga de datos hasta el informe final.
4. Asegúrate de tener conexión a internet para acceder al archivo `.json` desde la URL proporcionada.
5. Las bibliotecas `pandas`, `numpy`, `matplotlib`, `seaborn` y `plotly` ya están preinstaladas en Colab. No es necesario instalar nada adicional.

---

## 🔍 Pasos realizados

1. **Carga y normalización de datos** desde archivo `.json`.
2. Aplicación de procesos **ETL (Extracción, Transformación y Carga)**:
   - Conversión de columnas numéricas mal tipadas.
   - Transformación de variables categóricas y booleanas.
   - Manejo de valores nulos y outliers.
3. **Análisis Exploratorio de Datos (EDA)**:
   - Estadísticas descriptivas.
   - Gráficos comparativos entre `Churn` y otras variables.
4. **Visualizaciones personalizadas** con Matplotlib, Seaborn y Plotly.
5. Generación de **insights accionables y recomendaciones** para la empresa.

---

## 📌 Principales hallazgos

- La mayoría de los abandonos ocurre en los **primeros 6 meses** del cliente.
- El tipo de contrato mensual está fuertemente relacionado con una **alta tasa de churn**.
- Clientes con servicios adicionales (streaming, soporte, protección) tienen mayor permanencia.
- El **método de pago automático** está asociado con menor evasión.
- Personas mayores de 65 años tienen una tasa ligeramente más alta de cancelación.

---

## 📈 Herramientas utilizadas

- **Python**
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `requests`
- Google Colab

---

## 💡 Lecciones aprendidas

- Aplicación de técnicas de limpieza de datos reales con estructuras anidadas.
- Importancia del análisis visual para detectar patrones de comportamiento.
- Cómo transformar un conjunto de datos crudo en información estratégica para la toma de decisiones.

---

## 🤝 Agradecimientos

Este proyecto fue realizado por **Lady Soto Dávila** como parte del programa de formación **ONE (Oracle Next Education)** en la especialidad de **Data Science** con [Alura LATAM](https://www.aluracursos.com/) y [Oracle Next Education](https://www.oracle.com/lad/education/oracle-next-education/).

---

## 📬 Contacto

Puedes encontrarme en:
- [LinkedIn](https://www.linkedin.com/in/lady-soto-davila-dev/)
- [GitHub](https://github.com/LadySoto)

---
