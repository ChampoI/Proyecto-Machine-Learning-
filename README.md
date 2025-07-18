# 📊 Predicción Urbana con Machine Learning y Análisis Geoespacial — Bucaramanga 🇨🇴

Este proyecto presenta un pipeline de análisis predictivo y visualización de datos urbanos enfocado en la ciudad de **Bucaramanga, Colombia**. A través de herramientas como **Python**, **QGIS** y **Tableau**, se construyen modelos de predicción y visualizaciones interactivas para apoyar decisiones basadas en datos.

---

## 🧠 Objetivos Principales

- Limpiar y transformar datos urbanos históricos.
- Realizar análisis exploratorio y multivariable.
- Entrenar modelos predictivos para anticipar tendencias.
- Georreferenciar resultados sobre el mapa urbano de Bucaramanga.
- Comunicar hallazgos a través de dashboards interactivos.

---

## 🗂 Estructura del Repositorio

```bash
Proyecto-Machine-Learning/
├── Notebooks/                             # Proceso completo en Jupyter Notebooks
│   ├── _1_Limpieza.ipynb
│   ├── _2_EDA_L.ipynb
│   ├── _3_Preparando_El_Modelo_De_Prediccion.ipynb
│   └── _4_Prediciendo_Datos.ipynb
├── Capas Georeferenciadas - qgis/        # Archivos espaciales QGIS (.qgz, .shp, etc.)
│   └── comuna_bucaramanga_poligonal.qgz  # Georreferenciación polinomial
├── tableu/                                # Visualizaciones Tableau
│   ├── Datos_historicos_Bucaramanga_2010_-_2021.twb
│   ├── Predicciones_delectiva_-_Bucaramanga_2023.twb
│   ├── dfml.csv_Varias_conexiones.hyper
│   └── df_futuro_cantidad_sin_redondear.csv_Varias_conexiones.hyper
├── bandera_bucaramanga.png               # Imagen representativa
├── Bandera-de-Colombia-1024x730.png      # Bandera nacional
└── README.md
```

---

## 📘 Descripción de los Notebooks

### 🔹 `1. Limpieza de Datos`
> Archivo: `_1_Limpieza.ipynb`

- Preparación inicial de los datos.
- Filtrado geográfico para asegurar que los registros pertenezcan a la zona urbana de Bucaramanga.

### 🔹 `2. Análisis Exploratorio`
> Archivo: `_2_EDA_L.ipynb`

- Cruces de campos clave.
- Generación de datasets derivados para pruebas.
- Visualización de matrices de correlación, estadísticas y mapas referenciados.

### 🔹 `3. Preparación del Modelo`
> Archivo: `_3_Preparando_El_Modelo_De_Prediccion.ipynb`

- Evaluación de múltiples algoritmos de ML.
- Optimización de hiperparámetros.
- Exportación del modelo final para su uso posterior.

### 🔹 `4. Predicción Final`
> Archivo: `_4_Prediciendo_Datos.ipynb`

- Implementación del modelo entrenado sobre nuevos datos.
- Generación y exportación de resultados con etiquetas predictivas.

---

## 🗺️ Capas Geoespaciales (QGIS)

> Carpeta: `Capas Georeferenciadas - qgis/`

Contiene el archivo de proyecto `comuna_bucaramanga_poligonal.qgz`, una capa georreferenciada que permite visualizar y superponer los resultados del modelo sobre las comunas de Bucaramanga.

- **Sistema de referencia:** Georreferenciación polinomial.
- **Propósito:** Relacionar las predicciones con zonas geográficas para análisis espacial.

---

## 📈 Dashboards Interactivos (Tableau)

> Carpeta: `tableu/`

Se incluyen dashboards de alto nivel generados en Tableau para una mejor interpretación de los datos y resultados.

### 📊 Datos Históricos de Bucaramanga (2010–2021)
- Análisis temporal de variables urbanas.
- Visualizaciones multianuales integradas.
- Dataset: `dfml.csv_Varias_conexiones.hyper`

---

### 📈 Predicciones Electivas – Bucaramanga 2023
- Visualización de predicciones generadas por el modelo.
- Exploración por comuna.
- Dataset: `df_futuro_cantidad_sin_redondear.csv_Varias_conexiones.hyper`

---

## 🏳️ Identidad Territorial

Representación simbólica de la ciudad y el país:

<div style="display: flex; gap: 20px;">
  <img src="bandera_bucaramanga.png" alt="Bucaramanga" width="200"/>
  <img src="Bandera-de-Colombia-1024x730.png" alt="Colombia" width="200"/>
</div>

---

## ⚙️ Requisitos e Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/ChampoI/Proyecto-Machine-Learning-.git
cd Proyecto-Machine-Learning-
```

2. (Opcional) Crea un entorno virtual:
```bash
python -m venv env
source env/bin/activate  # En Windows: .\env\Scripts\activate
```

3. Instala dependencias (si hay `requirements.txt`):
```bash
pip install -r requirements.txt
```
---

## 👤 Autor

**ChampoI**  
GitHub: [@ChampoI](https://github.com/ChampoI)
