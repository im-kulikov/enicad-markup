# Вёрстка для Enicad, тестовое задание.



## Дисклеймер

- Я конечно мог бы придумать какой-то иной вариант переключения, но к сожалению из-за того, что работы
    много у меня почти не было времени на иное решение.
- Что касается установить форму посередине экрана, решение обусловлено тем, что можно использовать
    вариант когда устанавливается position: absolute, margin: auto, а top|left|right|bottom в 0,
    таким образом можно так же установить элемент в центр, но в таком случае необходимо использовать
    высоту, что не кошерно
- Так же установка формы по центру экрана выполняется добавлением модификатора &-static
- Для того чтобы установить определённой форме видимость - добавляем его radio-инпуту checked.
- Rails вариант не успел собрать, так же по причине ограниченного времени, но достаточно просто можно
    перенести всё написанное на Haml (я использую Hamlit) или Slim (проще всего). 

## Немного по стеку технологий:

в проекте используются следующие элементы:

- tars от команды 2gis
- scss как препроцессор + autoprefixer для совместимости с другими браузерами
- jade как препроцессор HTML

Так как задача стояла в том, чтобы реализовать вёрстку без JS, его не подключал. Из фреймворков использую
foundation, так как он позволяет mobile-first. Но в текущем варианте, я его использовал не более чем на 1%.

## Просмотр результата:

```
$ npm i
$ npm i -g tars-cli 
$ tars dev
```

После запуска и выбора в паре меню первые варианты, откроется страница с собранным проектом. 

PS: Если есть какие-то недостающие зависимости, которые возможно не описал в package.json - то больше информации можно найти
на странице проекта [tars от команды 2gis](https://github.com/tars/tars).

Так же, я загрузил пример к себе на сайт. Результат вы можете посмотреть на [этой странице](https://kulikov.im/test-tasks/enicad-markup/index.html)

!["Yandex.Metrika counter"](https://mc.yandex.ru/watch/37586045)
