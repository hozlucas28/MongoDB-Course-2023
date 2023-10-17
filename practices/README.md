## Observaciones

- Al eliminar un índice, empleando <code>dropIndex()</code> ó <code>dropIndexes()</code>, debo indicar el nombre que le asigno la base de datos al mismo durante su creación.
- Para que una base de datos se cree exitosamente hay que crear un colección en la misma en la misma instancia de ejecución.
- Si el objeto condición de un método esta vacio, entonces todos los registros de la colección se veran afectados por el método.
- Si quiero buscar un registro en base a su indetificador debo emplear la función <code>ObjectId()</code> en el valor de la condición <code>\_id</code>.
