# notebooks-ejercicios
Proyectos desarrollados sobre notebooks Jupyter

### Referencia
Se puede encontrar una explicación más completa de este material docente en el artículo **Introducción a la Programación con Python, Computación Interactiva y Aprendizaje Significativo**  ([PDF](http://www.aenui.net/ojs/index.php?journal=actas_jenui&page=article&op=view&path%5B%5D=430&path%5B%5D=632)), publicado en las _XXIV Jornadas sobre la Enseñanza Universitaria de la Informática_ ([JENUI18](http://jenui2018.uoc.edu/)). Para citar este trabajo:

```
@article{troyano2018introduccion,
  title={Introducción a la Programación con Python, Computación Interactiva y Aprendizaje Significativo},
  author={Troyano, José A. and Cruz, Fermín and González, Mariano and Vallejo, Carlos G. and Toro, Miguel},
  journal={Actas de XXIV Jornadas sobre la Enseñanza Universitaria de la Informática - JENUI'18},
  volume={3},
  pages={223--230},
  year={2018}
}
```

### Contenido

Cada notebook contiene un proyecto. Estos proyectos permiten ir descubriendo distintos elementos del lenguaje Python mediante su aplicación en la resolución de un problema concreto.  Se utilizará este material en las clases de teoría.

Los proyectos están parcialmente resueltos, incluyen:
- La organización del proyecto en funciones. Para cada función se definen los parámetros y se incluye un comentario explicativo de su funcionamiento.
- Una celda de código con el test para cada función
- La decisión de las estructuras usadas para representar los datos del proyecto

No se incluye:
- La implementación de las funciones. El cuerpo de las funciones contiene solo una instrucción <code>pass</code> que deberá ser sustituida por una implementación que cubra lo que se indica en el comentario explicativo. 

Los proyectos disponibles son:

1. **Audiencias (solucionado)**: análisis de audiencias televisivas
2. **Sevici**: identificación de estaciones en una red de alquiler de bicicletas
3. **GPS**: 
3. **Bolsa**: análisis de datos bursátiles
4. **FutElo**: sistema de puntuación Elo sobre resultados de fútbol
5. **Whatsapp**: cálculo de indicadores a partir de logs de conversaciones de whatsapp
6. **ATP**: comparación y evolución de rankings con la métrica de Kendall
7. **Recomendacion**: sistema de recomendación de películas
9. **Montecarlo**: aplicaciones del método de Montecarlo a la estimación de _pi_ y el nivel de fuerza de una jugada de póker

Para poder ejecutar los notebooks es necesario instalar Jupyter (http://jupyter.org/). Lo más recomendable es hacerlo a través de la distribución de Anaconda (https://conda.io/docs/user-guide/install/download.html) que incluye el intérprete de Python, y la mayoría de las librerías que usaremos a lo largo del curso.

Empezar a trabajar con un notebook es muy fácil (http://jupyter.readthedocs.io/en/latest/running.html) basta con ejecutar la siguiente instrucción desde la consola _Anaconda prompt_:

<code>jupyter \<nombre_notebook\></code>
