# Arrays

1. Дан случайный массив чисел (создайте самостоятельно).
С помощью метода `.filter()` отфильтруйте массив так,
чтобы в новый массив вошли только четные двухзначные числа из исходного.

2. Пользователь вводит 10 случайных значений. Каждое
значение необходимо записать в массив. С помощью
метода `.every()` проверить были ли все введенные
пользователем данные – числами.

3. Дан массив объектов
```js
const arr = [
  {a: 2, b: 1},
  {a: 5, b: 12},
  {a: 95, b: 7}
]
```
Используя ТОЛЬКО методы массивов (циклы запрещены):
- Вывести в консоль `'its valid'`, если во всех объектах поле `a > b`, вывести `'its invalid'` если хотя бы в одном объекте `a<=b`
- На основе массива arr, создать массив объектов у которых поле b возведено в квадрат
пример:
```js
const arr2 = [
  {a: 2, b: 1},
  {a: 5, b: 144},
  {a: 95, b: 49}
];
```