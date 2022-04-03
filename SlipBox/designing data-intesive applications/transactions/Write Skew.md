# Write Skew
Este problema se da cuando actualizamos unos datos en base a una logica de negocio.
Si una transaccion lee los datos y otra tambien los lee y los modifica da lugar a que la primera transaccion este desactualizada aunque ella no lo sepa, y por tanto puede seguir pasando la validacion de la logica de negocio aunque realmente ya no se este cumpliendo debido a que hubo una modificacion de los datos.

Por ejemplo:
1. Queremos obtener los doctores que estan on call, teniendo siempre que haber un doctor
2. Una transaccion lee los doctores que hay actualmente y ve que hay dos.
3. Otra transaccion lee los doctores que hay actualmente y ve que hay dos.
4. La primera transaccion modifica a un doctor para indicar que no esta on call y hace commit.
5. La segunda transaccion sigue creyendo que hay dos doctores en on call por lo que modifica otro doctor distinto para que no este on call y tambien hace commit.
6. Al final la base de datos queda con 0 doctores on call y violando una constraint de negocio.

# Tags
#databases #transactions 