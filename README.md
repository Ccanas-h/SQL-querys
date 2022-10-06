
>   Una tienda consciente con el cuidado del medioambiente recolecta Jeans de distintas 
partes de Chile para reciclarlos y darles un nuevo uso fabricando agendas para mujeres de escasos recursos. Sin embargo, existen otras prendas que llegan casi nuevas y deciden venderlas para solventar el negocio. Es por esto que le solicitan a usted ayuda para modernizar la tienda y llevar un control de aquellas prendas que puedan venderse. 

>En base a lo anterior, debemos desarrollar una aplicación que contenga un menú de acceso y que deberá contar con los siguientes requerimientos:

### *Requerimientos*
- En una nueva base de datos llamada unidad2-oracle, debemos cargar el archivo [unidad-oracle2](https://gist.githubusercontent.com/elrerag/18ba64101bb39bf9c37777b07c70b295/raw/01b820296fac5f64db7d4907aec365ba9a75a007/unidad2_oracle.sql "unidad-oracle2")

- El cliente usuario01 ha realizado la siguiente compra:
	- **Producto**: producto9.
	- **Cantidad**: 5.
	- **Fecha**: fecha del sistema.

>Utiliza lo que aprendiste sobre transacciones para almacenar los hechos que ocurrieron en este punto. Luego, comprueba los resultados mediante otra consulta, enfocando nuestra atención en el valor del stock, es decir, podremos ver si fue efectivamente descontado.

-  El cliente usuario02 ha realizado la siguiente compra:
	-**Producto**: producto1, producto2, producto8.
	-**Cantidad**: 3 de cada producto.
	-**Fecha**: fecha del sistema.
>Mediante el uso de transacciones, realiza las consultas correspondientes para este requerimiento y luego consulta la tabla producto para validar que si alguno de ellos se queda sin stock, no se realice la compra.

-   Realizar las siguientes consultas:
	**A**. Deshabilitar el AUTOCOMMIT.
	**B**. Insertar un nuevo cliente.
	**C**. Confirmar que fue agregado en la tabla cliente.
	**D**. Realizar un ROLLBACK.
	**E**. Confirmar que se restauró la información, sin considerar la inserción del punto b.
	**F**. Habilitar de nuevo el AUTOCOMMIT.
