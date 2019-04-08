Para nuestro trabajo final con las matrices, necesitamos la asistencia de alguien más: el ciclo `for`. Todo el código que esté dentro de las palabras `for` y `end` se va a ejecutar varias veces, y es útil para hacer acciones repetitivas. Por ejemplo, en el siguiente código...

```ruby
def imprimir_numeros_del_1_al_100
  for numero in 1..100
   imprimir(numero)
  end
end
```

...la línea `imprimir(numero)` se va a ejecutar muchas veces (cien, de hecho, porque escribimos `1..100`), y en cada ejecución se imprimirá `numero` en la consola.

¿Pero cuánto vale `numero`? ¡Depende! :scream: La primera vez que se ejecute el código vale 1; la siguiente, 2; y así hasta 100.

Sin utilizar `for`, el método anterior se vería de la siguiente forma:

```ruby
def imprimir_numeros_del_1_al_100
   imprimir(1)
   imprimir(2)
   imprimir(3)
   #...
   imprimir(98)
   imprimir(99)
   imprimir(100)
  end
end
```

Aquí lo acortamos para poder mostrarte, ¡pero es larguísimo! :dizzy_face: Por eso `for` es útil: permite simplificar operaciones... y hasta realizar algunas en las que **no sabemos exactamente** cuántas veces hay que ejecutar algo. :smirk:

> Probá en la consola el método `imprimir_numeros_del_1_al`, que recibe por parámetro cuántos números va a imprimir. ¡Podés ver su código en la `Biblioteca`!

> ```ruby
ム imprimir_numeros_del_1_al 3
1
2
3
=> 1..3
```