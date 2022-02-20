# Graph Database
Una base de datos que utiliza una representación interna del modelo de datos basada en grafos. Las entidades se corresponderian con los vertices y las aristas se corresponden con las relacciones entre las entidades.

Es interesante usar este tipo de base de datos cuando tenemos muchas relaciones many to many entre entidades ya que los tamaños de las queries se reducen bastante y esta más acorde la representación del modelo de datos con nuestro modelo de dominio.

Por ejemplo para representar en que pais viven las personas, tendriamos una entidad pais y una persona, y muchas personas vivirian en un pais y a si vez muchos paises pueden ser nacionalidad de muchas personas.

Hay varias formas de implementar la representación de una DB basada en graphos:
1. [[Property Graphs]]
2. [[Triple Stores]]
3. [[Datalog]]


# Tags
#databases #graphs