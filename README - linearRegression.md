# Proyecto de Regresión Lineal - Predicción de Acceso a Electricidad

Este proyecto tiene como objetivo predecir el **acceso a la electricidad** (% de la población) en diferentes países utilizando un modelo de **regresión lineal**. Se utilizan diversas variables relacionadas con la energía sostenible, como el acceso a combustibles limpios para cocinar, la participación de las energías renovables en el consumo final de energía y la electricidad de bajo carbono.

## Librerías utilizadas

El proyecto utiliza las siguientes librerías de Python:

- `pandas` - Para la manipulación de datos.
- `numpy` - Para operaciones matemáticas y matrices.
- `matplotlib` - Para la visualización de datos.
- `seaborn` - Para gráficos estadísticos.
- `sklearn` - Para la construcción y evaluación del modelo de regresión.

## Importación de los datos

Los datos utilizados en este proyecto provienen de un archivo CSV almacenado en GitHub, el cual se puede cargar mediante el siguiente código:

```python
import pandas as pd
data = pd.read_csv('https://raw.githubusercontent.com/AnshTanwar/Global-Data-on-Sustainable-Energy/refs/heads/main/global-data-on-sustainable-energy%20(1).csv')


## Conclusiones
El modelo de regresión lineal ha mostrado una buena capacidad para predecir el acceso a la electricidad basado en las características seleccionadas. Sin embargo, es posible que otras variables o técnicas de modelado puedan mejorar aún más los resultados.
