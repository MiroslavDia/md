# md

Списки
* элемент маркированного списка
- ещё один элемент ненумерованного списка
+ буллеты элементов могут быть разными

1. Элемент нумерованного списка
2. Элемент №2 того же списка
9. Элемент №3 списка — элементы нумеруются по порядку, цифра в начале строки не имеет значения
Заголовки
Создание заголовков производится путём помещения знака решетки перед текстом заголовка. Количество знаков «#» соответствует уровню заголовка. HTML предоставляет 6 уровней заголовков.

# Заголовок первого уровня
...
### Заголовок третьего уровня
...
###### Заголовок шестого уровня
Первые два уровня заголовка также имеют альтернативный синтаксис:

Заголовок первого уровня
========================

Заголовок второго уровня
------------------------
Цитаты (тег blockquote)
> Данный текст будет заключен в HTML-теги <blockquote></blockquote>
Ссылки
[Текст ссылки](http://example.com/ "Необязательный заголовок ссылки")
альтернативный способ задавать ссылки если есть повторения

Где-то среди текста встречается [текст ссылки][example].

Также ссылка повторяется [пример адреса][example].

Ссылка на [второй][foo] также [Bar][] ресурсы.

[example]: http://example.com/ "Необязательный заголовок ссылки"
[foo]: http://example.net/ 'Необязательный заголовок ссылки'
[bar]: http://example.edu/ (Необязательный заголовок ссылки)
Изображения
![Alt-текст](http://example.com/ "Заголовок изображения")
