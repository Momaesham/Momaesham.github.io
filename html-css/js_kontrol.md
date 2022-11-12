# Контрольная работа

> Запрещено искать ответы и решение в интернете.
> 
> Можно пользоваться своим предыдущим кодом.
## Вопросы

> Отвечаете на вопросы прямо в JS. Комментируете ответы и идёте дальше.

1. В чём разница let и const? 
2. Что такое цикл? Какие циклы вы знаете в JS, и как они работают?
3. Что такое function?
4. Что такое объект? Напишите пример.
5. Что такое массив? Напишите пример.
6. Что такое DOM-дерево?
7. Что такое браузерное событие?

## Задачи
1.	Дан массив arr = [-3, 6, 0, -15, 46, 0, 47, 9, -3, -8].
Найти самый большой элемент массива и его индекс. Вывести результат в консоль.

2.	Дан массив arr = [-3, 6, 0, -15, 46, 0, 47, 9, -3, -8].
Удалить из массива все отрицательные числа.

3.	Напишите функцию, которая будет принимать 2 значения: массив и число. Если число меньше длины массива, то удалить лишние элементы массива. Если число больше длины массива, то добавить нужное количество «0». Если значения равны – просто вывести массив.

4.	- Создайте объект User c полями firstName, lastName, year(год рождения)
    - Реализуйте метод, который возвращает полное имя пользователя
    - Реализуйте метод, который возвращает полную информацию о пользователе
    - Создайте массив из 10 пользователей
    - Добавьте возможность вывода пользователей старше определенного возраста n, упорядоченных в алфавитном порядке в обратном направлении


5.	Дан html, раскрасьте все div в цвета соответствующие содержимому div.
 ```html
    <div>silver</div>
    <div>gray</div>
    <div>white</div>
    <div>maroon</div>
    <div>red</div>
    <div>purple</div>
    <div>fuchsia</div>
    <div>green</div>
    <div>lime</div>
    <div>olive</div>
    <div>yellow</div>
    <div>navy</div>
    <div>blue</div>
    <div>teal</div>
    <div>aqua</div>
    <div>antiquewhite</div>
    <div>aquamarine</div>
    <div>azure</div>
    <div>beige</div>
    <div>bisque</div>
    <div>blanchedalmond</div>
    <div>blueviolet</div>
    <div>brown</div>
    <div>burlywood</div>
    <div>cadetblue</div>
    <div>chartreuse</div>
    <div>chocolate</div>
    <div>coral</div>
    <div>cornflowerblue</div>
    <div>cornsilk</div>
    <div>crimson</div>
    <div>darkblue</div>
    <div>darkcyan</div>
    <div>darkgoldenrod</div>
    <div>darkgray</div>
    <div>darkgreen</div>
    <div>darkgrey</div>
    <div>darkkhaki</div>
    <div>darkmagenta</div>
    <div>darkolivegreen</div>
    <div>darkorange</div>
    <div>darkorchid</div>
    <div>darkred</div>
    <div>darksalmon</div>
    <div>darkseagreen</div>
    <div>darkslateblue</div>
    <div>darkslategray</div>
    <div>darkslategrey</div>
    <div>darkturquoise</div>
    <div>darkviolet</div>
    <div>deeppink</div>
    <div>deepskyblue</div>
    <div>dimgray</div>
    <div>dimgrey</div>
    <div>dodgerblue</div>
    <div>firebrick</div>
    <div>floralwhite</div>
    <div>forestgreen</div>
    <div>gainsboro</div>
    <div>ghostwhite</div>
    <div>gold</div>
    <div>goldenrod</div>
    <div>greenyellow</div>
    <div>grey</div>
    <div>honeydew</div>
    <div>hotpink</div>
    <div>indianred</div>
    <div>indigo</div>
    <div>ivory</div>
    <div>khaki</div>
    <div>lavender</div>
    <div>lavenderblush</div>
    <div>lawngreen</div>
    <div>lemonchiffon</div>
    <div>lightblue</div>
    <div>lightcoral</div>
    <div>lightcyan</div>
    <div>lightgoldenrodyellow</div>
    <div>lightgray</div>
    <div>lightgreen</div>
    <div>lightgrey</div>
    <div>lightpink</div>
    <div>lightsalmon</div>
    <div>lightseagreen</div>
    <div>lightskyblue</div>
    <div>lightslategray</div>
    <div>lightslategrey</div>
    <div>lightsteelblue</div>
    <div>lightyellow</div>
    <div>limegreen</div>
    <div>linen</div>
    <div>mediumaquamarine</div>
    <div>mediumblue</div>
    <div>mediumorchid</div>
    <div>mediumpurple</div>
    <div>mediumseagreen</div>
    <div>mediumslateblue</div>
    <div>mediumspringgreen</div>
    <div>mediumturquoise</div>
    <div>mediumvioletred</div>
    <div>midnightblue</div>
    <div>mintcream</div>
    <div>mistyrose</div>
    <div>moccasin</div>
    <div>navajowhite</div>
    <div>oldlace</div>
    <div>olivedrab</div>
    <div>orangered</div>
    <div>orchid</div>
    <div>palegoldenrod</div>
    <div>palegreen</div>
    <div>paleturquoise</div>
    <div>palevioletred</div>
    <div>papayawhip</div>
    <div>peachpuff</div>
    <div>peru</div>
    <div>pink</div>
    <div>plum</div>
    <div>powderblue</div>
    <div>rosybrown</div>
    <div>royalblue</div>
    <div>saddlebrown</div>
    <div>salmon</div>
    <div>sandybrown</div>
    <div>seagreen</div>
    <div>seashell</div>
    <div>sienna</div>
    <div>skyblue</div>
    <div>slateblue</div>
    <div>slategray</div>
    <div>slategrey</div>
    <div>snow</div>
    <div>springgreen</div>
    <div>steelblue</div>
    <div>tan</div>
    <div>thistle</div>
    <div>tomato</div>
    <div>turquoise</div>
    <div>violet</div>
    <div>wheat</div>
    <div>whitesmoke</div>
    <div>yellowgreen</div>
```

6.	Дана строка. Найдите самое длинное слово в строке
str = 'Lorem ipsum dolor  sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna    aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco   laboris nisi ut aliquip ex ea commodo consequat. Duis aute    irure dolor in reprehenderit   in voluptate velit esse   cillum dolore eu fugiat nulla pariatur.    Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum'

7.	Создать массив, на четных местах в котором стоят единицы, а на нечетных местах - числа, равные остатку от деления своего номера на 5.

8.	- Создайте форму
    - Добавьте в нее input для ввода url картинки
    - Добавьте кнопку input type='submit'
    - Добавьте пустой div
    - При отправке формы нужно взять введенный url и вставить в div картинку с этим url.