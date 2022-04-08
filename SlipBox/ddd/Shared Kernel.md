# Shared Kernel
Consiste en que ambos [[Bounded Context]] compartirán una parte del modelo que es comun a ambos BC. El principal problema de esto es que tenemos un alto acoplamiento con los otros equipos que usen el modelo compartido debido a que un cambio en el modelo nos puede afectar.

En la práctica esto se puede implementar teniendo los BC en el mismo proyecto y compartiendo el codigo, o mismo con una libreria compartida que integrarán los BC en sus proyectos.

# Tags
#ddd 