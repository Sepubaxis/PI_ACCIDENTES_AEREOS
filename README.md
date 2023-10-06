<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 

### **Contexto**

Los accidentes aéreos son eventos inesperados e indeseados que involucran aeronaves y se producen daños físicos a personas o a la propia aeronave. Un accidente aéreo puede involucrar cualquier tipo de aeronave, incluyendo aviones comerciales, aviones privados, helicópteros, planeadores y globos aerostáticos.

Los accidentes aéreos pueden ser causados por diversos factores, como errores humanos, fallos de equipos, problemas meteorológicos, problemas de mantenimiento, fallas en la gestión del tráfico aéreo, problemas de diseño o problemas de fabricación. Y en cuanto a sus consecuencias, pueden ser tanto en términos de pérdidas humanas como económicas.

Es por eso que la industria de la aviación, las autoridades reguladoras y los investigadores trabajan incansablemente para mejorar la seguridad de la aviación y prevenir futuros accidentes. Por otro lado, para las organizaciones asociadas a la aviación, estudiar la causalidad de los accidentes y aprender a cómo prevenirlos en el futuro es clave para poder evitar pérdidas humanas y daños materiales significativos. 


### **Rol a desarrollar**

La **Organización de Aviación Civil Internacional (OACI)**, organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, el objetivo principal es poder obtener un análisis de datos relacionado a esto, junto a un dashboard que complemente los análisis con sus visualizaciones. 

La OACI únicamente cuenta con un dataset sobre datos de accidentes de aviones, pero insta a la consultora de datos -de la que forman parte- que intente cruzar esta información con otras fuentes de su interés. Esto con el objetivo de obtener mayor claridad y consistencia en los fundamentos del estudio.

## **Propuesta de trabajo -mínimos entregables-**
*Es importante que a la hora de empezar a desarrollar cada item, y tu demo, te ayudes tambien de la [rúbrica de evaluación](https://docs.google.com/spreadsheets/d/e/2PACX-1vTV3zL1aeGRlbXkiy5012GWbDBMseA4iziMXs597TZfgaYgazjxZDx_-q6L4s9io3JW4UPHcZs_XNyz/pubhtml).* 😄

`EDA` (Exploratory Data Analysis)

Debes realizar un análisis exploratorio de los datos en un notebook. Tienen que estar tus pasos documentados con claridad, con las conclusiones correspondientes en cada gráfico empleado y análisis de lo que vas observando, utilizando celdas Markdown para tal fin. La prolijidad del notebook será un aspecto a evaluar. Es importante que tengas en cuenta que, en muchas oportunidades y trabajos, un EDA constituye un entregable en sí mismo.

En esta línea, hay varios aspectos indispensables que **deben** ser abordados en cualquier Análisis Exploratorio de Datos y tomaremos como punto de partida para evaluar tu performance en este apartado. Entre estos aspectos destacados se encuentran: *búsqueda de valores faltantes, valores atípicos/extremos u outliers y registros duplicados*. Asimismo, la utilización de gráficos coherentes según la tipología de variable que corresponda resulta esencial.

***En caso de hacer uso de librerías como pandas_profiling, es indispensable acompañar los gráficos con análisis propios.***

`Dashboard`

Debe ser funcional y coherente con el storytelling. El dasbhoard tiene que incluir **filtros**, permitiendo explorar detalladamente los datos con la selección de cada uno de ellos. Es decir, es indispensable que sea **interactivo**. También, se espera que el diseño que implementen facilite la interpretación de la información y su análisis, siendo importante, para ello, la claridad en la presentación de los datos, aspectos inherentes a la esteticidad, elección coherente de los gráficos según las variables a visualizar, entre otros ítems. 

`Análisis` :warning:

No se considerará solamente la producción de gráficos con datos -dashboard-, sino también los análisis y conclusiones que puedan extraer a partir de ellos.

`KPIs`

Debes graficar y medir el KPI propuesto a continuación, representándolo adecuadamente en el dashboard. A su vez, tambíen tienes que proponer, medir y graficar un segundo KPI que consideres relevante para la temática. 
El KPI propuesto es:
- *Evaluar la disminución de un 10% la tasa de fatalidad de la tripulación en los últimos 10 años, comparado a la década anterior*.

  Definimos la **tasa de fatalidad de la tripulación** como el número total de tripulantes fallecidos en los accidentes registrados en la década a considerar, dividido en la cantidad total de accidentes aéreos ocurridos en este período de tiempo. Su fórmula es (Suma total de fallecidos en el período de tiempo / Suma total de accidentes en el período de tiempo).
  

`MUY IMPORTANTE` repasar qué es un KPI y cómo se diferencia de una métrica convencional. En el material de apoyo tienen lectura que puede ser de ayuda.</small>

`Repositorio de GitHub`

El repositorio debe contener un **Readme** principal donde presenten, en una primera instancia, de forma general **su proyecto** y detallen qué hay en cada archivo/carpeta del propio repositorio. Este Readme no puede ser el mismo de la consigna que nosotros les entregamos.
A su vez, el Readme debe incluir un **reporte de análisis con base en sus dashboards**, así como el análisis y la funcionalidad de los KPIs sugeridos.
