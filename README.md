# DHDSFW
Digital House - Data Science - Final Work

<div style="background-color: lightblue; padding: 30px;">
    
# Digital House - Data Science a Distancia

## Proyecto Final Integrador

### Autores: Daniel Borrino, Ivan Mongi, Jessica Polakoff, Julio Tentor
    
<p style="text-align:right;">Agosto 2022</p>

---
</div>

---
## Objetivo del Trabajo Final Integrador

<h4 style="text-align:center;">Demostrar que aprendimos conceptos y desarrollamos habilidades para obtener un modelo de aprendizaje automático que razonablemente predice un valor</h4>

### Escenario

Trabajamos como científicos de datos para una compañía; para consolidar nuestra posición presentamos el prototipo de un producto / servicio que permita transformar organizaciones al modelo Data-Driven Organization

### Requisitos del Trabajo Final Integrador

- Utilizar modelos de **regresión** o **clasificación** (es opcional) 👍
- Evaluar modelos mediante ensemble, bagging o **boosting** 👍
- Realizar **selección de hiperparámetros** 👍
- **Implementar pipeline** al menos con algunos pasos del preprocesamiento 👍
- Analizar **importancia de características** 👍
- **Serializar el modelo** con mejor desempeño 👍

### Entregables del Trabajo Final Integrador
#### Técnico (Jupyter Notebook)

1. Introducción y planteo del problema
2. Técnicas a utilizar y detalle del conjunto de datos
3. Desarrollo del análisis, visualizaciones, resultados de modelos
4. Detalle de hallazgos, conclusiones y recomendaciones

#### Presentación (audiencia NO TÉCNICA)

1. Resumen del problema
2. Métodos utilizados
3. Principales resultados

### Aspectos técnicos

La notebook se ejecuta correctamente en una instalación estándar de Anaconda versión *4.13.0 build  3.21.6, Python 3.9.7*

Deben asegurarse de tener la última versión de scikit-learn, pueden actualizar a la última versión accediendo a la consola de Anaconda y ejecutando:

    conda upgrade -c conda-forge scikit-learn
    
o accediendo a una terminal del sistema operativo y ejectutar (en esta opción recuerden habiliar el entorno en el que ejecutarán la notebook):

    python -m pip install scikit-learn --upgrade

Es necesario tener instalado el módulo **SHAP**

    conda install -c conda-forge/label/cf202003 shap

También hace falta XGBoost (en el enlace está la información para su instalación):

- [XGBoost](https://xgboost.readthedocs.io/en/stable/install.html)

---