## exploracion_visualizacion

# Practica del modulo de Exploracion y visualizacion de datos

# Bootcamp Big Data, machine learning e IA

## PRACTICA

Dataset de kaggle sobre la evolución de los salarios en el mundo
dentro de los puestos de trabajo del sector Data.

Archivo practice_salaries_data.pbix

Dashboard que analiza los salarios medios en dolares según:

1. Salario promedio en dolares entre los años 2020 y 2023 según el tamaño de las empresas: Pequeñas, medianas y grandes.
   A través de un visual de lineas y una linea de tendencia.

2. Visual geográfico de burbujas, el tamaño representa el salario promedio en cada país y el color varia entre rojo, naranja y verde
   para el salario maximo.

3. Visual de barras verticales donde hemos agrupado las diferentes tipificaciones de trabajos en subsectores.
   Podemos ver en que subsectores hay sueldos medios más altos. A este visual le hemos añadido un tooltip en formato anillo,
   donde podemos ver que porcentaje en cada subsector son trabajos ejecutivos, senior, intermedios o junior.

4. Visula de barras horizontales donde vemos el salario promedio comparado con el tipo de trabajo: on-site, remote o hybrid,
   y a su vez por los tipos de contrato.

5. Hemos añadido una medida total de salario medio total.

6. Para los apartados 2, 3, 4, y 5 hemos dejado un filtro por años que nos permite ir seleccionando uno o más años y ver su evolución
   en los diferentes visuales.

También podemos interactuar seleccionando en alguno de los gráficos un valor determinado y ver como afecta al resto de
visuales, como elegir un país en el vieual 2, un grupo en el visual 3 o alguno de los tipos de trabajo en el 4.

# EXTRA PRACTICA

En el archivo practica_ivr.pbix hemos importado de BigQuery una tabla realizada en el modulo de SQL avanzado, ETL y DataWarehouse ivr_summary1

Dentro lo hemos dividido en dos Dashboard
Dashboard1: Analiza la duración media de las llamadas de un centro de recepción de llamadas según diferentes factores.

1. Visual de barras verticales que compara el promedio de tiempo de las llamadas con el resultado en 3 categorías y las divide también por idiomas.

2. Visual de lineas con la evolución del promedio de tiempo de las llamadas agrupado por horas, con 3 lineas adicionales que marcan el máximo, el minimo y la mediana

3. Tarjetas de información, el promedio total, el máximo y el mínimo de tiempo de las llamadas. El número varía en 3 colores según el valor, a más bajo verde, medio amarillo anaranjado y alto rojo.

4. Un visual de barras horizontales que compara el promedio del tiempo de las llamadas separando por el idioma, el segmento de cliente y divididos a su vez por el vdn_aggregation de las llamadas.

Dashboard2: Analizar el número de rellamadas en las 24h posteriores y previas del mismo número

1. Visual en anillo para ver porcentaje de rellamadas en las 24h previas del mismo número se producen en 4 tramos horarios definidos previamente a lo largo de un día

2. Visual en anillo para ver el porcentaje de rellamadas en las 24h siguientes del mismo número en los mismos 4 tramos horarios.

3. Visual medidor donde vemos el número de casos de rellamadas en las 24h siguientes sobre el total de llamadas recibidas.

4. Visual de barras en porcentaje apiladas para ver el porcentaje de rellamadas del mismo número en las 24h previas según el idioma y el tipo de identificación del cliente.

5. Visual de barras en porcentaje apiladas para ver el porcentaje de rellamadas en las 24h posteriores según el idioma y el tipo de identificación del cliente.
