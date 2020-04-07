## Задача 2
Изкопирайте функцията `double_up` от първа задача (заедно с глобалната променлива използвана от нея). Дефинирайте друга функция `int double_up_static()` която връща степените на двойката, но използвайки _статична променлива_. Покажете, че двете функции работят еквивалентно в главната функция на програмата.

### Пример
```c
printf("%d\n", double_up() == double_up_static());  // 1
printf("%d\n", double_up() == double_up_static());  // 1
printf("%d\n", double_up() == double_up_static());  // 1

for(int i = 0; i < 9; i++) {
    double_up(); // no output expected
    double_up_static(); // no output expected aswell
}

printf("%d\n", double_up() == double_up_static());  // 1
```
