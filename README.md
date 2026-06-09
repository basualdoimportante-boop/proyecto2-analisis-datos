# Proyecto 2 — Análisis Inicial y Selección de Problema

## Descripción
Análisis exploratorio de datos (EDA) de cuatro conjuntos de datos diversos,
con diagnóstico de problemáticas y selección del dataset principal para modelado.
Bootcamp Data Science — Abril 2026.

## Conjuntos de Datos Analizados

| # | Dataset | Fuente | Problemática | Tipo |
|---|---------|--------|--------------|------|
| 1 | House Prices | Kaggle | Predecir precio de venta de propiedades | Regresión |
| 2 | Student Stress Factors | Kaggle | Predecir nivel de estrés (Bajo/Medio/Alto) | Clasificación |
| 3 | Crop Yield (Agricultura) | Kaggle | Predecir rendimiento de cultivo en ton/ha | Regresión |
| 4 | UFC Fights | Kaggle | Predecir ganador de pelea (Victoria/Derrota) | Clasificación Binaria |

## Estructura del Repositorio
/proyecto2-analisis-datos
|-- EDA_dataset1_propiedades.ipynb
|-- EDA_dataset2_meditacion.ipynb
|-- EDA_dataset3_agricultura.ipynb
|-- EDA_dataset4_ufc.ipynb
|-- README.md

## Resumen de Hallazgos EDA

**Dataset 1 — House Prices:**
EDA completo de precios de propiedades. Variable target: SalePrice.
Sin nulos críticos. Alta correlación entre tamaño del inmueble y precio.

**Dataset 2 — Student Stress Factors:**
Clasificación de nivel de estrés estudiantil. Dataset balanceado.
Factores académicos y de sueño son los más correlacionados con el estrés.

**Dataset 3 — Agricultura (Crop Yield):**
Predicción de rendimiento agrícola en ton/ha. Dataset limpio (11 duplicados eliminados).
Nitrógeno del suelo (0.88) y temperatura (-0.87) son los factores más determinantes.

**Dataset 4 — UFC Fights:**
8.461 peleas con 47 variables por combate. El control de suelo es el predictor
más fuerte de victoria. Las peleas se ganan principalmente por decisión (45.2%),
KO/TKO (33%) y sumisión (21.5%).

## Problema Seleccionado

**Dataset: UFC Fights**
**Tipo: Clasificación Binaria**

Predecir si el Peleador 1 gana o pierde una pelea usando sus estadísticas
de combate (golpes, derribos, control de suelo, knockdowns, sumisiones).

**Justificación:**
- Dataset rico con 8.311 registros útiles y 47 variables
- Target balanceado (Victoria: 64% / Derrota: 36%)
- Variables con poder predictivo claro identificado en el EDA
- Problema relevante para análisis deportivo y predicción de resultados

## Instrucciones para Ejecutar
1. Clonar el repositorio:

2. git clone https://github.com/basualdoimportante-boop/proyecto2-analisis-datos.git
2. Abrir cada notebook en Google Colab
3. Ejecutar las celdas en orden

## Autor
Martín Basualdo — Bootcamp Data Science Sonda Abril 2026
Asistente de codigo: Cloude de antropic 
## Licencia
MIT

1. Clonar el repositorio:
