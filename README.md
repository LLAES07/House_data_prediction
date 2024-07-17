# Predicción de Precios de Casas

Este repositorio proporciona modelos de regresión lineal y árboles de regresión entrenados para predecir los precios de las casas basados en características del dataset house_data.xlsx. Además, incluye un análisis descriptivo de los datos y evaluación del rendimiento de los modelos.

## Tabla de Contenidos

1. [Objetivo](#objetivo)
2. [Datos](#datos)
3. [Características](#características)
4. [Modelos](#modelos)
5. [Beneficios](#beneficios)
6. [Inicio Rápido (Jupyter Notebook)](#inicio-rápido-jupyter-notebook)
7. [Contribuciones](#contribuciones)

## Objetivo

Este repositorio tiene como objetivo:

- Implementar y comparar modelos de regresión lineal regularizados y árboles de regresión para predecir los precios de las casas.
- Proporcionar un análisis exploratorio detallado, limpieza de datos, preprocesamiento, selección de modelos y evaluación utilizando un Jupyter Notebook.

## Datos

El dataset `house_data.xlsx` contiene características detalladas de casas vendidas recientemente, junto con sus precios.


## Características

Las características principales incluyen:

El dataset proporciona información detallada sobre propiedades vendidas, incluyendo las siguientes características principales:

- **id**: Identificación única de la propiedad
- **date**: Fecha de venta de la propiedad
- **price**: Precio de venta de la propiedad
- **bedrooms**: Número de dormitorios
- **bathrooms**: Número de baños completos
- **sqft_living**: Pies cuadrados habitables 
- **sqft_lot**: Pies cuadrados de lote 
- **floors**: Número de pisos en la propiedad
- **waterfront**: Frente al agua (0 = No, 1 = Sí)
- **view**: Vistas
- **condition**: Condición (1 = Pobre, 5 = Excelente)
- **grade**: Grado  (1-13)
- **sqft_above**: Pies cuadrados sobre el nivel del suelo 
- **sqft_basement**: Pies cuadrados del sótano
- **yr_built**: Año de construcción
- **yr_renovated**: Año de renovación 
- **zipcode**: Código postal
- **lat**: Latitud 
- **long**: Longitud 
- **sqft_living15**: Pies cuadrados habitables 15
- **sqft_lot15**: Pies cuadrados de lote 15 

## Modelos

Este repositorio se centra en:

- Implementación de modelos de regresión lineal con regularización (Ridge, Lasso, Elastic Net).
- Construcción de modelos de árboles de regresión para capturar relaciones complejas.

## Beneficios

La predicción de precios de casas ofrece varios beneficios:

- Ayuda en la evaluación precisa del mercado inmobiliario.
- Facilita la toma de decisiones informadas para compradores y vendedores.
- Proporciona una herramienta para estimar el valor de las propiedades basada en características específicas.

## Inicio Rápido (Jupyter Notebook)

Para comenzar con este proyecto:

1. Clona este repositorio:

```
git clone https://github.com/LLAES07/house_data_prediction.git
```

2. Instala las dependencias requeridas:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Contribuciones

¡Se aceptan contribuciones a este repositorio! Si tienes ideas para mejorar, corregir errores, o explorar diferentes aspectos del modelo, no dudes en crear un pull request.


