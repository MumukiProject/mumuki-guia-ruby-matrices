La siguiente es una matriz con los horarios de apertura y cierre de un local :clock2:. Cada columna representa un día de la semana, de lunes a domingo  :date:; la primera fila representa el horario de apertura, y la segunda el horario de cierre. Como tiene dos filas y siete columnas, decimos que el tamaño de la matriz es `2x7`.

```ruby
horarios_por_dia = [
  ["08:00", "08:00", "09:00", "09:00", "11:00", "10:00", "Cerrado"],
  ["18:00", "18:00", "19:00", "19:00", "21:00", "14:00", "Cerrado"]
]
```

Para acceder a un elemento en particular, primero escribimos entre corchetes el número de fila y luego el de columna. ¡Siempre empezando desde cero!

Por ejemplo, para ver el horario de apertura del sábado, hacemos:

```ruby
ム horarios_por_dia[0][5]
> "10:00"
```

O para el horario de cierre del viernes, escribimos:

```ruby
ム horarios_por_dia[1][4]
> "21:00"
```

> Probá en la consola la matriz `tabla_periodica`, de 3x5, que contiene algunos elementos metales, no metales y gases nobles tal cual aparecen en la tabla periódica. ¿En qué posición está el `Neón`? ¿Y el `Fósforo`? :microscope: