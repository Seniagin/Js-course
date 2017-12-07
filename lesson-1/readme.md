### Домашнее задание 


* #####Задача 1
В поезде в каждом вагоне 8 мест. Цена на места отличается. Билеты можно покупать только на последовательные места.
Нам приходит информация, что N(случайное число) пассажиров купили билеты. Написать алгоритм, по которому мы можем посчитать, 
сколько денег мы получили за билеты. Подсказка (надо циклически ходить по массиву, поможет оператор % и длинна массива)
  ```javascript
     const passangersCount = Math.floor(Math.random()*1000 + 8);
     const ticketsCost = [1, 12, 18, 4, 5, 6, 8, 12];
     
   //tickets summ?
   
   ```
* #####Задача 2
 ```javascript
 // for..in + опеределение типа
 // Есть объект:
  const obj = {a:1, b: 2, d:[], c:{}, e: null, f: undefined, g: NaN, h: function() {}};
 //Написать функцию:
 
 function filterObject (obj, typename){
   // возвращает объект с полями только этого типа
 }

filterObject(obj, 'number') // {a:1, b:2}
filterObject(obj, 'array') // {d:[]}
filterObject(obj, 'null') // {e:null}
filterObject(obj, 'undefined') //{f: undefined}
filterObject(obj, 'nan') // {g: NaN} etc...
filterObject(obj, 'function')
 ```
* #####Задача 3
[Простые числа](https://ru.wikipedia.org/wiki/%D0%9F%D1%80%D0%BE%D1%81%D1%82%D0%BE%D0%B5_%D1%87%D0%B8%D1%81%D0%BB%D0%BE)
 ```javascript
   // вывести в консоль первые 100, 1000, 2000 простых чисел ( только не скопировать, а сгенерировать)
   getPrimeNumbers(numbersCount) //[1,3,5,7,11,13...]
 ```
Статьи к прочтению:

[О движке JS](https://habrahabr.ru/company/ruvds/blog/337042/)

[Учебник Флэнегана](https://drive.google.com/open?id=0B9xQXL9346zFcVNLcnp5MVVVTFk)
 Главы 2, 3, 4 (Если хватит сил и будет интересно - то 5);
 
[Операторы в js](https://javascript.ru/manual/operator) Пожмякать на ссылки и почитать
 
[Приоритет операторов](
https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Operator_Precedence
)

Также прочитать про двоичную систему исчисления и байтовое представление чисел (необязательно на это занятие, но крайне пригодится в будущем)

 
 