# Теория

- [SASS](https://sass-scss.ru)
- [Документация SASS](https://sass-scss.ru/documentation/)
- [Полный гайд по SCSS/SASS](https://medium.com/nuances-of-programming/%D0%BF%D0%BE%D0%BB%D0%BD%D1%8B%D0%B9-%D0%B3%D0%B0%D0%B9%D0%B4-%D0%BF%D0%BE-scss-sass-b09ae0c87afe)
- [Развёрнутое руководство по Sass/SCSS](https://tproger.ru/translations/complete-sass-guide/)
- [gulpjs](https://gulpjs.com/)
- [Gulp](https://siteok.org/blog/html/gulp#c-13)
- [Html препроцессор nunjucks](https://siteok.org/blog/html/nunjucks)
- [Nunjucks](https://mozilla.github.io/nunjucks/)
- [CSS - Префиксы браузеров](https://itchief.ru/html-and-css/vendor-prefixes)
- [Зачем нужны вендорные префиксы](https://vaden-pro.ru/blog/css/vendornye-prefiksy)

> Последние 3 ссылки вам нужны на почитать и желательно разобраться.

# Практика

Ссылка на [figma](https://www.figma.com/file/zujRsp3rGLVZBHP8ncOWGN/MEDDICAL---Hospital-website-template-(Community)-(Copy)?t=P1IxDnrUhHqpZfud-0)
> Нужно выполнить страницу Home и сделать ей адаптивную вёрстку. Делать компонентами те блоки, которые переиспользуются на других страницах. 

Для начала требуется установить gitbush. [Click for download](https://github.com/git-for-windows/git/releases/download/v2.39.0.windows.2/Git-2.39.0.2-64-bit.exe)

Также устанавливаем NodeJS (Recomended For Most Users) [Click for download](https://nodejs.org/en/)

Открываем Visual Studio Code и создаём пустую папку, куда будем помещать наш проект. 

Открываем терминал: Terminal -> New Terminal.

В поле, где появился терминал, есть знак "+", справа от него стоит галочка. Там выбираем Git Bush.

Теперь делаем последовательность команд в терминале:

1. Клонируем репозиторий ```git clone https://github.com/msheiko/web-builder.git```
2. Меняем директорию ```cd ./web-builder```
3. Устанавливаем зависимости ```npm install```
4. Запускаем процесс сборки ```npm run dev```

Должна открыться страница в браузере. Если нужно остановить процесс сборки, в терминале нажмите ```Ctrl + C```. Заново запускаете снова с помощью ```npm run dev```.

## Для работы с HTML

Модули (компоненты) для HTML создаются по пути ```src/_html/_base/_includes/```. Все блоки, которые используются на нескольких страницах должны быть созданы через модули.

Там, все файлы должны начинаться с ```_```. Например: ```_doctors.html```.

Для подлкючения этого модуля на вашу страничку, подключаете в файле ```index.html``` с помощью команды 
> {% INCLUDE "\_html/\_base/\_includes/\_doctors.html" %}

## Для работы с SCSS

Модули (компоненты) для SCSS создаются по пути ```src/assets/css/```. Все модули созданные с помощью HTML теперь требуется стилизировать.

Там, все файлы должны начинаться с ```_```. Например: ```_doctors.scss```.

После, нам требуется подключить этот файл к файлу, который в себе всё собирает. Он находится по пути ```src/assets/css/app.scss```. Подключаем с помощью команды ```@import "doctors";```

В папке ```fonts``` удаляем все стандартные шрифты и закидывем те, которые я прикреплял в ТГ.

Все картинки, которые нужны в проекте, помещаются в папку ```src/assets/css/img/```.  Подключаются в HTML вот так ```<img src="assets/img/example.jpg" alt="">```.

Создаём переменные, для работы с цветами. Они находятся по пути ```src/assets/css/_tools/_variables.scss```. Там создаём переменные. Например ```$primary: #1F2B6C;```.

Чтобы вызвать эту переменную в scss достаточно написать свойство и ```$primary```. Например ```color: $primary```.

### Поздравляю! Вы дошли до шага, когда можно начинать свой творческий путь. Удачи с:
