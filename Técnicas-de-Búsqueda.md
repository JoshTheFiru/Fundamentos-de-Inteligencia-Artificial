## **Técnicas de Búsqueda**
Un **sistema de búsqueda** se compone de 3 elementos principales:
- Un conjunto de estados
- Operadores, que tendrán un coste asociado (arbitratio o atribuido)
- Una estrategia de control

Será esta estrategia de control la responsable de decidir el orden de exploración de los estados. Estas estrategias podrán ser informadas (heurísticas) o no informadas (búsqueda a ciegas).
### **-- Técnicas de Búsqueda Sin Información --**
Estas técnicas realizan recorridos sistemáticos del espacio de búsqueda, sin tener información sobre el dominio del problema. 
Las técnicas existentes son las siguientes: 
#### *Tipos de algoritmos no informados*:
- Búsqueda Primero en Anchura
- Búsqueda Primero en Profundidad
- Búsqueda de Coste Uniforme
- Búsqueda en Anchura Iterativa
- Búsqueda en Profundidad Iterativa
- Búsqueda Bidireccional

Los siguientes recursos desarrollan explicaciones sobre los diferentes algoritmos de búsqueda no informados:
- https://www.javatpoint.com/ai-uninformed-search-algorithms (Técnicas de Búsqueda sin Información)
- https://www.youtube.com/watch?v=bSv4CWMTeR0 (Prof. Pieter Abbeel. Lecture 2 Uninformed Search Universidad de Berkeley, Primavera 2014).
- https://www.youtube.com/watch?v=1wu2sojwsyQ (<a href= "https://www.youtube.com/channel/UCUbp3Qabq6iYQrN2QC-ZUXw/videos"> John Levine </a>, Búsqueda Primero en Anchura Parte 1)
- https://www.youtube.com/watch?v=n3fPL9q_Nyc (<a href= "https://www.youtube.com/channel/UCUbp3Qabq6iYQrN2QC-ZUXw/videos"> John Levine </a>, Búsqueda Primero en Anchura Parte 2)
- https://www.youtube.com/watch?v=h1RYvCfuoN4 (<a href= "https://www.youtube.com/channel/UCUbp3Qabq6iYQrN2QC-ZUXw/videos"> John Levine </a>, Búsqueda Primero en Profundidad)
- https://www.youtube.com/watch?v=Y85ECk_H3h4 (<a href= "https://www.youtube.com/channel/UCUbp3Qabq6iYQrN2QC-ZUXw/videos"> John Levine </a>, Búsqueda en Profundidad Iterativa)
- https://www.youtube.com/watch?v=dRMvK76xQJI (<a href= "https://www.youtube.com/channel/UCUbp3Qabq6iYQrN2QC-ZUXw/videos"> John Levine </a>, Búsqueda de Coste Uniforme)

### **---- Técnicas de Búsqueda Heurísticas (Búsqueda Informada) ----**
Los *heurísticos* son aquellos mecanismos que permiten, en un espacio de estados y empleando conocimiento del dominio del problema, dirigir la búsqueda hacia zonas prometedoras del espacio de búsqueda, sin necesidad de visitar tantos nodos como requeriría a priori una búsqueda a ciegas. 

Una clasificación de las técnicas de búsqueda basadas en mecanismos heurísticos podría considerarse la siguiente:

#### *Tipos de algoritmos heurísticos*: 
- Búsqueda Primero el Mejor (BF)
- A*
    - Algoritmos e-admisibles:
        - Ponderación Dinámica
        - Ae*
- Búsqueda con memoria limitada: 
    - IDA*
    - SMA*
- Algoritmos Voraces
- Algoritmos de Ramificación y Poda
- Algoritmos de mejora iterativa o búsqueda local: 
    - Escalada o Máximo Gradiente
    - Temple Simulado
    - Búsqueda Tabú

Los siguientes recursos desarrollan explicaciones sobre los diferentes algoritmos de búsqueda heurísticos:

- https://www.ics.uci.edu/~kkask/Fall-2016%20CS271/slides/03-InformedHeuristicSearch.pdf (Dr. Kalev Kask - University of California. Explicación muy recomendable y gráfica del temario perteneciente a la asignatura CompSci 271: Introduction to Artificial Intelligence, Fall 2016)
- https://www.javatpoint.com/ai-informed-search-algorithms (Algoritmos Primero-el-mejor y A*)
- https://cse.sc.edu/~mgv/csce580f11/gradPres/580f11SiminFahimIDAStar.pdf (Dr. Marco Voltorta. Presentación "Efficient Memory-Bounded Search Methods." Explicaciones de los algoritmos IDA* y SMA*).
- https://www.cs.upc.edu/~mabad/ADA/curso0708/GREEDY.pdf (Algoritmos Voraces, Facultad de Informática U.P.C).
- https://es.wikipedia.org/wiki/Algoritmo_hill_climbing (Algoritmos de Escalada o Máximo Gradiente)
- https://machinelearningmastery.com/simulated-annealing-from-scratch-in-python (Algoritmo de Temple Simulado).
- https://www.researchgate.net/profile/Darrall-Henderson/publication/225260290_The_Theory_and_Practice_of_Simulated_Annealing/links/0c960516543772adef000000/The-Theory-and-Practice-of-Simulated-Annealing.pdf (Darrall Henderson, Sheldon H. Jacobson, Alan W. Johnson, "Teoría y Práctica del Temple Simulado).
- https://sci2s.ugr.es/sites/default/files/files/Teaching/GraduatesCourses/Algoritmica/Tema04-BusquedaTabu-12-13.pdf (Algoritmos de Búsqueda Tabú).
- https://www.youtube.com/watch?v=8pTjoFiICg8 ((Prof. Pieter Abbeel. Lecture 3 Informed Search Universidad de Berkeley, Primavera 2014).
- https://www.youtube.com/watch?v=6TsL96NAZCo (<a href= "https://www.youtube.com/channel/UCUbp3Qabq6iYQrN2QC-ZUXw/videos"> John Levine </a>, Búsquedas A*).
