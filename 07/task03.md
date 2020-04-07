## Задача 3
Дефинирайте функцията `is_perfect_square` която приема като аргумент едно цяло число и _връща_ 1 ако това число е точен квадрат на някое друго число или 0 ако не е. Подберете подходящи типове за параметъра и резултата на функцията.

Демонстрирайте коректността на функцията в главната функция на програмата със следните примери.

## Примери
```c
if(is_perfect_square(4)) {
    printf("4 is a perfect square number!");  // should go in here
    printf("2 * 2 = 4");
} else {
    printf("4 is not a square number!");  // should not get printed
}
```

```c
is_perfect_square(0);        // expected 1
is_perfect_square(-5);       // 0
is_perfect_square(1);        // 1
is_perfect_square(2);        // 0
is_perfect_square(9);        // 1
is_perfect_square(1048576);  // 1
```
Примерът служи само за илюстрация, за да изпринтирате на екрана трябва да използвате функцията `printf`.
