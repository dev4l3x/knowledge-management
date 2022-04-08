# Open Host Service
Es el reverso de [[Anticorruption Layer]]. En este caso la interfaz para comunicarse la definira el cliente y el supplier tendrá que proporcionar el modelo solicitado. Para no contaminar el modelo, el supplier crea una capa de abstracción (en el servidor).
Cabe destacar que el supplier puede tener varias capas distintas para distintos BC.

En la práctica podemos decir que es lo que hace REST y grpc, exponer una interfaz que abstrae el modelo interno del BC.

# Tags
#ddd 