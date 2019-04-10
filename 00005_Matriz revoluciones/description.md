Ahora que estamos cerca del final, queremos subirle un punto a nuestros estudiantes de un ejercicio anterior, Lara, Miguel y Micaela, porque se han portado muy bien durante el año. :smirk:

Como son tres estudiantes y cuatro materias, son doce las notas que tenemos que cambiar. Pero... ¡¿a mano?! :dizzy_face: ¿No existe alguna forma de *automatizar* esto, en lugar de tener que cambiar manualmente la nota de cada materia? ¡Sí, lo aprendimos recién! Pero vamos a necesitar más de un `for` :scream:.

Como en las matrices tenemos filas *y* columnas, necesitamos dos `for`: uno para recorrer todas las filas, y otro para trabajar con los elementos de *cada* fila. Hasta que no finaliza por completo el ciclo del segundo `for`, no continúa el ciclo del primero. Nuestro método se verá parecido a...

```ruby
def subir_notas!(notas)
  for fila in 0..2
    for columna in 0..3
       #Aquí va lo que queremos que ocurra en el elemento notas[fila][columna]
    end
  end
end
```

Las variables `fila` y `columna` van a tomar un valor distinto (empezando en 0, hasta 2 y hasta 3, respectivamente), cada vez que se ejecute el código dentro de los ciclos `for`. Al igual que para mostrar los números, podemos usar estas variables para trabajar con los elementos de la matriz.

Por ejemplo, la primera vez que se ejecute la cuarta línea, `fila` y `columna` valdrán 0; entonces, escribiendo `notas[fila][columna]` podemos acceder al elemento en `notas[0][0]`. La próxima iteración, `fila` seguirá valiendo 0 pero `columna` será igual a 1: entonces nos sirve para acceder a `notas[0][1]`. ¡Y así para recorrer toda la matriz! :tada:

> Completá el código: ¿a qué debe ser igual `notas[fila][columna]`? Recordá que queremos subirle un punto a todas las notas de la matriz. :satisfied: