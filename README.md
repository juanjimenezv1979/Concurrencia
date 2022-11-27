# Concurrencia

El Objetivo de este Repositorio es Desarrollar módulos software, mediante la práctica en el lenguaje Java usando 
herencia de Thread para adquisición de destrezas en programación con manejo de hilos en dicho lenguaje de programación.
El Caso de estudio es el siguiente:
La empresa UXZ Ltda requiere controlar la existencia de 10000 productos los cuales se almacenan en un vector Existencias,
mientras que los pedidos de los clientes de estos productos se almacenan en un vector Ventas. Estos dos primeros vectores el llenado sera
aleatorio. Se crear un tercer vector Pedidos que represente lo que se requiere comprar para mantener el stock (cantidad de inventario), 
para esto se considera la siguiente logica: si los valores correspondientes de los vectores Existencias y Ventas son
iguales se almacena este mismo valor, si el valor de Ventas es mayor que el de Existencias se almacena el doble de la diferencia entre Ventas y Existencias,
si se da el caso de que  Existencias es mayor que Ventas, se almacena Ventas; estos cálculos indican lo que se requiere
comprar para mantener el stock de inventario. 
La empresa UXZ Ltda, adicionalmente requiere conocer el valor más alto de las ventas realizadas.
