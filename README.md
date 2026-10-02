# Analisis y Clasificacion de Tipos de Clima

Proyecto de analisis exploratorio de datos (EDA), preprocesamiento y visualizacion de variables meteorologicas para clasificacion de tipos de clima.

## Descripcion del Dataset

El conjunto de datos contiene 13,200 registros y 11 caracteristicas meteorologicas que describen condiciones ambientales asociadas a cuatro tipos de clima (`Rainy`, `Sunny`, `Cloudy`, `Snowy`).

### Columnas y Variables

- `Temperature`: Temperatura ambiental medida en grados Celsius (°C).
- `Humidity`: Porcentaje de humedad relativa (%).
- `Wind Speed`: Velocidad del viento en kilometros por hora (km/h).
- `Precipitation (%)`: Porcentaje de probabilidad o nivel de precipitacion.
- `Cloud Cover`: Tipo de cobertura nubosa (`clear`, `partly cloudy`, `cloudy`, `overcast`).
- `Atmospheric Pressure`: Presion atmosferica medida en hectopascales (hPa).
- `UV Index`: Indice de radiacion ultravioleta.
- `Season`: Estacion del ano en la que se registro la medicion (`Winter`, `Spring`, `Summer`, `Autumn`).
- `Visibility (km)`: Visibilidad horizontal medida en kilometros.
- `Location`: Tipo de zona geografica (`inland`, `mountain`, `coastal`).
- `Weather Type`: Variable objetivo que clasifica el tipo de clima (`Rainy`, `Sunny`, `Cloudy`, `Snowy`).

## Estructura del Proyecto

- `Tipos de Clima-ALUMNO.ipynb`: Cuaderno Jupyter con el analisis completo, preprocesamiento y visualizaciones ejecutadas.
- `Weather_Classification.csv`: Dataset principal en formato CSV.
- `README.md`: Documentacion tecnica del proyecto y estructura del dataset.

## Contenido del Analisis

1. Importacion de librerias (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
2. Analisis Exploratorio de Datos (EDA): inspeccion de registros, tipos de datos, identificacion de nulos y mapa de calor.
3. Analisis de balanceo de clases de la variable objetivo (`Weather Type`).
4. Matrices de correlacion lineal y no parametrica (metodos Pearson, Kendall y Spearman).
5. Transformacion y conversion de unidades (Celsius a Fahrenheit).
6. Graficos de lineas individuales y comparativos en subplots para series de variables.
7. Diagramas de dispersion (Scatter Plots) con Matplotlib y Seaborn.
8. Histogramas con calculo de media y desviacion estandar.
9. Proyeccion tridimensional (3D Scatter Plot) con `mpl_toolkits.mplot3d`.
10. Estandarizacion (`StandardScaler`) y normalizacion (`MinMaxScaler`) de variables continuas.
11. Codificacion de variables categoricas mediante One-Hot Encoding (`pd.get_dummies`).
12. Grafico de burbujas (Bubble Chart) con dimensiones multivariables.
13. Diagrama de caja y bigotes (Box Plot) por tipo de clima y nubosidad.
14. Grafico de barras apiladas (Stacked Bar Chart) de temperatura media agrupada.

## Requisitos de Instalacion

Para ejecutar el cuaderno localmente se requiere Python 3.9 o superior y las siguientes dependencias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Ejecucion

Iniciar el entorno de Jupyter:

```bash
jupyter notebook "Tipos de Clima-ALUMNO.ipynb"
```
