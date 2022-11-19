# BÚSQUEDA HERÍSTICA SIN ADVERSARIOS

#### 1. ¿Qué variable representa la lista ABIERTA?
La lista abierta está representada por la variable 'openset' de la clase AStar.java (src/com/jwetherell/algorithms/graph/AStar.java).

![openset](https://github.com/serenablanco/busquedaHeuristica/blob/master/img/openset.png)

#### 2. ¿Qué variable representa la función g?
La función g está representada por la variable 'gScore' de la clase AStar.java.

![gScore](https://github.com/serenablanco/busquedaHeuristica/blob/master/img/gScore.png)

#### 3. ¿Qué variable representa la función f?
La función f está representada por la variable 'fScore', también de la clase AStar.java.

![fScore](https://github.com/serenablanco/busquedaHeuristica/blob/master/img/fScore.png)

#### 4. ¿Qué método habría que modificar para que la heurística representara la distancia aérea entre vértices?
Tendíamos que modificar el método aStar() de la clase AStar.java, ya que es este método el que evalúa los diferentes nudos y construye el mejor camino.

![método aStar](https://github.com/serenablanco/busquedaHeuristica/blob/master/img/metodo%20aStar.png)

#### 5. ¿Realiza este método reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice? Justifique la respuesta.
Sí, el método aStar() reevalúa los nudos en caso de que se encuentre una nueva ruta.
Este método cuenta con un bucle while, en el cual se evalúan los nodos de la lista abierta (openset). 
Se va guardando el mejor camino hasta el momento, pero cuando cambia la función f (fScore), se reordena la lista abierta para reevaluar los nudos.

![método aStar](https://github.com/serenablanco/busquedaHeuristica/blob/master/img/metodo%20aStar.png)
