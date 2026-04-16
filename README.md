# Maritime Anomaly Detection TFG Natalia Santamaría

Proyecto de Trabajo de Fin de Grado centrado en la detección de anomalías marítimas a partir de datos AIS.

## Objetivo

Desarrollar un pipeline de análisis capaz de identificar comportamientos anómalos en trayectorias marítimas mediante:
- preprocesamiento de datos AIS
- reconstrucción de trayectorias
- ingeniería de características
- modelos de detección de anomalías
- validación híbrida con reglas expertas
- análisis e interpretación de resultados
- ordenar anomalías por prioridad/riesgo

## Estructura del repositorio

- `notebooks/`: notebooks principales del desarrollo experimental
- `data/`: documentación y referencias sobre los datos
- `results/`: resultados exportados del pipeline
- `figures/`: imágenes y gráficas del proyecto

## Estado actual

Proyecto desarrollado inicialmente en Google Colab y actualmente en proceso de reorganización hacia una estructura más modular y reproducible.

## Próximos pasos

- modularizar parte de la lógica de los notebooks en scripts reutilizables
- desarrollar un simulador o demo del pipeline
- incorporar una capa de priorización o ranking de riesgo
- mejorar la reproducibilidad del proyecto fuera de Google Colab