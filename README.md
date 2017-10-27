# xo

xo —  логическая игра между двумя противниками на квадратном поле 3 на 3 клетки. Один из игроков играет «крестиками», второй — «ноликами».

### Правила
Игроки по очереди ставят на свободные клетки поля 3х3 знаки (один всегда крестики, другой всегда нолики). Первый, выстроивший в ряд 3 своих фигуры по вертикали, горизонтали или диагонали, выигрывает. Первый ход делает игрок, ставящий крестики.

## xo@0.0.1
Требуется написать xo для двух игроков.

### Примеры
```
    1   2   3
  +---+---+---+
a |   |   |   |
  +---+---+---+
b |   |   |   |
  +---+---+---+
c |   |   |   |
  +---+---+---+

1. mark cell a1 as X
2. mark cell a2 as X
3. mark cell a3 as X
4. mark cell b1 as X
5. mark cell b2 as X
6. mark cell b3 as X
7. mark cell c1 as X
8. mark cell c2 as X
9. mark cell c3 as X
10. quit

1

    1   2   3
  +---+---+---+
a | X |   |   |
  +---+---+---+
b |   |   |   |
  +---+---+---+
c |   |   |   |
  +---+---+---+

1. mark cell a2 as O
2. mark cell a3 as O
3. mark cell b1 as O
4. mark cell b2 as O
5. mark cell b3 as O
6. mark cell c1 as O
7. mark cell c2 as O
8. mark cell c3 as O
9. quit

4

    1   2   3
  +---+---+---+
a | X |   |   |
  +---+---+---+
b |   | O |   |
  +---+---+---+
c |   |   |   |
  +---+---+---+

1. mark cell a2 as X
2. mark cell a3 as X
3. mark cell b1 as X
4. mark cell b3 as X
5. mark cell c1 as X
6. mark cell c2 as X
7. mark cell c3 as X
8. quit

7

    1   2   3
  +---+---+---+
a | X |   |   |
  +---+---+---+
b |   | O |   |
  +---+---+---+
c |   |   | X |
  +---+---+---+

1. mark cell a2 as O
2. mark cell a3 as O
3. mark cell b1 as O
4. mark cell b3 as O
5. mark cell c1 as O
6. mark cell c2 as O
7. quit

5

    1   2   3
  +---+---+---+
a | X |   |   |
  +---+---+---+
b |   | O |   |
  +---+---+---+
c | O |   | X |
  +---+---+---+

1. mark cell a2 as X
2. mark cell a3 as X
3. mark cell b1 as X
4. mark cell b3 as X
5. mark cell c2 as X
6. quit

2

    1   2   3
  +---+---+---+
a | X |   | X |
  +---+---+---+
b |   | O |   |
  +---+---+---+
c | O |   | X |
  +---+---+---+

1. mark cell a2 as O
2. mark cell b1 as O
3. mark cell b3 as O
4. mark cell c2 as O
5. quit

1

    1   2   3
  +---+---+---+
a | X | O | X |
  +---+---+---+
b |   | O |   |
  +---+---+---+
c | O |   | X |
  +---+---+---+

1. mark cell b1 as X
2. mark cell b3 as X
3. mark cell c2 as X
4. quit

2

    1   2   3
  +---+---+---+
a | X | O | X |
  +---+---+---+
b |   | O | X |
  +---+---+---+
c | O |   | X |
  +---+---+---+

player X wonn.
```
