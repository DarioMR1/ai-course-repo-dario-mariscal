# Inteligencia Artificial Avanzada para la Ciencia de Datos I

## Información del Estudiante

- **Nombre**: Darío Mariscal Rocha
- **Grupo**: 500
- **Curso**: Inteligencia Artificial Avanzada para la Ciencia de Datos II

## Descripción

Este repositorio contiene los notebooks implementados durante el curso de Inteligencia Artificial Avanzada para la Ciencia de Datos I. Aquí se desarrollarán y documentarán los proyectos, ejercicios y análisis de datos realizados durante el semestre.

## Contenido

### Notebooks de Análisis
- `airbnb.ipynb` - Análisis de datos de Airbnb
- `Introduction_Time_Series_30_oct.ipynb` - Introducción al análisis de series temporales
- `Multiple_Imputation_MICE_9_oct.ipynb` - Análisis de imputación múltiple MICE para datos faltantes
- `Multivariate_Analysis_2_oct.ipynb` - Análisis multivariado
- `Nonlinear_Regression_22_sep.ipynb` - Regresión no lineal
- `Regression_Assumptions_28_sep.ipynb` - Análisis de supuestos de regresión
- `Time_Series_Deep_Learning_30_oct.ipynb` - Deep Learning para series temporales con CNN y LSTM
- `Variable_Selection_25_sep.ipynb` - Selección de variables

### Datasets
- `listings.csv` - Dataset de Airbnb
- `housing.csv` - Dataset de viviendas

### Configuración
- `requirements.txt` - Dependencias del proyecto
- `.gitignore` - Archivos ignorados por Git

## Estructura del Proyecto

```
ai-course-repo-dario-mariscal/
├── README.md
├── .gitignore
├── requirements.txt
├── airbnb.ipynb
├── Introduction_Time_Series_30_oct.ipynb
├── Multiple_Imputation_MICE_9_oct.ipynb
├── Multivariate_Analysis_2_oct.ipynb
├── Nonlinear_Regression_22_sep.ipynb
├── Regression_Assumptions_28_sep.ipynb
├── Time_Series_Deep_Learning_30_oct.ipynb
├── Variable_Selection_25_sep.ipynb
├── listings.csv
├── housing.csv
└── venv/          # Entorno virtual (ignorado por Git)
```

## Instalación y Configuración

1. Clonar el repositorio
2. Crear un entorno virtual: `python -m venv venv`
3. Activar el entorno virtual:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Instalar dependencias: `pip install -r requirements.txt`

## Dependencias

El proyecto incluye las siguientes librerías principales:
- **Análisis de datos**: polars, pandas, numpy
- **Visualización**: matplotlib, seaborn, plotly, bokeh  
- **Machine Learning**: scikit-learn, statsmodels
- **Deep Learning**: tensorflow, keras
- **Jupyter**: jupyter, jupyterlab, ipykernel
- **Utilitarios**: openpyxl, xlrd, numba

## Uso

Los notebooks pueden ser ejecutados en Jupyter Notebook o JupyterLab. Asegúrate de tener el entorno virtual activado antes de ejecutar los notebooks.

## Autor

**Darío Mariscal Rocha** - Estudiante de Inteligencia Artificial Avanzada para la Ciencia de Datos I
