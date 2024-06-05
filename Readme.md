# <h1 align=center>**`SINIESTROS VIALES`**</h1>  
<p align="center">
<img src="Imagen.jpg" height="300">
</p>

En la era actual de la ciencia de datos, la capacidad para recopilar, analizar y comprender grandes volúmenes de datos se ha convertido en una herramienta indispensable para abordar los desafíos sociales más apremiantes. En este contexto, los siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA) representan un área de interés crítico que demanda una atención informada y basada en datos.

Como analistas de datos, nos encontramos ante el desafío de utilizar la información disponible para identificar patrones y tendencias significativas que puedan informar políticas y acciones efectivas en materia de seguridad vial. En este sentido, el análisis de todas las incidencias de los siniestros viales entre 2016 y 2021 en CABA, se presenta como una oportunidad para aplicar nuestro conocimiento y habilidades en ciencia de datos para abordar un problema que impacta directamente en la vida y la seguridad de los ciudadanos.

A lo largo del proyecto, exploraremos el conjunto de datos con un enfoque riguroso y analítico, utilizando herramientas y técnicas avanzadas de visualización y modelado de datos para revelar insights significativos sobre la naturaleza y la incidencia de los siniestros viales en nuestra ciudad. Al hacerlo, buscamos no solo proporcionar una visión detallada de los patrones de ocurrencia de estos eventos, sino también contribuir al desarrollo de estrategias proactivas y preventivas que puedan salvar vidas y mejorar la calidad de vida de nuestros conciudadanos.

### Objetivo
Comprender las causas y patrones de los siniestros viales en Buenos Aires mediante estrategias basadas en datos.

## Objetivos específicos:

* Analizar datos históricos de siniestros viales para identificar variables relevantes.
* Analizar la frecuencia de siniestros a lo largo del día, la semana o el año para comprender cuándo ocurren con mayor frecuencia.
* Identificar áreas geográficas con una alta concentración de siniestros. Esto podría ayudar a implementar medidas preventivas específicas en esas zonas.
* Explorar relaciones entre variables y patrones de ocurrencia de siniestros.
* Investigar las causas subyacentes de los siniestros para tomar decisiones informadas.
* Proponer estrategias de intervención basadas en los resultados del análisis.
* Contribuir a la toma de decisiones para la prevención de siniestros viales en Buenos Aires
* Utilizar los insights obtenidos para proponer mejoras en la infraestructura vial y en las políticas de seguridad vial.

## Alcanzando estos objetivos, esperamos:

* Reducir el número de siniestros viales en Buenos Aires.
* Minimizar el impacto de los siniestros en la seguridad vial, la infraestructura y la economía.
* Crear un ambiente vial más seguro para todos los usuarios de las calles.

### Contexto

Los accidentes de tránsito son incidentes que involucran vehículos y pueden ser causados por múltiples factores, resultando en daños materiales y/o físicos a los implicados. En la densamente poblada Ciudad Autónoma de Buenos Aires, con un tráfico considerable, estos eventos son una preocupación constante por su impacto en la seguridad pública, la infraestructura vial, y los servicios de emergencia.

Con una población de 3,120,612 habitantes en un área de 200 km² según el censo de 2022, y más de 12 millones de vehículos circulando por sus autopistas en julio de 2023, la prevención de accidentes y la implementación de políticas de seguridad vial eficaces son cruciales. Argentina enfrenta una preocupante situación respecto a las muertes por siniestros viales, con cifras alarmantes según los informes del Sistema Nacional de Información Criminal (SNIC). Entre 2018 y 2022, se registraron 19,630 muertes en accidentes de tráfico en todo el país, lo que equivale a un promedio de 11 personas fallecidas por día. Estas estadísticas evidencian una problemática que afecta a nivel nacional, siendo esencial abordarla de manera específica en la Ciudad de Buenos Aires.

El proyecto se enfoca en analizar a fondo los siniestros viales en CABA, entre los años 2016 y 2021, identificando patrones, tendencias y factores clave que puedan contribuir a la toma de decisiones informadas. Con un enfoque integral, se busca comprender la dinámica de estos incidentes, desde aspectos temporales y geográficos hasta la influencia de diferentes tipos de vehículos y actores en las vías públicas.

