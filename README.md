# ArchPC-SUAI
Помощь по Архитектуре ЭВМ в ГУАП c [VAX-11](https://en.wikipedia.org/wiki/VAX-11)

### [Cкрипт](src/1.py) для помощи в 1 лабе
1. Задаете Номер варианта (V)
2. Задаете Номер группы (G)

### Адресация
| ->[] | ->[]->[]  |
|:---:|:---:|
| Ссылаетя на знаечение | Ссылается на ссылку, которая ссылается на значение |
| Косвенная | Двойная косвенная |
* [B, D, F ->[]->[]](Address/B-D-F) - Следует понимать, адрес не может быть дальше чем на ±128 от объявления адресации, если у вас все правильно, но все равно не работает => Попробуйте подтянуть ваши ячейки ближе друг к другу
* [A, C, E ->[]](Address/A-C-E) - По возможности расположите ваши значения после объявления адресации, чтобы избежать проблем с дополнительным кодом
* [8F](Address/8F) - При возможности заменяйте на литеральную адресацию
* [9F](Address/9F) - Всегда LongWord
* [5](Address/5X) 
* [6 ->[]](Address/6X) 
* [7 ->[]](Address/7X) 
* [8 ->[]](Address/8X)
* [9 ->[]->[]](Address/9X)

### [Перевод в плавающую запятую](Mantissa/)

## Помогите будущему поколению! TODO
* [x] Добавить адресацию 5
* [x] Добавить адресацию 6
* [x] Добавить адресацию 7
* [ ] Добавить адресавацию 9x
* [ ] Добавить Литеральную
* [ ] Дополнить 8F литеральной
* [ ] Добавить раздел "Переходы"
* [ ] Добавить рубрика "Вопросы от Яковлева, которые в водят в беличий транс"


| ![Яковлев](img/brainfucker.jpg)  |  Ленивей студента - только преподаватель <br> &copy; _Яковлев Александр Викторович_ |
|--------|:---:|


