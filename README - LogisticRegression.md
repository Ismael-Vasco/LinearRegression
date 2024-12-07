# Proyecto de Regresión Logística: Predicción del Acceso a la Electricidad

Este proyecto utiliza **regresión logística** para predecir el acceso a la electricidad en diferentes países a partir de un conjunto de datos globales sobre energía sostenible. El objetivo es clasificar si el acceso a la electricidad en un país supera el 50% de la población, basándose en variables relacionadas con la energía renovable y el acceso a combustibles limpios.

## Librerías utilizadas

Este proyecto hace uso de varias bibliotecas populares de Python para manipulación de datos y construcción de modelos de machine learning:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
# Métricas de evaluación
from sklearn.metrics import accuracy_score, confusion_matrix, roc_curve, roc_auc_score
´´´

## importación de datos
data = pd.read_csv('https://raw.githubusercontent.com/AnshTanwar/Global-Data-on-Sustainable-Energy/refs/heads/main/global-data-on-sustainable-energy%20(1).csv')
