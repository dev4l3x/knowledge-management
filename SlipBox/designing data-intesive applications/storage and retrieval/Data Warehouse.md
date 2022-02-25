# Data Warehouse
Como hace queries a la base de datos de producción en modo [[OLAP (Online Analytics Processing)]] sería bastante costoso (porque accede a muchos datos de golpe y son queries que requieren un procesamiento pesado) se usan los Data Warehouse, que son bases de datos que reciben los datos de las bases de datos originales (de muchas a la vez generalmente) y los convierten en datos basados en eventos. Posteriormente se pueden hacer queries [[OLAP (Online Analytics Processing)]] sobre esos conjuntos de datos sin preocuparse de interferir con las BD de producción.

Una gran ventaja de tener los datos para análisis en otra BD es que podemos usar otra tecnología distinta que nos permita hacer el tipo de queries que necesitamos de una manera más especializada.

# Tags
#databases #datawarehouse