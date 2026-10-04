# Análisis y segmentación del comportamiento de compra de clientes

## Descripción

Proyecto académico de minería de datos enfocado en el análisis del comportamiento de compra de clientes mediante técnicas de análisis exploratorio, segmentación y clasificación.

El proyecto utiliza Python y técnicas de aprendizaje automático para identificar patrones y grupos de clientes a partir de sus características y comportamiento de compra.

---

## Objetivo

Analizar el comportamiento de los clientes mediante técnicas de minería de datos para:

- Explorar y visualizar los datos.
- Identificar grupos de clientes mediante K-Means.
- Aplicar regresión logística para clasificación.
- Analizar e interpretar los resultados obtenidos.

---

## Dataset

Se utilizó el **Customer Shopping Trends Dataset**, publicado por **Sourav Banerjee** en Kaggle.

[Customer Shopping Trends Dataset – Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)

El dataset contiene **3,900 registros y 19 variables** relacionadas con características de clientes y comportamiento de compra.

El archivo original `shopping_trends.csv` no se incluye en este repositorio. Para ejecutar el proyecto, debe descargarse desde Kaggle y colocarse en:

```text
data/shopping_trends.csv

---

## Metodología

El proyecto se desarrolló mediante las siguientes etapas:

### Preparación de datos

- Limpieza y revisión del dataset.
- Generación de un archivo procesado.

### Análisis exploratorio

- Estadísticas descriptivas.
- Visualización de variables y patrones.

### Segmentación

- Aplicación de K-Means.
- Selección de 4 clusters mediante el método del codo.

### Clasificación

- Aplicación de regresión logística.
- Evaluación de los resultados obtenidos.

---

## Resultados principales

- 3,900 registros analizados.
- 4 clusters identificados mediante K-Means.
- Regresión logística con una exactitud aproximada de **84.19 %** sobre el conjunto de prueba.
- Generación de datasets procesados para continuar con el análisis.

Los resultados completos, gráficas y procedimientos se encuentran en el notebook y en la documentación del proyecto.

---

## Tecnologías

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Visual Studio Code

Las dependencias se encuentran en `requirements.txt`.

Para instalarlas:

```bash
pip install -r requirements.txt

---

## Estructura del proyecto

```text
Proyecto-Mineria-Datos/
│
├── data/
│   ├── shopping_trends_limpio.csv
│   └── shopping_trends_con_clusters.csv
│
├── documentacion/
│   └── Documento_ProyectoFinal_Mineria.pdf
│
├── notebook/
│   └── Proyecto_Final.ipynb
│
├── presentacion/
│   └── Presentacion_Proyecto_Final_Mineria_Datos.pptx
│
├── requirements.txt
└── README.md

`shopping_trends.csv` es el dataset original y se mantiene fuera del repositorio.

---

## Mi participación

Participé como **líder del proyecto**, encargándome de la coordinación, el planteamiento del problema y la revisión general del trabajo.

También participé directamente en distintas etapas del desarrollo, incluyendo:

- Procesamiento de datos.
- Análisis exploratorio.
- Elaboración de visualizaciones.
- Implementación de K-Means.
- Aplicación del método del codo.
- Implementación de regresión logística.
- Interpretación de resultados.
- Documentación del proyecto.
- Preparación de la presentación final.

---

## Documentación

Para consultar el desarrollo completo del proyecto:

- **Documento:** `documentacion/Documento_ProyectoFinal_Mineria.pdf`
- **Presentación:** `presentacion/Presentacion_Proyecto_Final_Mineria_Datos.pptx`
- **Código:** `notebook/Proyecto_Final.ipynb`

---

## Limitaciones

El análisis está limitado a las variables disponibles en el dataset utilizado. Los resultados de los modelos deben interpretarse dentro del contexto de este conjunto de datos.

---

## Conclusión

El proyecto permitió aplicar técnicas de minería de datos para explorar el comportamiento de compra, segmentar clientes mediante K-Means y realizar una tarea de clasificación mediante regresión logística.

La combinación del análisis exploratorio y los modelos utilizados permitió obtener diferentes perspectivas sobre los datos y sus patrones de comportamiento.