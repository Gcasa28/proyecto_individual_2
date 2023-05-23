Proyecto individual parte 2
Gabriel Casanova

Contexto:
Los accidentes aéreos son eventos inesperados e indeseados que involucran aeronaves y se producen daños físicos a personas o a la propia aeronave. Los accidentes aéreos pueden ser causados por diversos factores, como errores humanos, fallos de equipos, problemas meteorológicos, problemas de mantenimiento, fallas en la gestión del tráfico aéreo, problemas de diseño o problemas de fabricación. Y en cuanto a sus consecuencias, pueden ser tanto en términos de pérdidas humanas como económicas.
Para este el analisis historico de todos estos accidentes nos da una perspeectiva de como atacar las carencias en la seguridad de la aviacion asi como tambien, ayudar a mejorar la capacitación de los pilotos y el personal de mantenimiento, así como a mejorar el diseño y la fabricación de aviones y equipos de aviación.

Objetivo:
Hacer un ETL, para luego realizar un EDA y por ultimo realizar KPIs que ayuden a visualizar y trabajar en base de prevenir accidentes aereos aprendiendo de los datos y accidentes del pasado, ya sea mejorando la seguridad, capacitacion y/o mentenimiento de las aeronaves.

Procedimiento:
Luego de descargar el dataset y convertirlo en un dataframe de pandas el cual pude observar que habian columnas en diferentes idiomas, muchos datos faltantes, columnas que no iba a necesitar, datos que no correspodian a la columna, asi que fui columna por columna corrigiendo para exportarlos a power bi, ya con los datos cargados ahi puedo hacerles un tratamientos mas general como corregir los tipos de datos, crear un calendario, establecer algunas metricas que me iban a servir para conformar mis KPIs, y por ultimo realizar las graficas y un informe de lo que quiere decir cada elemento de Dashboard. A continuacion mencionare con su nombre las graficas que aparecen:

- Cantidad total de accidentes : Es la cantidad total de accidentes dentro de la base de datos proporcionada (despues de realizado un ETL y EDA).

- Indice de supervivencia : Porcentaje de Supervivientes basado en todos los accidentes de aeronave registrados.

- Tasa de mortalidad : Porcentaje de fallecidos basado en todos accidentes de aeronaves registrados.

- Tasa de accidentes por operador : Porcentaje medio de los accidentes de todos los operadores.

Luego unas tablas interactivas donde de pueden ver diferentes aspectos de los accidentes aeroes como:

- El Operador : Aerolínea u operador de la aeronave.

- Lugar del accidente : Lugar donde ocurrio el siniestro.

- Tipo de aeronave : Tipo o modelo de aeronave.

- Descripcion : Breve descripción del accidente y causa si se conoce.

y por ultimo estan 3 graficos donde se muestra un top de los Lugares del accidente, tipo de aeronave con mas accidentes, y una tabla comparativa donde muestra 2 lineas una haciendo referencia a todas las personas que iban en la aeronave y otra de los fallecidos en los accidentes.

Luego se encuentran 2 paginas mas con otros 2 darshboard que aportan mas informacion si es que esta es requerida.

Aqui una pequeña descripcion de las columnas del Dataframe.