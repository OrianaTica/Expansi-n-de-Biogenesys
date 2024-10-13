# Expansion de Biogenesys

## Introducción

Este proyecto analiza datos de muertes, recuperaciones y casos activos de COVID-19 en seis países, con un enfoque en el impacto de la vacunación. El objetivo principal es evaluar cómo la vacunación ha contribuido a reducir la mortalidad, identificando patrones y tendencias relevantes.
Además, se examina la relación entre las tasas de letalidad y las enfermedades preexistentes para determinar la vulnerabilidad de ciertos grupos. También se analiza la distribución de las dosis de vacunación por rangos etarios, evaluando la cobertura alcanzada.
Finalmente, se presenta un resumen de la situación actual en los países estudiados, destacando el control de la pandemia y los avances en la vacunación.

## Requisitos

- Visual  Studio Code
- Python: Para técnicas ETL y análisis
ipython==8.25.0

jupyter_client==8.6.2

jupyter_core==5.7.2

matplotlib==3.9.1

matplotlib-inline==0.1.7

numpy==2.0.0

pandas==2.2.2

pyodbc==5.1.0

seaborn==0.13.2

shapely==2.0.5

virtualenv==20.26.3

- Power BI: Para la presentación de los informes e insights obtenidos

## Desarrollo
El presente proyecto se centra en el análisis detallado de los datos relacionados con la pandemia de COVID-19 en seis países seleccionados. El estudio aborda múltiples aspectos clave de la pandemia, incluyendo las cifras de muertes, recuperaciones y casos activos, con un enfoque particular en el impacto de la vacunación en la reducción de la mortalidad.
Uno de los objetivos principales fue evaluar la efectividad de las campañas de vacunación y cómo estas han contribuido a la disminución de las tasas de mortalidad por COVID-19. Para ello, se analizó la correlación entre las tasas de vacunación y la reducción de las muertes, permitiendo identificar patrones y tendencias que demuestren el impacto positivo de la inmunización a gran escala.
Adicionalmente, se investigó la relación entre las tasas de letalidad y la prevalencia de enfermedades preexistentes en la población. Este análisis buscó determinar si existía una correlación significativa que pudiera indicar una mayor vulnerabilidad en ciertos grupos demográficos.
Otro aspecto crucial del proyecto fue el estudio de la distribución de las dosis de vacunación según los distintos rangos etarios de la población. Este análisis permitió observar cómo las estrategias de vacunación se adaptaron a las diferentes necesidades de edad, así como evaluar la cobertura alcanzada en los grupos de mayor riesgo.
Finalmente, se presenta un resumen de la situación actual en los seis países analizados, destacando el estado de control de la pandemia, el progreso en la vacunación y las estrategias implementadas para mantener la seguridad sanitaria a largo plazo. El análisis proporciona insights clave para entender cómo la respuesta global al COVID-19 ha evolucionado y cómo podría mejorar en el futuro.


## EDA e insights
- Casos Confirmados Acumulados por País:
Donde Brasil lidera con un gran margen, acumulando alrededor de 14 millones de casos confirmados, lo que representa la mayoría de los casos en la región.
El segundo país con mayor cantidad de casos es Argentina, sigue con 4 millones de casos, mientras que Colombia tiene 3 millones. Perú, México y Chile tienen entre 1 y 2 millones de casos cada uno.
- Promedio de Nuevos Fallecidos por Semana:
Brasil nuevamente muestra las cifras más altas, con picos que alcanzan más de 1500 fallecidos por semana en algunos periodos.
Argentina y Perú muestran tendencias similares, aunque con menores cantidades, mientras que Chile, Colombia y México tienen cifras más bajas.
Las tendencias generales indican una disminución en el promedio de nuevos fallecidos hacia las últimas semanas del año, lo que podría reflejar mejoras en las condiciones de salud o las respuestas gubernamentales.
- Dosis acumuladas de vacunas administradas por país:
Brasil es el país con mayor cantidad de dosis suministradas en la región, seguido                                                          por Mexico y Argentina.
Colombia, Perú y Chile tienen menores cifras de vacunación.
Pero al analizar las dosis suministradas por habitante, Chile, Argentina y Perú son los países con mayor cantidad de dosis por habitante.
- Cobertura de vacunación vs Casos confirmados:
Se observa una relación inversa entre las coberturas de vacunación altas, y la disminución de los casos confirmados de COVID
- Tasa de letalidad:
La tasa de letalidad comparativa entre países es igual.
Influencia de enfermedades preexistentes en la letalidad:
Brasil, Argentina y Colombia son los países con mortalidades mas altas, sin embargo la prevalencia de personas fumadoras o con diabetes no son similares entre los países. Lo mismo ocurre con los países con menor letalidad como Colombia, Peru y Chile que presentan distintos niveles de prevalencia. Llevando a concluir que la letalidad del COVID no es influenciada por estos factores preexistentes.
- Situacion actual:
Brasil es el país con mayor numero de contagiados y recuperados, lo que puede estar relacionado con su densidad poblacional. 
La cifra de fallecidos es mucho menor comparada con los casos activos y fallecidos, lo que puede explicarse por la implementación de la vacunación.
