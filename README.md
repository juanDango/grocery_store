# Clasificación de Productos de Supermercado con Redes Neuronales

Este proyecto implementa un modelo de red neuronal profunda para clasificar productos de supermercado utilizando características visuales y estadísticas. Se desarrolló un modelo eficiente con un enfoque en optimizar la precisión y el rendimiento para su uso en un entorno de supermercado inteligente.

## Integrantes

1. Juan Daniel Castrellón (201729285)
2. Javier Alejandro Gómez (201217975) 

## Descripción

El objetivo principal del proyecto es automatizar el registro de productos en un supermercado utilizando cámaras y sensores, reduciendo el tiempo necesario para registrar productos manualmente y minimizando errores. Se logró desarrollar un modelo robusto con un desempeño de 96.8% de precisión en validación, utilizando el dataset Grocery Store Dataset.  

El proyecto incluye:

- Un modelo basado en MobileNetV2 preentrenado para extracción de características visuales.
- Un modelo 2 con una rama de procesamiento de estadísticas (histogramas de color, características derivadas).
- Integración de ambas ramas en un modelo combinado para mejorar el rendimiento.

## Resultados Principales
- Precisión promedio (macro y micro): 0.97
- Pérdida final de test: 0.3
- Punto de equilibrio (ROI): 0.26 meses (~8 días).
- Ahorro mensual estimado: 1,728,000 COP.

## Estructura

```
├── neural_networks.ipynb          
├── data_understanding.ipynb
├── data.pickle     ## No se cargo al repo, pero resulta de la ejecucion del primer notebook!
├── README.md
├── Presentación.pdf  
├── taller_2.docx  
└── requirements.txt  
```

Los notebooks se pueden correr, primero `data_understanding.ipynb`, seguido de `neural_networks.ipynb`

## Referencias

- Grocery Store Dataset: https://github.com/marcusklasson/GroceryStoreDataset
- Salario mínimo en Colombia 2023: Decreto 2613 de 2022
- Costo por error manual estimado en 161 COP basado en estudios internos.
