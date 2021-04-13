# ✨ Язык разметки Markdown (.md)
Markdown (произносится маркда́ун) — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других). 
# Заголовки
Создание заголовков производится путём помещения знака решетки перед текстом заголовка. Количество знаков «#» соответствует уровню заголовка. Как и в HTML, предоставлены 6 уровней заголовков:
# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня
Если использовать серию из знаков «*», или «-», или «_» на отдельной строчке, то можно создать подчеркивание:
# Текст с выделением
*курсив*
**сильное выделение**
~~зачеркнутый~~
##### **Полужирный заголовок**
##### *Заголовок курсивом*
##### ~~Зачеркнутый заголовок~~
Заголовки также можно выделить.
> Цитаты (тег blockquote)


# Списки
* элемент маркированного списка
- ещё один элемент маркированного списка
+ буллеты элементов могут быть разными, что не скажется на отображении списка

1. Элемент нумерованного списка
2. Элемент №2 того же списка
9. Элемент №3 списка — элементы нумеруются по порядку, цифра в начале строки не имеет значения

# Программный код
Элементы кода могут быть внутри строки (inline) либо многострочными блоками.
Внутри строки код выделяется символом «\`» (апостроф), чтобы экранировать апостроф - напишите перед ним символ «\».
Пример кода внутри строки (inline) `Hello world!`
Многострочный блок кода обозначается отступом из 4 пробелов или одного Tab. 
Между окончанием блока текста и началом блока кода должна быть одна пустая строчка.

    Ниже начинается многострочный блок кода
    <!doctype html>
    <html>
        <head>
            <!-- Заголовок документа -->
        </head>
        <body>
            <!-- Тело документа -->
        </body>
    </html>
    Блок кода завершился
# Ссылки
#### [Текст ссылки](http://example.com/ "Необязательный заголовок ссылки")

Альтернативный способ задавать ссылки, если есть повторения:
Где-то среди текста встречается [текст ссылки][example].
Также ссылка повторяется: [пример адреса][example].

[example]: http://example.com/ "Необязательный заголовок ссылки"

# Изображения
Два изображения на одной строчке:
![Alt-текст](https://via.placeholder.com/150x50 "Заголовок изображения") ![Alt-текст](https://via.placeholder.com/150x50 "Заголовок изображения")
Два изображения на разных строчках:
![Alt-текст](https://via.placeholder.com/150x50 "Заголовок изображения") 
![Alt-текст](https://via.placeholder.com/150x50 "Заголовок изображения")

# Таблица
Таблица может содержать ссылки, изображения, inline программный код и текст, ячейка таблицы может быть пустой.
Заголовок 1 | Заголовок 2 | Заголовок 3
---|---|---
Ячейка текста | | ![Alt-текст](https://via.placeholder.com/150x50 "Заголовок изображения")
[Текст ссылки](http://example.com/ "Необязательный заголовок ссылки")|Ячейка текста|`Hello, world!`
