## Чекпоинт 4. scope переменных

### Мягкий дедлайн (уложиться в срок) - 12 апреля

Расширяем функциональность! Теперь пора обрабатывать создание переменных!

* Необходимо обработать shadowing-переменных (одна переменная закрывает другую)
* Переменная дважды объявляется в одном scope
* Переменная используется, хотя она не объявлена


Дополнительно необходимо реализовать систему типов. Для этого предлагается адаптировать `ScopeLayer`, 
чтобы в значении был один из объектов:
* примитивный тип
* методы
    * принимаемые аргументы (имя - тип)
    * возвращаемое значение
* классы
    * список методов
    * список полей
    
Необходимо контролировать, чтобы функция именно вызывалась, и чтобы переменной класса нельзя было присвоить тип.

Пример можно найти в [примере variable scope](/05-variable-scopes). 

Успехов!