### Descripción del Problema

En el contexto de una ciudad con altas densidades de tráfico y población como Buenos Aires, los siniestros viales representan una preocupación constante. Este proyecto tiene como objetivo principal analizar los datos de homicidios en siniestros viales entre los años 2016 y 2021 para proporcionar información crucial que guíe medidas de prevención efectivas.

### Desarrollo del Proyecto

El desarrollo del proyecto se divide en varias etapas:

Extracción, transformación y carga (ETL): Se cargan y transforman los datos de siniestros viales para su posterior análisis.

Análisis Exploratorio de Datos (EDA): Utilizando Pandas, Numpy, Seaborn, Matplotlib y Folium, se exploran patrones, relaciones y tendencias en los conjuntos de datos. Se identifican variables clave para la presentación en el panel de control (dashboard).

Creación del Dashboard en Power BI: Se desarrolla un panel de control interactivo en Power BI destacando análisis clave por variables temporales, genero, ubicacion geográficas y relacionadas con las víctimas.

Definición de KPI y Conclusiones: Se establecen Indicadores Clave de Desempeño (KPIs). Se presentan conclusiones y recomendaciones para mejorar la seguridad vial en CABA.


### Estructura del Proyecto
La estructura del proyecto sigue un patrón organizativo claro para facilitar la comprensión y reproducción. A continuación, se detalla la estructura de carpetas y archivos:

/DataSet: Contiene los conjuntos de datos utilizados, los datos limpios y el Dashboard en Power BI.
README.md: descripción y documentación del proyecto
EDA.ipynb: Análisis Exploratorio de Datos.
ETL.ipynb: Extracción, transformación y carga de los datos.
Homicidio_Jk.pbix: DashBoard de PowerBi del proyecto

### Ámbito del Proyecto

El proyecto se desarrolló siguiendo estos aspectos clave:

* Preprocesamiento de datos:  El documento ETL.ipynb se encuentra en el repositorio de este sitio
* Análisis exploratorio de datos y Desarrollo de KPI's El documento EDA.ipynb se encuentra en el repositorio de este sitio


# Tecnologías Utilizadas

El proyecto hace uso de diversas tecnologías y herramientas para realizar un análisis exhaustivo de los siniestros viales. Algunas de las principales tecnologías utilizadas incluyen:

