# notebooks-ejercicios
Proyectos desarrollados sobre notebooks Jupyter 

Cada notebook contiene un proyecto. Estos proyectos permiten ir descubriendo distintos elementos del lenguaje Python mediante su aplicación en la resolución de un problema concreto.

Los proyectos están parcialmente resueltos, incluyen:
- La organización del proyecto en funciones. Para cada función se definen los parámetros y se inlcuye un comentario explicativo de su funcionamiento.
- Una celda de código con el test para cada función
- La decisión de las estructuras usadas para representar los datos del proyecto

No se inlcuye:
- La implementación de las funciones. El cuerpo de las funciones contiene solo una instrucción <code>pass</code> que deberá ser sustituida por una implementación que cubra lo que se indica en el comentario explicativo. 

Los proyectos disponibles (ordenados de menor a mayor dificultad) son:

1. *Audiencias (solucionado)*: análisis de audiencias televisivas
2. *Sevici*: identificación de estaciones en una red de alquiler de bicicletass 
3. *Bolsa*: análisis de datos bursátiles
4. *FutElo*: sistema de puntuación Elo sobre resultados de fútbol
5. *ATP*: comparación y evolución de rankings con la métrica de Kendall
6. *Recomendacion*: sistema de recomendación de películas
7. *Whatsapp*: Cálculo de indicadores a partir de logs de conversaciones de whatsapp
8. *Montecarlo*: aplicaciones del método de Montecarlo a la estimación de $\pi$ y el nivel de fuerza de una jugada de póker

Para poder ejecutar los notebooks es necesario instalar Jupyter (http://jupyter.org/). Lo más recomendable es hacerlo a través de la distribución de Anaconda (https://conda.io/docs/user-guide/install/download.html) que incluye el intérprete de Python, y la mayoría de las librerías que usaremos a lo largo del curso.

Empezar a trabajar con un notebook es muy fácil (http://jupyter.readthedocs.io/en/latest/running.html) basta con ejecutar la siguiente instrucción desde la consola _Anaconda prompt_:

<code>jupyter \<nombre_notebook\></code>
