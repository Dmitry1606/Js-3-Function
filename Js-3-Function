// Задание 1
// Перепишите код, заменив цикл for на while, без изменения поведения цикла.

// for (let i = 0; i < 3; i++) {
// alert( `number ${i}!` );
// }

let i = 0;

while(i < 3) {
    alert( `number ${i}!` );
    i++
}



// Задание 2
// Перепишите код с использованием тернарного оператора
// let male = true;
// let gender;
// if (male) {
// gender = 'man';
// } else{
// gender = 'woman'
// }

let male = true;
let gender;

let result = gender == 'man' ? 'man' : 'woman';
alert(result);



// Задание 3
// Задать массив логических значений (true/false). Каждое значение обозначает мужчина (true) или женщина (false).
// Из этого массива сформировать массив объектов такой же длины, как и заданный массив.
// У каждого объекта должно быть одно поле, gender, которое равно man, если значение в заданном массиве - true, и woman, если значение в заданном массиве - false.
// Т.е. из
// [true, false]
// должно получиться
// [{ gender: 'man' }, { gender: 'woman' }]

let massiv = [true, false]

let massiv2 = []

for(let i = 0; i < massiv.length; i++) {

let gender = massiv[i] == true ? 'man' : 'woman';

massiv2.push({ gender: gender })
}
console.log(massiv2)



// Задание 4
// Создайте функцию findPositiveNumbers()
// 1) Внутри функции должен определяться массив, например let arr = [5, 4, 3, -3, -10, -1, 8, -20, 0] .
// Функция должна вывести в консоль все положительные числа по одному.
// 2) Функция должна не выводить числа в консоль, а составить из них новый массив. В самом конце тела функции - вывести новый массив в консоль.
// 3) Функция должна не выводить массив в консоль, а вернуть новый массив из положительных элементов arr.
// 4) Изначальный массив arr должен не описываться внутри функции, а поступать в нее как параметр.

let arr = [5, 4, 3, -3, -10, -1, 8, -20, 0];
function findPositiveNumbers(arr) {
    let newArr = []
    for(let i = 0; i < arr.length; i++)
    if (arr[i] > 0) {
        newArr.push(arr[i])
    }

return newArr;
}
let something =  findPositiveNumbers(arr)
console.log(something);



// Задание 5
// Напишите функцию, которая принимает два параметра: значение и количество элементов. Функция создает новый массив и заполняет его этим значением в указанном количестве.
// Например: из переданных значений ('a', 3) получаем массив ['a', 'a', 'a']

function createArray(count,content) {
    let arr = []
    for(let i = 0; i < count; i++) {
        arr.push(content)
    }
return arr;
}
let anything = createArray(7,'coffee')
console.log(anything);



// Задание 6
// Определите массив, например let arr = [5, 4, 3, 8, 0].
// Создайте функцию filterFor(arr, a). Функция должна вернуть новый массив из элементов arr, но в нем должны содержаться элементы, которые больше или равны (>=) значению переменной a.
// Например, запуск функции filterFor(arr, 5) дает результат [5,8]
// а запуск функции filterFor(arr, 10) дает результат []
// а запуск функции filterFor(arr, 3.11) дает результат [4,5,8]

let array = [5, 4, 3, 8, 0];

let a = 5

function  filterFor(inArray, a) {
    let newArr = []
    for(let i = 0; i < inArray.length; i++) {
    if (inArray[i] >= a) {
        newArr.push(inArray[i])
        }

    }
    return newArr;
}
let tea = filterFor(array,a)
console.log(tea)



console.clear()
// Задание 7
// Написать функцию вывода в консоль случайного цвета. Это будет строка вида "rgb(10,55,250)"
// Здесь у вас будет две функции: одна ваша - getRandomRGB, а вторая - функция получения случайного числа в диапазоне min - max. Вот эта функция (просто скопируйте, она уже готова):
// function getRandomInteger(min, max) {
// return Math.floor(Math.random() * (max - min)) + min;
// }
// Подсказка: 
// Каждый цвет - 3 числа, каждое число лежит в диапазоне от 0 до 255. 
// Одна функция может вызывать другую функцию


function getRandomInteger(min, max) {
    return Math.floor(Math.random() * (max - min)) + min;
}
function  getRandomRGB() {

console.log(`rgb ${getRandomInteger(0, 255)}, ${getRandomInteger(0, 255)}, ${getRandomInteger(0, 255)}`)
}
getRandomRGB()



//Задание 8
//Написать функцию pow(x, n), которая возвращает x в степени n. Иначе говоря, умножает x на себя n раз и возвращает //результат (!!! решить без оператора **)

function pow(x, n){
    let result = x
    for(let i = 0; i < n; i++) {
        result = result * x 
    }
    return result
}
let pew = pow(2,3)
console.log(pew)



//Задание 9
//Написать функцию isInteger(x), которая определяет, является ли число целым, и возвращает true либо false.

function isInteger(x) {
    let result = x % 1 === 0 ? true : false;

    return result ;
}
let number  = isInteger(34) 
let number1  = isInteger(34.8) 
console.log(number,number1)



// Задание 10
// Написать функцию, которая принимает целое число n.   
// Внутри функции запустить цикл от 1 до n с шагом 0,5. На каждой итерации цикла выводить в консоль текущее число (i) и информацию о том, целое ли оно.
// Пример, при запуске функции с параметром 3:

// "1 integer"
// "1.5 decimal"
// "2 integer"
// "2.5 decimal"

function integer(n) {
    for(let i = 1; i < n; i = i + 0.5) {
        let result = i % 1 === 0 ? 'integer' : 'decimal';
        console.log(`${i} ${result}`)
    }
}
integer(5)
