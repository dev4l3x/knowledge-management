# [[Bad Smell]] Feature Envy
Se da cuando tenemos un objeto que usa datos o operaciones de otras clases para hacer sus porioias operaciones, en lugar de usar sus propios datos. 
Esto se suele dar por ejemplo cuando movemos propiedades de un objeto a otro pero no las operaciones, resultando en una clase que tiene los datos y otras operaciones. 
Esto podría estar relacionado con [[Bad Smell Shotgun Surgery]] ya que para modificar algo que en principio está relacionado tendríamos que tocar varias clases


# References



# Tags