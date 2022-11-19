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

![método aStar](https://github.com/serenablanco/busquedaHeuristica/blob/master/img/metodo aStar.png)

#### 5. ¿Realiza este método reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice? Justifique la respuesta.

