# RECOMENDACIÓN DE PELÍCULAS

## Descripción:
En este proyecto se busca desarrollar un sistema de recomendación de películas basado en contenido, es decir, basado en la similitud entre las características de dos películas diferentes. Si a un usuario le gusta una pelicula X, es muy probable que le guste la pelicula Y, considerando que X y Y son películas similares.

Para realizar el proyecto fue necesario hacer uso de técnicas de limpieza y análisis de datos con el fin de preparar la data de manera numérica para su análisis posterior. Se hizo uso de rake, una librería que ofrece un algoritmo para la extracción de palabras clave de un texto o frases. Se elaboran vectores numéricos codificando características de las películas y se usaron herramientas matemáticas como la similitud de coseno para comparar las películas entre sí.

## ¿Cómo correr el proyecto?

- Deben instalarse las librerías del archivo requirements.txt. En el ambiente de python del proyecto se encuentran instaladas las librerías. 
- Para usar la librería rake se debe descargar un archivo adicional. Si no se tiene, se produce un error en la ejecución el cual explica el archivo que debe ser descargado con nltk.download().

- Una vez instalado, se puede usar el cuaderno 03 para obtener recomendaciones de una película.
- En el cuaderno 01 y 02 se documenta el procedimiento de procesado de data y extracción de características.

## Ejemplo

Para un usuario que vio la película 'Finding Nemo', el motor de recomendaciones arroja las siguientes 10 películas:

1. Monsters, Inc.
2. Who Framed Roger Rabbit
3. WALL·E
4. Wreck-It Ralph
5. Shrek
6. Moana
7. Ratatouille
8. Toy Story 2
9. Toy Story 3
10. Toy Story 4