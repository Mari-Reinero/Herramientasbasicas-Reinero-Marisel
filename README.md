# Análisis de Producción y Eficiencia - Planta de Hielo

## Objetivo del proyecto

Analizar los registros históricos de producción de una planta de hielo con el objetivo de evaluar los niveles de producción, las horas de funcionamiento de los equipos y su eficiencia.

El análisis busca transformar los registros operativos de la planta en información útil para facilitar la interpretación y la toma de decisiones.

## Dataset

El proyecto parte de un archivo Excel con registros históricos de producción de hielo.

Los datos incluyen información relacionada con:

- Fecha de producción
- Compresor utilizado
- Roliteras
- Tipo de producto
- Cantidad producida
- Horarios de encendido y apagado
- Horas de funcionamiento

Para realizar correctamente el análisis fue necesario comprender el funcionamiento operativo de la planta y la relación existente entre los compresores y las roliteras.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Power BI
- GitHub

## Proceso realizado

1. Importación y exploración inicial del dataset.
2. Revisión de la estructura, tipos de datos y calidad de los registros.
3. Análisis de las particularidades operativas de la planta considerando la relación entre compresores y roliteras.
4. Identificación de registros inconsistentes en las horas de funcionamiento.
5. Corrección de horas de funcionamiento utilizando criterios definidos a partir del análisis de los datos y del funcionamiento de los equipos.
6. Análisis de producción y eficiencia.
7. Generación de un dataset limpio para visualización en Power BI.
8. Desarrollo de un dashboard interactivo en Power BI.

## Dashboard

Se desarrolló un dashboard en Power BI para visualizar los principales indicadores de producción y eficiencia.

Incluye:

- Producción total en kilogramos
- Horas totales de producción
- Eficiencia global en kg/hora
- Producción por compresor
- Evolución mensual de la producción
- Producción por tipo de producto
- Filtros por año, mes, compresor y descripción

## Archivos del repositorio

- `informe producción hielo.xlsx`: dataset original.
- `Proyecto Final.ipynb`: notebook con el proceso de limpieza y análisis.
- `produccion_hielo_limpio_ARG.csv`: dataset limpio utilizado para la visualización.
- `Dashboard Producción.pbix`: dashboard desarrollado en Power BI.

## Autor

**Marisel Reinero**

Proyecto Final - Análisis de Datos
