# Aggregates (DDD)
Son como una transacción de varias entidades con el objetivo de mantener la consistencia entre todas esas entidades. Este tipo de objeto se usa cuando tenemos una lógica compleja, de esta manera agregamos varias [[Entity (DDD)]] y [[Value Object]] y solo permitimos su modificacion a través del [[Aggregate Root]].
El [[Aggregate Root]] es el responsable de coordinar las modificaciones entre todas las entidades y vo además de mantener la consistencia entre todas las entidades que lo forman, por eso se dice que un [[Aggregate Root]] es una transacción.


# Tags
#ddd 