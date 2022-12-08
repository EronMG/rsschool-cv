# **Zaytsev Nikita**

[!me](/Desktop/zalov/img/nikita.jpg)

## **Contacts**

- **Location:**Minsk,Belarus
- **Phone:**+375-29-835-36-19
- **Email:**eronmcgonagal@gmail.com
- **Discord:**EronMcGonagal(Никита)#1565

## **About me**

I have good interpersonal skills, am an excellent team worker and very willing to learn and develop new skills.
I am reliable and dependable and often seek new responsibilities within a wide range of employment areas.

## Skills

- HHTML
- CSS
- JS

## Code exmaple

{

class Vector { //шаблон кода для создания объектов, который устанавливает в них начальные значения
\_x;
\_y;
constructor(x, y) { //инициализировать объект
this.\_x = x;
this.\_y = y;

}

    get x() { // для чтения
        return this._x;
    }

    get y() {
        return this._y;
    }

    set x(value) { //для записи
        this._x = value;
    }

    set y(value) {
        this._y = value;
    }

    get length() {
        return Math.sqrt(this._x ** 2 + this._y ** 2); // функция скалярное произведение
    }

    plus(vector) {
        return new Vector(this._x + vector._x, this._y + vector._y); // функция сложения
    }

    minus(vector) {
        return new Vector(this.x - vector.x, this.x - vector.x); // функция вычитания
    }

    multiply(num) {
        return new Vector(this.x * num, this.y * num);
    }

    toString() {
        return `Vector(${this.x}, ${this.y})`;
    }

}

const v1 = new Vector(1, 2);
const v2 = new Vector(2, 3);
const v3 = new Vector(3, 4);

const arr = [v1, v2, v3];

// вывести вектора с заданным модулем
const length = 5;
const filtered = arr.filter(vector => vector.length === length);
console.log(filtered.map(vector => vector.toString()));

// определить вектор с наибольшей/наименьшей суммой элементов
const min = arr.reduce((min, vector) => vector.x + vector.y < min ? vector.x + vector.y : min, Infinity);
const max = arr.reduce((max, vector) => vector.x + vector.y > max ? vector.x + vector.y : max, -Infinity);
console.log(min, max);
}

## Experience

## Education

- **University:**MITSO(Ingeneer-Programmist)
- **Courses:**FreeCodeCamp,HTML Academy.

## English

B1
