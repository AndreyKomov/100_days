*day 1 - 18 nov*
создал файл

*day 2 - 21 nov*
HTML/CSS basics     https://slides.com/sergeyshalyapin/html_css_basics#/
GIT basics          https://github.com/rolling-scopes-school/lectures/blob/master/lectures/git.md

*day 3 - 23 nov*

https://learn.javascript.ru/
intro              
basics 1 - 5 

let – это современный способ объявления.

var – это устаревший способ объявления.

const – похоже на let, но значение переменной не может изменяться.

**********

*day 1 - 27 nov*

http://learn.javascript.ru

Типы данных

*В JavaScript есть 7 основных типов.*

number для любых чисел: целочисленных или чисел с плавающей точкой.

string для строк. Строка может содержать один или больше символов, нет отдельного символьного типа.
boolean для true/false.
null для неизвестных значений – отдельный тип, имеющий одно значение null.
undefined для неприсвоенных значений – отдельный тип, имеющий одно значение undefined.
object для более сложных структур данных.
symbol для уникальных идентификаторов.
Оператор typeof позволяет нам увидеть, какой тип данных сохранён в переменной.

Имеет две формы: typeof x или typeof(x).
Возвращает строку с именем типа. Например, "string".
Для null возвращается "object" – это ошибка в языке, на самом деле это не объект.

*day 2 - nov 29*

pats 6 - 10

+tasks

*day 3 - nov 30*

part 11

while – Проверяет условие перед каждой итерацией.

do..while – Проверяет условие после каждой итерации.

for (;;) – Проверяет условие перед каждой итерацией, есть возможность задать дополнительные настройки.

Чтобы организовать бесконечный цикл, используют конструкцию while (true). При этом он, как и любой другой цикл, может быть прерван директивой break.

Если на данной итерации цикла делать больше ничего не надо, но полностью прекращать цикл не следует – используют директиву continue.

Обе этих директивы поддерживают метки, которые ставятся перед циклом. Метки – единственный способ для break/continue выйти за пределы текущего цикла, повлиять на выполнение внешнего.

Метки не позволяют прыгнуть в произвольное место кода, в JavaScript нет такой возможности.

**********

*day 1 14 dec*
function

function имя(параметры, через, запятую) {
  /* тело, код функции */
}

*********

*day 1 28 dec*

function expression

*Функции – это значения. Они могут быть присвоены, скопированы или объявлены в другом месте кода.
*Если функция объявлена как отдельная инструкция в основном потоке кода, то это Function Declaration.
*Если функция была создана как часть выражения, то считается, что эта функция объявлена при помощи Function Expression.
*Function Declaration обрабатываются перед выполнением блока кода. Они видны во всём блоке.
*Функции, объявленные при помощи Function Expression, создаются, только когда поток выполнения достигает их.

*day 2 29 dec*

arrow-functions-basics

let func = (arg1, arg2, ...argN) => expression

1. Без фигурных скобок: (...args) => expression – правая сторона выражение: функция выполняет его и возвращает результат.

2. С фигурными скобками: (...args) => { body } – скобки позволяют нам писать многострочные инструкции внутри функции, но при этом необходимо указывать директиву return, чтобы вернуть какое-либо значение.

**********

*day 1 - 23 jan*

Объекты

Объекты – это ассоциативные массивы (коробки с папками свойств различных) с рядом дополнительных возможностей

Они хранят свойства (пары ключ-значение), где:

Ключи свойств должны быть строками или символами (обычно строками).
Значения могут быть любого типа.
Чтобы получить доступ к свойству, мы можем использовать:

Запись через точку: obj.property.
Квадратные скобки obj["property"]. Квадратные скобки позволяют взять ключ из переменной, например, obj[varWithKey].
Дополнительные операторы:

Удаление свойства: delete obj.prop.
Проверка существования свойства: "key" in obj.
Перебор свойств объекта: цикл for for (let key in obj).
Объекты присваиваются и копируются по ссылке.

Чтобы сделать «настоящую копию» (клон):      Object.assign или _.cloneDeep(obj).


В JavaScript есть много других типов объектов:

*Array* для хранения упорядоченных коллекций данных,
*Date* для хранения информации о дате и времени,
*Error* для хранения информации об ошибке.
… и так далее.

*day 2 - 26 jan*

Methods of primitive.

Есть 6 примитивных типов: string, number, boolean, symbol, null и undefined.

Объявляется при помощи фигурных скобок {}, например: {name: "Рома", age: 30}. В JavaScript есть и другие виды объектов: например, функции тоже являются объектами.

Каждый примитив имеет свой собственный «объект-обёртку», которые называются: String, Number, Boolean и Symbol. Таким образом, они имеют разный набор методов.

К примеру, существует метод str.toUpperCase(), который возвращает строку в верхнем регистре.

Число имеет собственный набор методов. Например, toFixed(n) округляет число до n знаков после запятой.

Все примитивы, кроме null и undefined, предоставляют множество полезных методов.

Формально эти методы работают с помощью временных объектов, их вызов не требует много ресурсов.



