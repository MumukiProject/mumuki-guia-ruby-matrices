En el ejercicio anterior escribiste una nueva matriz, ¡y te salió muy bien! :smile: Una vez que la matriz ya está definida, sus contenidos se pueden modificar de forma simple. Por ejemplo, si Lara (primera fila) volvió a rendir biología (segunda columna) y se sacó 9, es cuestión de identificar la fila y columna correspondiente y escribir el nuevo elemento:

```ruby
notas_por_estudiante[0][1] = 9
```

O si Micaela (en la tercera fila) obtuvo una nota perfecta en educación física (la cuarta columna), escribimos:

```ruby
notas_por_estudiante[2][3] = 10
```

¡Recordá que se empieza a contar desde cero! Y hablando de recordar... teníamos guardada en una matriz dónde se sientan  12 estudiantes de otro curso, ¡pero nos olvidamos la posición de casi todo el mundo! :sweat_smile:

En la pestaña `Biblioteca` podés ver qué posiciones recordamos. También sabemos que:

* `bruno` se sienta adelante de todo para ver bien, pero no tiene detrás a `paula`.

* `diana` se sienta en la columna del medio, pero no se sienta al lado de `paula` ni de `perla`.

* `maría` se sienta delante de `lucas` y detrás de `ailén`.

* `lucas` y `fabio` son mejores amigos, por lo que se sientan uno al lado del otro.

* `tomás` siempre se queja de que la cabeza de `mateo` no lo deja ver el pizarrón.

* `simón` quería sentarse adelante de todo, pero `carla` se quedó en ese lugar.

> Modificá los elementos necesarios en la matriz `aula` para almacenar dónde se sienta cada estudiante. :raising_hand: :bow: