# 🧹 Proyecto de Limpieza y Diagnóstico de Datos

> Proyecto colaborativo desarrollado dentro del **Bootcamp de Data Analytics**. El objetivo principal es llevar a cabo una auditoría, exploración inicial, diagnóstico y proceso de limpieza profunda sobre conjuntos de datos en formato CSV para dejarlos optimizados y listos para su análisis en un `DataFrame` de Pandas.

---

## 📌 Objetivos del Proyecto

1. **Exploración Inicial:** Inspeccionar el volumen, la estructura general, nombres de columnas y tipos de datos cargados preliminarmente.
2. **Diagnóstico de Calidad de Datos:**
   * Identificación y porcentaje de valores nulos o faltantes (`NaN`).
   * Detección de registros duplicados a nivel general e identificador único.
   * Detección de inconsistencias en variables categóricas (espacios en blanco, tipografía, tildes).
   * Identificación de valores atípicos (*outliers*) y errores de rango en variables numéricas.
3. **Limpieza y Transformación:** Imputación/eliminación de nulos, estandarización de columnas, normalización de cadenas de texto y conversión de tipos de datos (especialmente fechas con `pd.to_datetime`).
4. **Validación:** Comprobación mediante gráficas de la transformación realizada.
4. **Exportación:** Generación de un conjunto de datos limpio (*Clean Dataset*) en formato CSV listo para la fase de análisis exploratorio (EDA).

---

## 📊 Dataset Utilizado
Para este proyecto, trabajaremos con el dataset **"cafe"** que contiene información sobre las ventas realizadas en una tienda.

- **Dataset principal**: [Descargar dataset cafe](https://docs.google.com/spreadsheets/d/1IyCki7pOA8BH7cXYhSn5Rvu2KT58u4TG/edit?usp=drive_link&ouid=110279074755235998253&rtpof=true&sd=true)

---

## 🛠️ Tecnologías y Librerías Utilizadas

* **Lenguaje:** Python 3.x
* **Entorno de Trabajo:** Google Colab / Jupyter Notebooks
* **Librerías Principales:**
  * `pandas`: Manipulación, diagnóstico y limpieza de datos estructurados.
  * `numpy`: Operaciones matriciales y manejo de valores nulos (`np.nan`).
  * `matplotlib` / `seaborn`: Visualización gráfica del diagnóstico de datos (matrices y curvas de nulos).
* **Control de versiones:** GitHub

---

## 📂 Estructura del Repositorio

```text
├── data/
│   ├── raw/              # Archivos CSV originales (sin modificar)
│   └── processed/        # Archivos CSV limpios y listos para producción
├── notebooks/            # Notebooks de exploración y limpieza (.ipynb)
├── src/                  # Funciones auxiliares o scripts de limpieza (.py)
├── .gitignore            # Archivos excluidos del control de versiones
├── requirements.txt      # Dependencias del proyecto
└── README.md             # Documentación del repositorio