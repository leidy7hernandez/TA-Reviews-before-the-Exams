1) En Big Data, la característica variedad consiste en:

a- El establecimiento de un flujo de datos masivo y continuo
b- Poder gestionar y canalizar grandes volúmenes de datos provinientes de diversas fuentes
c- Poder trabajar con datos estructurados y no estructurados

2) El Teorema CAP dice que:

a- Un sistema SQL tiene la característica de ser consistente
b- Un sistema No-SQL puede ser tolerante a particiones y consistente
c- No es posible para ningún sistema de bases de datos garantizar al mismo tiempo consistencia, disponibilidad y tolerancia a particiones
d- Un sistema SQL puede ser consistente y estar disponible
e- Un sistema SQL o No-SQL no puede garantizar al mismo tiempo consistencia, disponibilidad y tolerancia a particiones

3) En un cluster que tiene un factor de réplica de 3 y un tamaño de bloque de 128 MB, se guarda un archivo de 2000 MB ¿Cuántos segmentos del archivo original se deberán distribuir a lo largo del cluster?

a- 48
b- 47
c- 17

4) Señale la característica relevante de Apache Spark:

a- Notable mejora en la velocidad de procesamiento debido al uso de la memoria RAM del cluster
b- Puede sustituir todas las funcionalidades de los motores No-SQL
c- Tolerancia a fallos de red

Responder utilizando los archivos provistos en las carpetas "data_cp_airports" y "data_cp_flights". Se pueden encontrar en este enlace: https://drive.google.com/drive/folders/1ntcy9Ks72bjuBOEwCVZPFzki7ofBZade 

Nota: para la realización de los puntos 16 al 20, se puede utilizar el entorno visto en clase ubicado en el repositorio: https://github.com/soyHenry/DS-M4-Cluster_Spark

Quitar de la tabla "flights" los registros que tengan valores nulos o faltantes en los campos "ArrDelay" y "DepDelay". Luego contestar las siguientes preguntas:

5) Si consideramos que cuando el campo ArrDelay es mayor a 25 el vuelo está demorado; contestar: ¿cuál es la tupla de aeropuertos con mayor cantidad de vuelos demorados entre sí? Nota: es posible tomar el nombre del aeropuerto desde el archivo "airports.csv", donde "airport_id" se puede relacionar con "OriginAirportID" y "DestAirportID" de la tabla "flights"

a-Honolulu International - Kahului Airport
b-San Francisco International - Los Angeles International
c-Chicago O'Hare International - San Francisco International

6) Si consideramos que cuando el campo ArrDelay es mayor a 25 el vuelo está demorado; contestar: ¿cuál es la cantidad de vuelos demorados?

a-380502
b-1255037
c-2309883