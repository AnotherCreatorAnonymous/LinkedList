Carlos Jiménez, Tomas Espitia, Diego Rojas


# punto 2

## ¿Cómo afecta el tener un nodo previo a las demas funciones?
## ¿Cómo optimiza el nuevo atributo (previo) la implementación de las funciones insert/update/delete?

Incorporar el enlace prev en cada nodo de una lista enlazada hace que las operaciones de agregar y eliminar nodos sean mucho más eficientes, ya que permite acceder al nodo previo sin tener que recorrer toda la lista. Esto es especialmente útil para las inserciones y eliminaciones en el medio de la lista, que se vuelven mucho más rápidas. Además, facilita unir dos listas al conectar directamente el último nodo (tail) de una lista con el primero (head) de la otra en solo un paso. Aunque el enlace prev no mejora el tiempo de búsqueda, da más flexibilidad para reorganizar y modificar grupos de nodos en ambas direcciones, haciendo la lista enlazada más versátil y optimizada.
