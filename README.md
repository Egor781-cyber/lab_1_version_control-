#  Опис файлу `bookstore.xml`

Файл **`bookstore.xml`** є навчальним прикладом структурування даних у форматі **XML**.  
Він моделює базу даних книжкового магазину, де зберігаються відомості про книги, авторів, видавництва, ціни, а також наявність у різних філіях.


##  Основне призначення

Мета цього документа — продемонструвати, як за допомогою **XML** можна:

- організувати дані в ієрархічній формі (магазин → книга → автор → ціна);
- забезпечити зручний обмін інформацією між системами;
- використовувати **DTD** або **XSD** для перевірки правильності структури файлу;
- навчитися застосовувати **DOM** і **XPath** для доступу до елементів XML у програмах.


##  Структура документа

Приклад структури `bookstore.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<bookstore>
    <book category="Programming">
        <title lang="en">Learning XML</title>
        <author>John Smith</author>
        <publisher>O’Reilly Media</publisher>
        <price>39.95</price>
        <stock>25</stock>
    </book>

    <book category="Web">
        <title lang="en">HTML & CSS: Design and Build Websites</title>
        <author>Jon Duckett</author>
        <publisher>Wiley</publisher>
        <price>29.99</price>
        <stock>40</stock>
    </book>
</bookstore>
