# Refactoring Separate query from modifier
Separar operaciones que tienen side effects de las que no, es decir si una operación devuelve un objeto lo ideal es que no mute ningun parametro ni realice nada más de lo que dice el nombre. 
No hay que tomarse esta norma siempre al 100% ya que puedes tener algún side effect como puede ser usar una cache en un get para mejorar la velocidad.

# References



# Tags