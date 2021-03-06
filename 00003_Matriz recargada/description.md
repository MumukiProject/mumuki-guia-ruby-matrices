En el ejercicio anterior escribiste una nueva matriz, ¡y te salió muy bien! :smile: Una vez que la matriz ya está definida, sus contenidos se pueden modificar de forma simple. Por ejemplo, si Lara (primera fila) volvió a rendir biología (segunda columna) y se sacó 9, es cuestión de identificar la fila y columna correspondiente y escribir el nuevo elemento:

```ruby
notas_por_estudiante[0][1] = 9
```

O si Micaela (en la tercera fila) obtuvo una nota perfecta en educación física (la cuarta columna), escribimos:

```ruby
notas_por_estudiante[2][3] = 10
```

¡Recordá que se empieza a contar desde cero! Y hablando de recordar... teníamos guardada en una matriz dónde se sientan  12 estudiantes de otro curso, ¡pero nos olvidamos la posición de casi todo el mundo! :sweat_smile:

En la `Solución` podés ver qué posiciones recordamos. También sabemos que:

* `Bruno` se sienta adelante de todo para ver bien, pero no tiene detrás a `Paula`.

* `Diana` se sienta en la columna del medio, pero no se sienta al lado de `Paula` ni de `Perla`.

* `María` se sienta delante de `Lucas` y detrás de `Ailén`.

* `Lucas` y `Fabio` son mejores amigos, por lo que se sientan uno al lado del otro.

* `Tomás` siempre se queja de que la cabeza de `Mateo` no lo deja ver el pizarrón.

* `Simón` quería sentarse adelante de todo, pero `Carla` se quedó en ese lugar.

> Modificá los elementos necesarios en la matriz `aula` para almacenar dónde se sienta cada estudiante respetando mayúsculas y tildes. :raising_hand: :bow: