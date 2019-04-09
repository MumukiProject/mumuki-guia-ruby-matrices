Ahora que estamos cerca del final, queremos codificar una matriz de 5x5 donde cada elemento sea la multiplicación de su número de fila y columna. O sea...

```ruby
ム matriz[2][3]
> 6
ム matriz[4][4]
> 16
```

¿Existe alguna forma de *automatizar* esto, en lugar de tener que calcular manualmente cuál es la multiplicación de cada posición? ¡Sí, lo aprendimos recién! Pero vamos a necesitar más de un `for` :scream:.

Como en las matrices tenemos filas *y* columnas, necesitamos dos `for`: uno para recorrer todas las filas, y otro para trabajar con los elementos de *cada* fila. Hasta que no finaliza por completo el ciclo del segundo `for`, no continúa el ciclo del primero. Nuestro método se verá parecido a...

```ruby
def construir_matriz_de_multiplicacion_5x5
  matriz = []
  for fila in 0..4
    for columna in 0..4
       #Aquí va lo que queremos que ocurra en el elemento matriz[fila][columna]
    end
  end
  return matriz
end
```

Las variables `fila` y `columna` van a tomar un valor distinto, entre 0 y 4, cada vez que se ejecute el código dentro de los ciclos `for`. Al igual que para imprimir los números, podemos usar estas variables para trabajar con los elementos de la matriz.

Por ejemplo, la primera vez que se ejecute la cuarta línea, `fila` y `columna` valdrán 0; entonces, escribiendo `matriz[fila][columna]` podemos acceder al elemento en `matriz[0][0]`. La próxima iteración, `fila` seguirá valiendo 0 pero `columna` será igual a 1: entonces nos sirve para acceder a `matriz[0][1]`. ¡Y así para recorrer toda la matriz! :tada:

> Completá el código: ¿a qué debe ser igual `matriz[fila][columna]`? Recordá que queremos que cada posición de la matriz guarde la multiplicación de su número de `fila` por su número de `columna`. :satisfied: