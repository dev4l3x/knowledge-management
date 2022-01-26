# [[Bad Smell]] Middleman
Se da cuando practicamente todos los métodos de una clase lo que hacen es llamar a otra directamente. Sin embargo esto puede ser que tenga sentido si estamos usando un Proxy o algunos patrones de diseño por ejemplo.

Igual tambien no tiene porque ser malo porque nos permite desacomplarnos de una clase.

Lo ideal sería evaluar sin realmente necesitamos esa clase intermediria, si existe por algún motivo.

El problema es si no sirve para nada y lo único que hace es añadir ruido, en ese lugar podemos usar el objeto al que llama directamente en lugar de usar ese intermediario.

# References



# Tags