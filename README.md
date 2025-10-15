# Reto 3: Consumo de Agua y Presión Hídrica en el Área Metropolitana de Barcelona

## Tópico: Medio ambiente y sostenibilidad

## Agenda 2030: ODS 6 – Agua limpia y saneamiento | ODS 13 – Acción por el clima

## Descripción:

El agua es un recurso natural fundamental para el bienestar de la población, el funcionamiento de la economía y la sostenibilidad ambiental. Sin embargo, en las ciudades, el consumo de agua se ha mantenido elevado o incluso en aumento, a pesar de una mayor concienciación ciudadana y de las campañas de ahorro.

En un contexto de cambio climático, con períodos de sequía más prolongados, temperaturas más altas y precipitaciones más irregulares, esta situación genera una presión cada vez más intensa sobre el sistema hídrico.

El Área Metropolitana de Barcelona es un claro ejemplo de esta tensión: alta densidad de población, intensa actividad económica y un uso extensivo del recurso hídrico en todos los sectores.

Los patrones de consumo varían mucho según el momento del día, la estación del año, el tipo de uso (doméstico, comercial o industrial) y el contexto climático. Esto dificulta identificar con claridad dónde y cuándo se producen usos excesivos o ineficientes que podrían corregirse mediante medidas específicas.

## Objetivo y entrega de datos:

¿Cómo se distribuye el consumo de agua en el Área Metropolitana de Barcelona en función del tipo de uso, la estación del año, el momento del día y las condiciones ambientales?

A partir de los datos disponibles, identifica zonas y períodos con consumos elevados o ineficientes, construye indicadores clave para su seguimiento, y propone recomendaciones para una mejor gestión del recurso hídrico.

## Bases de datos sugeridas:

1. Datos de consumo de agua en la ciudad de Barcelona proporcionados por Aigües de Barcelona (es necesario registrarse para obtener los datos).

2. Este enlace dirige al Catálogo de Datos Abiertos de la Agencia Catalana del Agua (ACA), donde se pueden consultar y descargar diversos conjuntos de datos relacionados con la gestión del agua en Cataluña.

3. Datos climatológicos de AEMET (Agencia Estatal de Meteorología).

------------------------------

## Bases de datos usadas:

Hemos descargado el dataset de la opción 1. Sólo traía los datos del municipio de Barcelona y no de todo el Área metropolitana, y solo para 2023. (opción "SET DE DADES 1 - CONSUM TOTAL AGREGAT")

Lo hemos cargado desde el fichero .parquet en python a un dataframe de pandas y lo hemos exportado a un csv para poderlo analizar en Power BI.

## Campos del dataset:

Secció censal/Sección censal/Census section

Districte/Distrito/District

Municipi/Municipio/Municipality

Data/Fecha/Date

Ús/Uso/Use

Nombre de comptadors/Número de contadores/Number of meters

Consum acumulat (L/dia)/Consumo acumulado (L/día)/Accumulated consumption (L/day)

## Herramientas usadas para análisis:

Power BI

## Conclusiones datos analizados:

Observamos una caída muy importante del consumo doméstico hacia abril de 2023. Justo coincide con la sequía y con la activación de excepcionalidad de marzo 2023:

https://www.totbarcelona.cat/es/sociedad/los-hogares-de-barcelona-reducen-el-consumo-agua-en-plena-sequia-438255/#:~:text=Cuando%20el%20marzo%20del%202023,litro%20menos%20que%20en%20marzo

01/11/2023 10:20
"Cuando el marzo del 2023 se activó la fase de excepcionalidad, que actualmente todavía está en vigor, los hogares de Barcelona tenían un consumo acumulado de 103 litros por persona y día. Este consumo solo contabiliza el consumo doméstico de agua sin tener en cuenta el agua que usan la industria, los comercios y los servicios municipales. Si se suman estos otros usos, según los mismos datos del consistorio, a septiembre del 2023 lo consumo de agua total en Barcelona es de 173 litros por persona y día, un litro menos que en marzo."


