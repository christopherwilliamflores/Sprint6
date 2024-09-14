# Sprint6
# Web App de Análisis de Datos de Vehículos

## Descripción del Proyecto

Esta aplicación web permite realizar un análisis exploratorio interactivo de un conjunto de datos de anuncios de venta de vehículos. El objetivo principal de la aplicación es proporcionar a los usuarios una herramienta sencilla para visualizar y explorar datos relevantes sobre los vehículos en venta, como el kilometraje (odometer), precio, año de fabricación, entre otros.

La aplicación está diseñada con **Streamlit**, lo que permite a los usuarios interactuar con los datos a través de gráficos y visualizaciones sin necesidad de conocimientos avanzados en programación o análisis de datos. Los usuarios pueden generar gráficos como histogramas y gráficos de dispersión con solo presionar un botón o seleccionar opciones desde la interfaz web.

## Funcionalidades

La aplicación proporciona las siguientes funcionalidades:

1. **Visualización de histogramas**: Los usuarios pueden generar histogramas que representan la distribución de los datos, como el kilometraje de los vehículos en venta, lo que les permite observar patrones y tendencias dentro del conjunto de datos.
   
2. **Gráfico de dispersión**: También se puede generar un gráfico de dispersión que muestra la relación entre dos variables, como el precio y el kilometraje, lo que permite al usuario observar la correlación entre ellas.

3. **Interfaz interactiva**: La aplicación cuenta con botones y casillas de verificación que permiten a los usuarios seleccionar qué visualización desean ver, proporcionando una experiencia interactiva.

## Datos Utilizados

El conjunto de datos utilizado proviene de un archivo CSV llamado `vehicles_us.csv`, que contiene información detallada sobre vehículos en venta en los Estados Unidos. Algunas de las variables incluidas son:

- **Precio**: Precio del vehículo.
- **Kilometraje (odometer)**: Distancia recorrida por el vehículo.
- **Año de fabricación**: Año en que fue fabricado el vehículo.
- **Tipo de vehículo**: Categoría del vehículo (SUV, Sedan, etc.).

## Requisitos

Para ejecutar la aplicación localmente, se deben instalar las siguientes dependencias:

```bash
pandas
streamlit
plotly-express
