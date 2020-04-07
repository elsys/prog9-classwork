## Задача 6
Дефинирайте функцията `void queen_move_positions(char letter, int pos)` която изпринтира на екрана всички възможни полета на които може да се премести шахматна царица поставена върху полето на позиция `<letter><pos>`. Входната позиция, както и очаквания изход, използват [шахматната нотация](https://bg.wikipedia.org/wiki/%D0%A8%D0%B0%D1%85%D0%BC%D0%B0%D1%82%D0%BD%D0%B0_%D0%BD%D0%BE%D1%82%D0%B0%D1%86%D0%B8%D1%8F).

![Chessboard notation](https://upload.wikimedia.org/wikipedia/commons/1/11/SCD_algebraic_notation.png)

За обработване на входа и принтиране направете две помощни функции:
- `from_vertical` която приема символи от _a_ до _h_ и връща съответстващото поле като число от _1_ до _8_
- `to_vertical` която приема цифра от 1 до 8 и връща символ от _a_ до _h_

Реда на принтиране на възможните позиции няма значение.

## Примери
```c
queen_move_positions('h', 9);
// expected output:
// g8 f8 e8 d8 c8 b8 a8 h7 h6 h5 h4 h3 h2 h1 g7 f6 e5 d4 c3 b2 a1
```

```c
queen_move_positions('g', 2);
// expected output:
// f2 e2 d2 c2 b2 a2 g3 g4 g5 g6 g7 g8 h2 g1 f3 e4 d5 c6 b7 a8 h3 h1 f1
```
