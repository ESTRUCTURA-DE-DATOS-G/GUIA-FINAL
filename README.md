# GUIA-FINAL

Sesión 1:

1. Aplicaciones prácticas de los grafos:

- Redes sociales: Representar amistades o conexiones entre personas.
- Logística y transporte: Rutas de entrega, planificación de rutas.
- Circuitos eléctricos: Conexiones entre componentes.
- Mapas y navegación: Enrutamiento GPS.
- Diseño de redes informáticas: Conexiones entre dispositivos.
  
2.	Elabore una tabla sobre los algoritmos más importantes aplicables a un grafo. Especifique en qué consiste cada uno y muestre un ejemplo de aplicación.
- https://docs.google.com/document/d/1bWziNKhmvYNqHwsgTeW7tBpz2wdDXZ-6KXQHKhrYFt4/edit

-------PRGUNTAS ORIENTADORAS
1. ¿Cuales fueron los aprendizajes obtenidos al realizar esta guía?, liste como mínimo 3 aprendizajes y relaciónelos con su futuro que hacer profesional.
  SOLUCION
-Al realizar la guía, adquirimos una comprensión profunda de varios algoritmos de grafos, como Dijkstra y Prim. Estos algoritmos son esenciales para encontrar caminos más cortos, árboles de expansión mínima, y estructuras de conectividad en grafos.
-La habilidad de elegir y manipular la estructura de datos adecuada es crucial en el desarrollo de software. Conocer estas estructuras de grafos me permitirá optimizar el rendimiento de aplicaciones que manejan grandes volúmenes de datos interconectados, como redes sociales y sistemas de recomendación.

2. ¿Donde presento mayor dificultad resolviendo la guía? y como lo resolvieron cuales fueron las
estrategias de solución?
   SOLUCION
Al principio, tuvimos dificultades para entender cómo funcionan los algoritmos de caminos más cortos, especialmente Dijkstra y prim.

-------PRESABERES REQUERIDOS
1) Sea G un grafo y ((x,y)=(y,x)) se dice que es:
SOLUCION: b) Dirigido

2) Cuál es el algoritmo capaz de resolver el problema de camino mínimo.
SOLUCION: c) Algoritmo de Dijkstra

3) ¿Qué clase tiene los siguientes atributos?
SOLUCION: c) Grafo

-------Actividad DE TRABAJO AUTONOMO
1. En media página describir las diferencias entre los algoritmos de Dijkstra y Floyd.
SOLUCION
El algoritmo de Dijkstra se utiliza para encontrar el camino más corto desde un nodo fuente a todos los demás nodos en grafos con pesos no negativos, ideal para sistemas de navegación y redes de comunicación. Su complejidad temporal es 𝑂(𝑉2)O(V2) con matrices de adyacencia y 𝑂(𝑉log𝑉+𝐸) O(VlogV+E) usando colas de prioridad. En contraste, el algoritmo de Floyd-Warshall calcula los caminos más cortos entre todos los pares de nodos, siendo útil para análisis de redes y sistemas de transporte, con una complejidad temporal de 𝑂(𝑉3)O(V3). Dijkstra es más eficiente en grafos dispersos y no maneja pesos negativos, mientras que Floyd-Warshall trabaja bien con grafos densos y puede manejar pesos negativos, pero no ciclos negativos. Dijkstra expande rutas iterativamente desde la fuente, mientras que Floyd-Warshall actualiza una matriz de distancias considerando cada nodo como intermediario en los caminos.



