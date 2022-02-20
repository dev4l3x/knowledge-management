# Ventajas NoSQL frente a relacional
En general las bases de datos NoSQL surgen para solucionar ciertos problemas que con bases de datos relacionales sería bastante complicado, una serie de problemas que solucionan son:
* [[Escalabilidad]] ya que son horizontalmente escalables mientras que las SQL solo verticalmente.
* Queries mas especializadas
* Libertad a la hora de usar los schemas ya que usa [[Schema on read]]

Otra ventaja es la manera de representar los datos, ya que en NoSQL generalmente puedes almacenar los datos de una manera no estructurada (como los documentos que permiten tener subdocumentos dentro) que encaja más con el modelo de dominio. Generalmente en bases de datos relacionales ocurre [[Impedance mistmatch en DB]].

Sin embargo cuanto más avanza el desarrollo de un producto se van definiendo más las entidades y puede ser que al final cada vez más nuestro modelo de dominio se vaya acercando más a un modelo relacional.

# Tags
#nosqlvsrelacional 