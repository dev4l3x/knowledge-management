# Refactoring Encapsulate Variable
Se debe encapsular una variable publica en un método de acceso para de esta manera poder aplicar una validación sobre ese campo y controlar su acceso en general. 
Además con esto reducimos el acomplamiento entre las clases que usan el campo, ya que si exponemos la variable directamente y luego se quiere añadir algo de logica sobre el valor de esa variable no podriamos.

# Relacionado con Bad Smells
[[Bad smell datos mutables]], [[Datos globales]]

# References



# Tags