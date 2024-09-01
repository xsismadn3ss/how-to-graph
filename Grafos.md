#principal
Su primera aplicación fue en [[El problema de los siete puentes de Königsberg]] solucionado por el matemático [[Leonhard Euler]].

Un grafo es una estructura de datos que permite representar a los objetos como vértices y aristas. A simple vista se puede pensar que la única utilidad de un grafo es estética, pero su versatilidad yace en representar de forma abstracta e intuitiva relaciones entre objetos y como se conectan entre sí. Esta herramienta tiene un sin fin de aplicaciones en la [[Telecomunicaciones]], [[Ciencia de datos]], [[Machine Learning]] e [[Inteligencia artificial]].

## Partes de un grafo
* [[Nodos]]: objetos que pueden tener relación con uno o más objetos.
* [[Relaciones]]: líneas o aristas que conectar a los objetos y brindan contexto de las conexiones de los objetos.
* [[Nodos padre]]: nodo central al cual se conecta otros nodos.
* [[Nodos hijo]]: nodo que hace referencia a uno o más nodos.

## Tipos de grafos
* [[No dirigido]]: mapa de grafos que no usa flechas, únicamente aristas
* [[Dirigido]]:  mapa de grafos que utiliza flechas para representar que nodos hacen referencia a otros.
* [[Ponderado]]: a los grafos se les asigna un peso o grado dependiendo del numero de nodos que hace referencia e él. El grado de un nodo puede representar la distancia, gastos, temperatura o cualquier medida relevante.
* [[Conexo]]:  es cuando se puede llegar a otro nodo recorriendo una ruta (existe conectividad entre todos los nodos)
	*![[Pasted image 20240831230150.png]]
* [[Acíclico]]: no existe un camino cerrado en un grafo.
* [[Completo]]: la ruta en un grafo es cerrada y no se repite dos veces la misma arista.
	![[Pasted image 20240831230543.png]]
## Terminología de grafos
* [[Ciclo]]: ruta en un mapa de nodos en el que no se repite más de una vez un nodo, a excepción del nodo inicial.
* [[Grado de un nodo]]: Numero de aristas, referencias o conexiones que tiene un nodo.
* [[Camino]]: Un ruta en un mapa de nodos

## Proximamente...
* Cómo aplicar los grafos en programación
* Cómo hacer [backtracking]
* Cómo crear y usar el [[Algoritmo Dijkstra]]
* Cómo crear y usar el algoritmo [[A✳️]] (A*)
* Cómo aplicar grafos en mapas.