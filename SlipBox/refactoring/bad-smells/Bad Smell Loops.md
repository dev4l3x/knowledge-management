# [[Bad Smell]] Loops
Es preferible utilizar funciones lambda en lugar de los clasicos `for` o `foreach` ya que aumenta considerablemente la legibilidad.
Por ejemplo, es muchas mas legible esto:

```java
objects.forEach(MyClass::update);
```

que esto:

```java
for (MyClass myObj : objects) { 
	myObj.update(); 
}
```

# References



# Tags