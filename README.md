# Proyecto Final Modelos II- Entrenamiento de modelos de Machine Learning para la clasificación de la intención de compra en comercio electrónico
Modelo de clasificación binaria para predecir la intención de compra basado en el comportamiento de navegación de los compradores en línea. Machine Learning — UdeA 2026-02

# Integrantes Grupo 12:
-Jenny Andrea Orozco Osorio
-Max Daniel Perez Quintero
-Paolo Steven Martinez Cardona

# [Link video sustentación]

## Archivos importantes del repositorio

`reporte proyecto final modelos 2.pdf`: Este es el archivo pdf donde se encuentra el reporte acerca del proyecto.

`desarrollo-proyecto.ipynb`: Dentro de este notebook se encuentra todo el desarrollo que se realizó para el proyecto, está dividido en varias partes:

- Al principio se importa el dataset y se realizó una exploración y encoding para las variables.
- Luego se define la división de datos en train y test y se define la metodología de validación, con esto ya se entrena cada modelo usando un pipeline y una malla de hiperparámetros.
- Finalmente se realiza la operación de reducción de dimensión para encontrar el valor de cada variable y se aplica tanto PCA como UMAP al dataset y se comparán los resultados contra la versión  con todas las variables.

# Pasos para poder reproducir el notebook

El único requisito para poder ejecutar el notebook es obtener las dependencias descritas en el archivo `requirements.txt` si se usa el gestor de paquetes pip y `pyproject.toml` si se usa uv, a continuación se dejan las dos opciones para obtener las dependencias.

## Instalación de dependencias usando pip

```
pip install -r requirements.txt
```
## Instalación de dependencias usando uv

```
uv sync
```
