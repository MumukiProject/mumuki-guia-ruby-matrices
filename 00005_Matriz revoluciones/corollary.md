¡Increíble!

La variable de un ciclo `for` que aquí llamamos `fila` lleva el nombre de, simplemente, la letra `i`. Como también es común **anidar** ciclos `for` (es decir, tener uno dentro de otro), el segundo `for` suele usar como variable la letra `j`, por ser la letra siguiente a la `i` en el abecedario. :satisfied:

En este caso, nuestro método funciona *únicamente* para matrices que tengan 3 filas y 4 columnas; si le pasamos otra por parámetro, no funcionará o subirá menos notas de las que tiene que subir. Para evitar eso, la cantidad de filas y columnas también podría pasarse por parámetro u obtenerse en función de la matriz que se pasa, por ejemplo usando `size`.