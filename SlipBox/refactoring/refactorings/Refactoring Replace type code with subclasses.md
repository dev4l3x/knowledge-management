# Refactoring Replace type code with subclasses
Cuando una clase tiene un campo tipo (generalmente enumerado) podemos utilizar polimorfismo para diferenciar los tipos en lugar de una propiedad.
Esto generalmente compensa (sobre los enumerados) si esos tipos tienen campos o comportamiento especificos de ellos.

Para refactorizar eso se podría utilizar el patrón `Strategy` o `State`.

# References



# Tags