# Grafos

Un grafo es una estructura de datos que permite representar a los objetos como vértices y aristas. A simple vista se puede pensar que la única utilidad de un grafo es estética, pero su versatilidad yace en representar de forma abstracta e intuitiva las relaciones entre objetos y como se conectan entre sí. Esta herramienta tiene un sin fin de aplicaciones en las [Telecomunicaciones](Anexos/Telecomunicaciones.md), [Ciencia de datos](Anexos/Ciencia_de_datos.md), [Machine Learning](Anexos/Machine_Learning.md) e [Inteligencia artificial](Anexos/Inteligencia_artificial.md).

Su primera aplicación fue en [El problema de los siete puentes de Königsberg](Anexos/El_problema_de_los_siete_puentes_de_Königsberg.md) solucionado por el matemático [Leonhard Euler](Mencion/Leonhard_Euler.md).

## Partes de un grafo

- **Nodos**: objetos que pueden tener relación con uno o más objetos.
- **Relaciones**: líneas o aristas que conectan a los objetos y brindan contexto de las conexiones de los objetos.
- **Nodos padre**: nodo central que hace referencia a otros nodos.
- **Nodos hijo**: nodo referenciado a un nodo padre.

## Tipos de grafos

- **No dirigido**: mapa de grafos que no usa flechas, únicamente aristas.
- **Dirigido**: mapa de grafos que utiliza flechas para representar que nodos hacen referencia a otros.
- **Ponderado**: a los grafos se les asigna un peso o grado dependiendo del numero de referencias que realice. El grado de un nodo puede representar la distancia, gastos, temperatura o cualquier medida relevante.
- **Conexo**: es cuando se puede llegar de un nodo a otro recorriendo una ruta (existe conectividad entre todos los nodos).
  ![Grafo conexo](conexo.png)
- **Acíclico**: no existe un camino cerrado en un grafo.
- **Completo**: la ruta en un grafo es cerrada y no se repite dos veces la misma arista.
  ![Grafo completo](completo.png)

## Terminología de grafos

- **Ciclo**: es una ruta en un mapa de nodos que comienza y termina en el mismo vértice.
- **Grado de un nodo**: numero de aristas, referencias o conexiones que tiene un nodo.
- **Camino**: una ruta en un mapa de nodos.

## Proximamente...

- Cómo aplicar los grafos en programación
- Cómo hacer [Backtracking](Algoritmos/Backtracking.md)
- Cómo crear y usar el [Algoritmo Dijkstra](Algoritmos/Dijkstra.md)
- Cómo crear y usar el algoritmo [A asterisco](Algoritmos/A✳️.md)
- Cómo aplicar grafos en mapas.

### [Bibliografía](Bibliografía/Bibliografía.md)
