##### Задача 1
реализовать функцию ```sum```, которая будет работать таким образом:
```javascript
 sum(a)(b) === a + b;
 ```

##### Задача 2
```javascript
var a = 5;
function a() { }

alert(a);
```
Что выведет алерт? Почему? Объяснить полученный результат.

##### Задача 3
```javascript
var value = 0;

function f() {
  if (1) {
    value = true;
  } else {
    var value = false;
  }
  console.log(value); 
}

f();
console.log(value)
```
Что будет, если из строки ``` var value = false``` убрать ```var```

##### Задача 4
Реализовать функцию ```getCounter```, чтобы она работала следюущим образом: 
```javascript
function getCounter() {
  // тут твой код
}
 
const myCounter = getCounter();
 
console.log(myCounter()) //1
console.log(myCounter()) //2
console.log(myCounter()) //3
console.log(myCounter()) //4
```

##### Задача 5

Реализовать метод ```fibonacci``` (рекурсивно и последовательно)

```javascript
console.log(fibonacci(10)) // 55
```

##### Задача 6
```javascript
var a = 5;
(function () {
 console.log(a);
 var a = 9;
})();
console.log(a);
```
Что выведется в консоль, почему?

```javascript
var a = 5;
(function () {
 console.log(a);
 a = 9;
})();
console.log(a);
```
 
 А в этом случае?
 
 **К прочтению:**
* *Учебник Флэнегана параграф 3.10*
* [learn.javascript](https://learn.javascript.ru/functions-closures)

