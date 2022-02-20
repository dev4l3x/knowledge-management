# ¿Cuando usar NoSQL o relacional?
Generalmente obtenemos mas performance en bases de datos NoSQL cuando tenemos una aplicación que no va a usar muchas relaciones y no tiene que hacer queries extras para obtener más datos ya que estas se basan en la [[Denormalizacion de los datos]].

Cuando tenemos una aplicación con muchas relaciones nos interesa usar DB relacionales ya que proporcional operaciones JOIN sobre los datos que generalmente son más eficientes que hacer una query extra para los datos. Las bases de datos SQL se basan en la [[Normalizacion de los datos]]


# Tags
#nosqlvsrelacional 