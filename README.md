# **Detección de Anomalías con Deequ**

Trabajo en conjunto con:
- Fabian Salazar Figueroa (https://github.com/alfa7g7)
- Raul Echeverry (https://github.com/RaulEcheverryLopez)
- Esteban Ordoñez (https://github.com/leoe21)

En el presente trabajo se aborda un análisis y detección de anomalías en un conjunto de datos utilizando la biblioteca Deequ, desarrollada por Amazon. Deequ es una herramienta poderosa para evaluar la calidad de los datos mediante la creación de métricas estadísticas y el uso de técnicas automatizadas para identificar irregularidades. Este análisis sigue una metodología estructurada que incluye las siguientes etapas:

1. **Selección del Dataset**:
Se ha seleccionado un conjunto de datos que contiene diferentes tipos de información (numérica, categórica, y posiblemente temporal), con el fin de maximizar la riqueza y diversidad del análisis. Una parte de este dataset será destinada a representar datos "nuevos", mientras que otra parte servirá como referencia histórica. Esto permitirá aplicar técnicas de detección de anomalías, evaluando la consistencia entre datos actuales y pasados.

2. **Aplicación de Deequ Profiling**:
En esta etapa, se utilizará Deequ para realizar un perfilado inicial del dataset. Este proceso permitirá obtener una visión global de la distribución de los datos, su integridad, la existencia de valores atípicos, y otras métricas relevantes. Estas métricas iniciales proporcionan la base para establecer criterios de calidad.

3. **Uso de Deequ Analyzer**:
Posteriormente, se aplicarán los análisis del módulo Analyzer de Deequ, que permite extraer métricas específicas del dataset. Estas métricas incluyen estadísticas descriptivas avanzadas, correlaciones y otras propiedades de los datos. Los resultados serán fundamentales para establecer reglas de calidad.

4. **Detección de Anomalías con Deequ**:
Finalmente, mediante el módulo de detección de anomalías de Deequ, se identificarán patrones inesperados en los datos nuevos en comparación con los históricos. Esta etapa tiene como objetivo detectar desviaciones significativas que podrían señalar problemas de calidad, errores en los datos o tendencias fuera de lo común.
