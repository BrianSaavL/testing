#Entregable

En primer lugar la red electrica es modelada como un grafo dirigido, por lo que el algoritmo recorrera el grafo de forma iterativa. para cada nodo del grafo el algoritmo verifica si este posee hijos y en el caso que no los tenga o todos estos ya esten marcados como recorridos se suma la potencia de este nodo a una variable y se marca el nodo como recorrido. Se repite este proceso hasta que el grafo sea recorrido completamente y se retorna la variable.
