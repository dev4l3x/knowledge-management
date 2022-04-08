# Separate Ways
Esta estrategia se utiliza cuando el coste de integrar varios [[Bounded Context]] supera a los problemas que puedan causar tener el código duplicado en cada BC. De esta manera consistiría en duplicar el código comú en cada BC y ahorrarnos la comunicación entre ellos.

Esta es una medida a tomar con mucha cautela y nunca se debería usar con los BC que forman parte del core, ya que estos son los que te aportan la ventaja competitiva y tienen que ser fáciles de mantener y evolucionar.

# Tags
#ddd 