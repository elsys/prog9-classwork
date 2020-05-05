Напишеш функция pop, която получава масив от цели числа, връща последния елемент на масива, който е положителен и същевременно го заменя с -1

Ако масива няма положителни числа, върнете първия елемент на масива.

Пример:

```
int a[] = {100, 200, 300, 400, 500};
int a_size = sizeof(a)/sizeof(a[0]);

printf("%d\n", pop(a, a_size)); // 500
printf("%d\n", pop(a, a_size)); // 400
printf("%d\n", pop(a, a_size)); // 300
printf("%d\n", pop(a, a_size)); // 200
printf("%d\n", pop(a, a_size)); // 100
printf("%d\n", pop(a, a_size)); // -1
printf("%d\n", pop(a, a_size)); // -1
printf("%d\n", pop(a, a_size)); // -1

int b[] = {-100, 200, -300, 400, -500};
int b_size = sizeof(b)/sizeof(b[0]);

printf("%d\n", pop(b, b_size)); // 400
printf("%d\n", pop(b, b_size)); // 200
printf("%d\n", pop(b, b_size)); // -100
printf("%d\n", a[4]); // -500
printf("%d\n", a[2]); // -300
```