- [![Visual Studio Code](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue)](https://code.visualstudio.com/)
- [![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)]
- [![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)](https://jupyter.org/)
- [![Pandas](https://img.shields.io/badge/Library-Pandas-brightgreen)](https://pandas.pydata.org/)
- [![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-blue)](https://matplotlib.org/)
- [![Seaborn](https://img.shields.io/badge/Library-Seaborn-yellow)](https://seaborn.pydata.org/)
- [![GitHub](https://img.shields.io/badge/Platform-GitHub-lightgrey)](https://github.com/)
- [![Git](https://img.shields.io/badge/Version%20Control-Git-blue)](https://git-scm.com/)
- [![Power BI](https://img.shields.io/badge/BI%20Tool-Power%20BI-yellow)](https://powerbi.microsoft.com/)
- ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)


### Metodología implementada en ETL

El proceso de Extracción, Transformación y Carga (ETL) es esencial en el análisis de datos, permitiendo la preparación y el modelado de datos para su posterior análisis. En este proyecto, nos enfocaremos en un conjunto de datos específico relacionado con homicidios en siniestros viales en la Ciudad de Buenos Aires durante el período 2016-2021. A través del ETL, buscaremos comprender la naturaleza y las características de estos incidentes, identificando patrones significativos que puedan ayudar a las autoridades locales a tomar medidas efectivas para reducir la cantidad de víctimas fatales en siniestros viales.

**1. Eliminación de Duplicados y verificamos tipo de datos por cada tabla :** Para asegurar la unicidad de las filas en el conjunto de datos, se han eliminado los duplicados y verificando tipos de datos para cada tabla.

**2. Filtrado de Fechas Inválidas:** Se ha realizado un filtrado riguroso en la columna 'FECHA' para identificar y cuantificar los valores atípicos que no cumplen con el formato aaaa-mm-dd. Esto proporciona una comprensión clara de la calidad de los datos y posibles problemas en las fechas de lanzamiento.

**3. Union de las tablas:** Como parte de la transformación se ha realizado la union de las tablas por medio del identificador de siniestro combinando la informacion completa y se pueda trabajar de manera mas optima.

**4. Gestión de Valores Nulos:** Manejo de datos faltantes: Imputación, eliminación o sustitución de valores faltantes. Eliminación de duplicados: Remover registros duplicados. Corrección de errores: Corregir errores en los datos, como formatos incorrectos o valores anómalos. Eliminación de duplicados: Remover registros duplicados. 

**5. Identificación de Outliers:** Para asegurar la integridad de las columnas, se ha revisado cuidadosamente mediante la ordenación y filtrado de los primeros y últimos valores. Esta inspección visual permite identificar posibles outliers o valores incoherentes que podrían requerir tratamiento adicional para su corrección o eliminación.

**6. Eliminación de Registros Incoherentes:** La eliminación de registros incoherentes es una medida importante para mantener la calidad de los datos. En caso de encontrar registros con valores nulos en todas las columnas relevantes para la API, se ha procedido a eliminarlos. Esto asegura que los análisis futuros se basen en datos confiables y coherentes.

**7. Creacion de nuevas columnas:** se crearon dos columnas nuevas como barrio para realizar análisis geográfico y determinar comportamiento de los siniestros por barrio.

*Todas estas etapas se llevaron a cabo de manera local en **Visual Studio Code (VSCODE)**, empleando **Jupyter Notebook** como nuestro entorno principal. Para la implementación de cada paso, contamos con la potencia de **Python** como lenguaje de programación, respaldado por las versátiles bibliotecas **numpy y pandas**, que fueron fundamentales para la manipulación y transformación eficiente de los datos. Estas herramientas esenciales se combinaron hábilmente para crear un flujo de trabajo fluido y eficaz, permitiendo que el proyecto tomara forma de manera coherente y organizada.*

### Metodología implemetada para EDA

El Análisis Exploratorio de Datos (EDA) es una fase crucial en el proceso de análisis de datos que busca comprender la naturaleza y las características de un conjunto de datos antes de aplicar modelos más avanzados o llegar a conclusiones. En este proyecto de EDA, nos enfocaremos en un conjunto de datos relacionado con homicidios en siniestros viales en la Ciudad de Buenos Aires durante el período 2016-2021. A través del EDA, exploraremos diferentes aspectos de los datos para extraer información valiosa y patrones significativos. El objetivo principal es proporcionar una visión comprehensiva de los incidentes, identificando tendencias, relaciones y posibles áreas de intervención para mejorar la seguridad vial en la ciudad.

**1. Definición del Problema y Objetivos:** Definir claramente el problema: ¿Qué se busca entender o resolver? Establecer objetivos específicos: ¿Cuáles son las preguntas clave que se necesitan responder?

**2. Recolección de Datos:** Cargue del dataset de datos: homocidios.csv. Recolección de datos: Extraer y consolidar los datos necesarios para el análisis.

**3. Análisis Exploratorio de Datos (EDA):** Descriptiva inicial: Calcular medidas estadísticas básicas como media, mediana, moda, desviación estándar, etc. Visualización de datos: Usar gráficos y visualizaciones para identificar patrones y tendencias. Esto incluye histogramas, gráficos de barras, gráficos de dispersión, diagramas de caja, mapas de calor, etc. Identificación de outliers: Detectar y analizar valores atípicos.
Análisis de correlación: Evaluar la relación entre diferentes variables mediante matrices de correlación y gráficos de dispersión.

**4. Análisis Detallado:** Segmentación de datos: Dividir los datos en subconjuntos relevantes para análisis más específicos. Análisis temporal: Examinar cómo varían los datos a lo largo del tiempo. Análisis geoespacial: Analizar la distribución geográfica de los datos (si aplica). Análisis de grupos y perfiles: Identificar y analizar grupos o clusters dentro de los datos.

**5. Interpretación de Resultados:** Resumir hallazgos clave: Describir las principales conclusiones del EDA. Relacionar con los objetivos: Vincular los hallazgos con los objetivos del análisis. Identificar áreas de interés: Señalar áreas que requieren un análisis más profundo o que presentan oportunidades para intervención.

**6. Documentación y Reporte:** Documentar el proceso de EDA: Mantener un registro detallado de los pasos seguidos, las herramientas utilizadas y las decisiones tomadas. Preparar un reporte: Crear un informe claro y conciso que presente los hallazgos, visualizaciones clave y conclusiones. Comunicación de resultados: Presentar los resultados a las partes interesadas de manera efectiva, utilizando DasBoard de PowerBi.
Herramientas Comunes Utilizadas en EDA. Lenguajes de Programación: Python (con librerías como pandas, numpy, matplotlib, seaborn). Plataformas de Visualización: Power BI. Entornos de Desarrollo: Jupyter Notebook.

Implementar esta metodología asegura que el EDA sea sistemático y exhaustivo, permitiendo a los analistas de datos extraer insights valiosos y tomar decisiones informadas basadas en los datos.

### Análisis de Datos

El análisis realizado revela una serie de patrones significativos en relación con los homicidios, abordando variables temporales, perfiles de víctimas y distribución espacial.

En primer lugar, se observa una disminución notable en la cantidad de homicidios en el año 2020, atribuible a las medidas de cuarentena por COVID-19. Sin embargo, esta tendencia no se replica de manera consistente en años anteriores. Aunque diciembre destaca como un mes con un pico en el número de víctimas, esta tendencia no es uniforme en todos los años, sugiriendo una posible influencia de la flexibilización de las restricciones de cuarentena en los patrones de homicidios.

Al analizar escalas temporales más detalladas, se encuentra que la mayoría de los homicidios ocurren entre lunes y viernes, lo que podría relacionarse con el traslado diario al trabajo. Sin embargo, no se observan diferencias significativas en la distribución de víctimas entre los días de la semana. Además, un porcentaje considerable de las víctimas se registra en las primeras horas de la mañana, aunque la mayoría de estos incidentes ocurrieron durante el fin de semana.

En cuanto al perfil de las víctimas, se destaca que la mayoría son hombres, en su mayoría dentro del rango de edad de 25 a 35 años. Cerca de la mitad de las víctimas son conductores, principalmente de motocicletas, y la responsabilidad del accidente recae principalmente en vehículos como automóviles, colectivos y camiones.

En términos de distribución espacial, los accidentes en las avenidas son comunes en todas las comunas de la Ciudad Autónoma de Buenos Aires, con la mayoría de las víctimas perdiendo la vida en estos lugares, especialmente en los cruces con otras calles. El rol de la víctima varía entre moto y peatón dependiendo de la comuna.

Este análisis integral proporciona una visión detallada de los patrones temporales, el perfil de las víctimas y los factores espaciales relacionados con los homicidios, lo que puede ser fundamental para identificar áreas de enfoque en términos de prevención y políticas públicas orientadas a la seguridad ciudadana.

### Análisis de KPI's

En función de lo analizado en el punto anterior, se plantearon tres objetivos en relación a la disminución de la cantidad de víctimas fatales de los siniestros viales, desde los cuales se proponen tres indicadores de rendimiento clave o KPI.

* Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*

Las tasas de mortalidad relacionadas con siniestros viales suelen ser un indicador crítico de la seguridad vial en una región. Se define como Tasa de homicidios en siniestros viales al número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico, en este caso se toman 6 meses. Su fórmula es:  (Número de homicidios en siniestros viales / Población total) * 100,000

Como Población Total se calculó la población para el año 2021 a partir de los censos poblacionales del año 2010 y 2022.

En este caso, para el año 2021, la Tasa de homicidios en siniestros viales fue de 1.42 lo que significa que, durante los primeros 6 meses del año 2021, hubo aproximadamente 2.85 homicidios en accidentes de tránsito por cada 100,000 habitantes. Ahora, el objetivo planteado es reducir esta tasa para el siguiente semestre de 2021 en un 10%, esto es 1.86. Cuando se calcula el KPI para este período se obtiene que la Tasa de homicidios en siniestros viales fue de 1.86, lo que significa que para el segundo semestre de 2021 SI se cumple con el objetivo propuesto.

* Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior*

Como se vio en el análisis exploratorio, el 44% de las víctimas mortales se transportaban en moto al momento del hecho. Por lo que se consideró importante proponer el monitoreo de la cantidad de accidentes mortales en este tipo de conductor. Para ello se define a la Cantidad de accidentes mortales de motociclistas como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. La fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

Para este caso, se toma como año actual al año 2021 y como año anterior al año 2020. En primer lugar, se calculó la Cantidad de accidentes mortales de motociclistas para el año 2020, el cual resultó de 36, de esta manera el objetivo a cumplir es de 25 (es decir, la reducción del 7% de la cantidad de accidentes para 2021). El calcular la Cantidad de accidentes mortales de motociclistas para el año 2021 resultó de 46 lo que significa que aumentó un 73% la cantidad de muertes de conductores de motociclistas respecto del 2021. Por no anterio, Este KPI No se cumple.

* ### Definición del KPI Propuesto:

Reducir en un 10% el número de siniestros viales con víctimas mortales que ocurren en avenidas en la ciudad de Buenos Aires, comparado con el año anterior.

Fórmula: Reducir la cantidad de accidentes mortales en avenidas en el último año = ((numero_siniestros_mortales_año_anterior_avenidas - numero_siniestros_mortales_ultimo_año_aavenidas) / numero_siniestros_mortales_año_anterior_avenidas) * 100

* Justificación del KPI:

Relevancia: Las avenidas suelen ser las vías con mayor tráfico y velocidad, lo que aumenta la probabilidad de siniestros viales con consecuencias graves. Reducir los accidentes en estas vías puede tener un impacto significativo en la seguridad vial general.

Medible: Este KPI se puede medir con precisión utilizando los datos existentes sobre la ubicación y gravedad de los siniestros.

Accionable: Permite focalizar esfuerzos en medidas preventivas como mejoras en la infraestructura, control de velocidad y campañas de concientización específicamente en avenidas.

Temporalidad: Evaluar la reducción de siniestros en un periodo anual permite ajustar estrategias y políticas de seguridad vial de manera continua.

* Implementación del KPI:

1. Filtrar los siniestros en avenidas.

2. Contar el número de siniestros viales con víctimas mortales en el último año y en el año anterior.

3. Calcular la reducción porcentual.

4. Determinar si se cumplió el objetivo del 10%.

La propuesta del KPI, ayudará a focalizar los esfuerzos de reducción de siniestros en una de las áreas más críticas de la infraestructura vial urbana, las avenidas, contribuyendo así a mejorar la seguridad general en la ciudad de Buenos Aires.

Como Respuesta del KPI propuesta, nos indica lo siguiente: Número de siniestros viales con víctimas mortales en avenidas en 2020: 52, Número de siniestros viales con víctimas mortales en avenidas en 2021: 61, Reducción en porcentaje: -17.31% ¿Se cumplió el objetivo del 10% de reducción? No

### Conclusiones.

Reducción de Accidentes Durante la Pandemia: La distribución anual de accidentes muestra una clara reducción en 2020, coincidiendo con el inicio de la pandemia de COVID-19 y las consecuentes restricciones de movilidad. Este hallazgo destaca cómo las medidas de cuarentena impactaron significativamente en la disminución de la actividad vial y, por ende, en los accidentes.

Variabilidad en los Accidentes Fatales: No se observa un patrón consistente de accidentes fatales mes a mes a lo largo de los años. Sin embargo, desde diciembre de 2019 hasta noviembre de 2020, hubo una notable disminución en los accidentes fatales, probablemente debido a las restricciones de movilidad impuestas durante la pandemia.

Tendencias y Picos Anuales: La tendencia general del número de víctimas de accidentes fatales muestra una variabilidad significativa año tras año. Los años 2018, 2016 y 2017 presentan picos notables en la cantidad de accidentes, lo cual puede estar asociado con factores específicos de esos años.

Consistencia en la Severidad de los Accidentes: El análisis de la información de víctimas, revela que la mayoría de los incidentes fatales involucran una sola víctima. Este patrón sugiere una consistencia en la gravedad de los accidentes, siendo raro que un siniestro resulte en más de una víctima fatal.

Distribución Demográfica de las Víctimas: El 75% de las víctimas fatales son menores de 55 años, con una mediana de 39 años. La mayor concentración de víctimas fatales se encuentra entre los 20 y 40 años. Los hombres, especialmente jóvenes, son más frecuentemente víctimas que las mujeres, quienes suelen ser adultas mayores.

Roles y Edades de las Víctimas: Los conductores y pasajeros acompañantes tienen edades promedio similares, alrededor de 35 años. Los peatones suelen ser adultos y adultos mayores, con una variabilidad más amplia en edades, incluyendo niños en algunos casos.

Distribución Geográfica de los Accidentes: Las comunas con mayor cantidad de víctimas fatales son las Comunas 1, 4, 9, 8 y 7, con la Comuna 1 liderando significativamente. Estas áreas presentan vías muy transitadas, lo que aumenta el riesgo de accidentes.

Accidentes en Avenidas: Las avenidas concentran una mayor cantidad de accidentes fatales, probablemente debido a factores como el alto flujo de vehículos y la complejidad de las señalizaciones y normas de tránsito.

Tipos de Vehículos Involucrados: Las víctimas son principalmente peatones, motociclistas y conductores de automóviles. Los automóviles y motocicletas son los acusados más frecuentes en los accidentes donde la víctima es un peatón.

Horarios de Mayor Riesgo: Los accidentes son más frecuentes en horarios de despliegue y regreso laboral, específicamente entre las 5am y 9am, y entre las 4pm y 7pm.

### Recomendaciones

Implementación de Medidas de Seguridad en Avenidas: Dado que las avenidas son puntos críticos, es vital mejorar las señalizaciones, implementar reductores de velocidad y aumentar la presencia de controles policiales.

Campañas de Concientización y Educación Vial: Desarrollar campañas educativas dirigidas especialmente a los jóvenes, quienes constituyen la mayor proporción de víctimas. Enfocar estas campañas en el uso de motocicletas y el comportamiento de los peatones puede ser particularmente efectivo.

Mejora de la Infraestructura Vial: Aumentar y mejorar la infraestructura para ciclistas y peatones, incluyendo más ciclovías y cruces peatonales seguros, especialmente en las comunas más afectadas.

Políticas de Tráfico y Regulaciones: Fortalecer la aplicación de las leyes de tráfico, especialmente en las horas pico, y considerar sanciones más severas para infracciones graves, como el exceso de velocidad y el uso de dispositivos móviles al conducir.

Uso de Tecnologías Avanzadas: Integrar sistemas de monitoreo del tráfico en tiempo real y promover el uso de vehículos con tecnologías avanzadas de asistencia al conductor para reducir el riesgo de accidentes.

Análisis Continuo de Datos: Establecer sistemas robustos para la recolección y análisis continuo de datos sobre siniestros viales, permitiendo a las autoridades identificar rápidamente las áreas problemáticas y evaluar la efectividad de las medidas implementadas.


### Invitación a la Colaboración Comunitaria: 

Comparte tus Ideas,  Contribuciones, Si tienes ideas, sugerencias o te gustaría colaborar, no dudes en enviar mensaje para enriquecer el proyecto.

### Agradecimientos

Agradezco a HENRY por apoyo y por proporcionar conocimientos, ténicas y tecnologías de punta valiosos para este proyecto. Este proyecto no solo es un análisis de datos; es un esfuerzo colaborativo para hacer que las calles de Buenos Aires sean más seguras. ¡Gracias por explorar nuestro trabajo! Gracias por tu interés y apoyo.





