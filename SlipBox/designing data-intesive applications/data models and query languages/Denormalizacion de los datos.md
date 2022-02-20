# Denormalizacion de los datos
Es el proceso inverso de [[Normalizacion de los datos]] en el que en lugar de tener un unico sitio para datos repetidos los modelos contienen los propios datos. Sin embargo es importante destacar que la integridad de los datos se reduce bastante, ya que si queremos modificar un dato tendriamos que modificarlo en todos los lugares en los que se usa.

Sin embargo la denormalización nos aporta la ventaja de al tener todos los datos en un modelo, tenemos escrituras y lecturas más rápidas debido a que no hay que hacer queries extras para obtener más datos.

# Tags
#nosqlvsrelacional 