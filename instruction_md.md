# Справочные материалы по Markdown

Markdown - это облегченный язык разметки с синтаксисом форматирования обычного текста.

## Полужирное и курсивное начертания

Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки, например **вот так**.

Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки, например *вот так*.

## Заголовки

Язык разметки Markdown поддерживает 2 стиля обозначения заголовков: подчеркивание и выделение символом («#»).

Платформа Docs поддерживает шесть уровней заголовков Markdown:
* Между последним символом # и содержимым заголовка должен присутствовать пробел.
* В одном файле Markdown должен быть один и только один заголовок H1.
* Заголовок H1 указывается в файле в первую очередь, сразу после блока метаданных YML.
* Заголовки H2 автоматически отображаются в правом меню навигации опубликованного файла. * Заголовки более низкого уровня не отображаются, поэтому для удобства перехода по содержимому рекомендуется использовать заголовки H2.

## Изображения

Для изображений по умолчанию поддерживаются следующие типы файлов: .jpg, .png.

Базовый синтаксис Markdown для внедрения изображения выглядит следующим образом: 

![Привет](icon.jpg)

## Ссылки

Система публикации поддерживает два типа гиперссылок: **URL-адреса** и **ссылки на файлы**. Самый простой способ создать относительную ссылку — скопировать URL-адрес в браузере, а затем удалить часть.

https://learn.microsoft.com/contribute/how-to-write-links

## Списки (нумерованные, маркированные)

Чтобы создать нумерованный список, можно использовать все единицы. При публикации числа отображаются в возрастающем порядке в виде последовательного списка, например, вот так:
1. Элемент 1
2. Элемент 2
3. Элемент 3

Для создания маркированного списка используйте - или *, за которым следует пробел в начале каждой строки, выглядит следующим образом:

* Элемент 1
* Элемент 2
* Элемент 3

## Автоматические ссылки

Markdown поддерживает упрощённый порядок автоматического создания ссылок для URL-адресов и адресов электронной почты. Для этого достаточно поместить URL-адрес или почтовый адрес в угловые скобки, и Markdown сделает его гиперссылкой.

## Цитаты

Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа.

> Вот пример цитаты
>> Пример вложенной цитаты

## Дополнительные элементы

Обратный слеш
Может употребляться в Markdown перед специальными символами для того, чтобы они воспринимались в их буквальном (а не служебном) значении.

## Строчные элементы

Markdown поддерживает два стиля оформления ссылок:

* Гиперссылка, с немедленным указанием адреса (внутритекстовая);
* Гиперссылка, подобная сноске.

## Введение в GitHub. Работа с удаленным репозиторием

Коммит, созданный нами, хранится в репозитарии, привязанном к конкретной папке на нашем компьютере, т.е. является локальным. Для загрузки данных в удаленный репозитарию сначала нужно к нему подключиться.
Для того, чтобы связать созданный нами локальный репозитарий с удаленным, выполним команду:
**git remote add origin ссылка**

Отправка коммита осуществляется с помощью команды push, которая имеет два параметра - имя удаленного репозитория (в нашем случае origin) и ветку, в которую необходимо внести изменения (master - это ветка по умолчанию для всех репозиториев).