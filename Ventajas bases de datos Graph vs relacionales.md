# Ventajas bases de datos Graph vs relacionales
Las pricipales ventajas que nos aporta una base de datos basada en grafos son:
* La posibilidad de modelar datos que esta fuertemente interconectamos con la flexibilidad de poder añadir nuevas relaciones en un futuro (en sql tendriamos que cambiar el schema).
* Queries para acceder a datos relacionales más sencillas en comparación con SQL (tenidriamos que hacer JOINS complejos)

Si tenemos datos muy interconectados que se pueden representar mediante grafos compensa usar más una [[Graph Database]] por la compejidad que nos oculta. Sin embargo si tenemos un conjuto de datos bien estructurado (un modelo que esta bien definido y no cambia frecuentemente) podemos beneficiarnos de las ventajas de las bases de datos relacionales ya que va a ser más rapido.

Un problema de las [[Graph Database]] es que para saber la estructura interna de ese grafo tiene que comprobar cada uno.


# Tags
#databases #nosqlvsrelacional 