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

## xo@0.0.2
Требуется написать xo с полем размерами **5x5** для двух игроков. 

### Примеры
```
    1   2   3   4   5
  +---+---+---+---+---+
a |   |   |   |   |   |
  +---+---+---+---+---+
b |   |   |   |   |   |
  +---+---+---+---+---+
c |   |   |   |   |   |
  +---+---+---+---+---+
d |   |   |   |   |   |
  +---+---+---+---+---+
e |   |   |   |   |   |
  +---+---+---+---+---+

1. mark cell a1 as X
2. mark cell a2 as X
3. mark cell a3 as X
4. mark cell a4 as X
5. mark cell a5 as X
6. mark cell b1 as X
7. mark cell b2 as X
8. mark cell b3 as X
9. mark cell b4 as X
10. mark cell b5 as X
11. mark cell c1 as X
12. mark cell c2 as X
13. mark cell c3 as X
14. mark cell c4 as X
15. mark cell c5 as X
16. mark cell d1 as X
17. mark cell d2 as X
18. mark cell d3 as X
19. mark cell d4 as X
20. mark cell e5 as X
21. mark cell e1 as X
22. mark cell e2 as X
23. mark cell e3 as X
24. mark cell e4 as X
25. mark cell e5 as X
26. quit

1

    1   2   3   4   5
  +---+---+---+---+---+
a | X |   |   |   |   |
  +---+---+---+---+---+
b |   |   |   |   |   |
  +---+---+---+---+---+
c |   |   |   |   |   |
  +---+---+---+---+---+
d |   |   |   |   |   |
  +---+---+---+---+---+
e |   |   |   |   |   |
  +---+---+---+---+---+

1. mark cell a2 as O
2. mark cell a3 as O
3. mark cell a4 as O
4. mark cell a5 as O
5. mark cell b1 as O
6. mark cell b2 as O
7. mark cell b3 as O
8. mark cell b4 as O
9. mark cell b5 as O
10. mark cell c1 as O
11. mark cell c2 as O
12. mark cell c3 as O
13. mark cell c4 as O
14. mark cell c5 as O
15. mark cell d1 as O
16. mark cell d2 as O
17. mark cell d3 as O
18. mark cell d4 as O
19. mark cell d5 as O
20. mark cell e1 as O
21. mark cell e2 as O
22. mark cell e3 as O
23. mark cell e4 as O
24. mark cell e5 as O
15. quit

...
```
