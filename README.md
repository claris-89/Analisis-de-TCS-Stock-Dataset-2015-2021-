# Analisis-de-TCS-Stock-Dataset-2015-2021-

# Mini Proyecto de Análisis de TCS Stock Dataset (2015-2021)

## Descripción del Proyecto

Este mini proyecto consiste en un análisis exploratorio del dataset de las acciones de Tata Consultancy Services (TCS) para el periodo de 2015 a 2021. El objetivo principal es entender el comportamiento de las acciones de TCS, identificar tendencias clave en los precios y analizar el volumen de operaciones.

## Objetivo

El proyecto tiene como objetivo realizar un análisis detallado del comportamiento de las acciones de TCS, identificando tendencias en los precios de apertura, cierre y ajustados, así como en el volumen de operaciones. Este análisis proporcionará una visión integral del rendimiento de las acciones de TCS y permitirá comprender mejor los factores que han influido en su variación a lo largo del tiempo.

## Pasos del Proyecto

1. **Preparación y Exploración de los Datos**
   - Cargar el dataset en un dataframe utilizando Pandas.
   - Explorar el dataset para identificar valores faltantes o duplicados.
   - Analizar la estructura de las columnas utilizando el método `info()`.
   - Calcular estadísticas básicas como la media, mediana, máximos y mínimos con el método `describe()`.

2. **Análisis de la Evolución de los Precios**
   - Crear un gráfico de líneas que muestre la evolución de los precios de apertura (Open), cierre (Close) y ajustado (Adj Close) a lo largo del tiempo.
   - Calcular la diferencia diaria entre los precios altos (High) y bajos (Low) y visualizar la distribución de estas variaciones con un histograma.

3. **Análisis de Volumen de Operaciones**
   - Graficar la tendencia del volumen de operaciones (Volume) a lo largo del tiempo.
   - Identificar los días con los mayores volúmenes de operaciones y analizar posibles eventos que pudieron influir en estos volúmenes, correlacionando con los gráficos de precios si es posible.

4. **Relación entre Volumen y Precio**
   - Graficar un diagrama de dispersión entre el volumen de operaciones (Volume) y los precios de cierre ajustados (Adj Close).
   - Analizar si existe alguna correlación entre estas dos variables y calcular la correlación numérica entre Volume y Adj Close.

5. **Identificación de Tendencias**
   - Calcular medias móviles (por ejemplo, de 30 días) para los precios de cierre ajustados (Adj Close).
   - Graficar las medias móviles junto con los precios de cierre para observar tendencias a corto y largo plazo.

6. **Análisis de Anomalías**
   - Identificar los días en los que hubo una variación excepcionalmente alta en el precio (por ejemplo, días con cambios superiores al 5% en el precio de cierre ajustado).

## Resultados Clave

- **Evolución de los Precios**: Los precios de apertura, cierre y ajustados mostraron fluctuaciones significativas, con incrementos notables alrededor de 2019 y 2021.
- **Distribución de las Variaciones Diarias**: La mayoría de las diferencias diarias entre los precios altos y bajos se encuentran en un rango pequeño, con una distribución sesgada a la derecha.
- **Volumen de Operaciones**: Los picos en el volumen de operaciones podrían correlacionarse con eventos importantes de la empresa y factores macroeconómicos.
- **Relación entre Volumen y Precio**: Existe una correlación positiva débil (0.1125) entre el volumen de operaciones y los precios de cierre ajustados.
- **Tendencias a Corto y Largo Plazo**: Las medias móviles de 30 días ayudan a identificar tendencias subyacentes en los precios de cierre ajustados.

## Conclusión

Este análisis exploratorio ha permitido identificar y comprender mejor las tendencias y comportamientos de las acciones de TCS durante el periodo de 2015 a 2021. Los hallazgos obtenidos son útiles para la toma de decisiones financieras y proporcionan una base sólida para futuros análisis más profundos del mercado de valores.
