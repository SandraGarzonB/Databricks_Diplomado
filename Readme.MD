# Procesamiento de Datos Abiertos de Colombia en Databricks

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo principal la descarga, procesamiento y análisis de datos abiertos del gobierno colombiano. Se utilizarán dos conjuntos de datos oficiales provenientes del portal [datos.gov.co](https://www.datos.gov.co/) y se cargarán en una instancia de **Databricks** para su análisis posterior.

## 📂 Datasets Utilizados

1. **SECOP I - Contratos del Estado**
   - 📎 URL: [https://www.datos.gov.co/resource/rpmr-utcd.csv](https://www.datos.gov.co/resource/rpmr-utcd.csv)
   - 📝 Descripción: Información relacionada con contratos públicos en Colombia registrados en el Sistema Electrónico para la Contratación Pública (SECOP).

2. **MEN - Matrícula por Establecimiento Educativo**
   - 📎 URL: [https://www.datos.gov.co/resource/nudc-7mev.csv](https://www.datos.gov.co/resource/nudc-7mev.csv)
   - 📝 Descripción: Datos del Ministerio de Educación Nacional sobre la matrícula escolar por establecimiento educativo a nivel nacional.

## 🎯 Objetivos

- Descargar y explorar los conjuntos de datos desde sus fuentes oficiales.
- Realizar limpieza y transformación de los datos según las necesidades del análisis.
- Subir los datos procesados a una instancia de **Databricks**.
- Preparar los datos para análisis posterior (consultas, visualizaciones, modelos predictivos, etc.).

## 🛠️ Tecnologías Utilizadas

- Python (pandas, requests)
- Apache Spark (mediante Databricks)
- Databricks Community Edition
- Jupyter Notebook (opcional)

## 🗂️ Estructura del Proyecto
📁 datasets/
    ├── contratos_secop.csv
    └── matriculas_men.csv
📁 scripts/
    └── procesamiento_datos.py
📁 notebooks/
    └── analisis_databricks.ipynb

## 🧾 Créditos

- [SECOP - Colombia Compra Eficiente](https://www.colombiacompra.gov.co/)
- [Ministerio de Educación Nacional](https://www.mineducacion.gov.co/)
- [datos.gov.co](https://www.datos.gov.co/)

## 📄 Licencia

Este proyecto utiliza datos abiertos bajo licencias públicas. El código fuente es distribuido bajo la licencia MIT.
