Отчет о результатах тестирования сервиса [https://restful-booker.herokuapp.com/apidoc/index.html#](https://restful-booker.herokuapp.com/apidoc/index.html "Follow link")

**Testing Team:** тестировщик Ольга Колодич

**Testing Process Description:** Был протестирован API [https://restful-booker.herokuapp.com/apidoc/index.html#](https://restful-booker.herokuapp.com/apidoc/index.html "Follow link"). Создан чек-лист из 20 тест-кейсов. Проведено ручное тестирование приложения по чек-листу. Оформлено 3 бага. Отмечено некорректное описание работы функции DeleteBooking в спецификации.

**Schedule:** затрачено 24 часа.
**Summary:** Базовые функции API проверены, работают согласно документации. Не осуществляются GET запросы по first/lastname и checkin/checkout date. При повторном запросе POST c использованными ранее данными создается новый запрос с новым ID и удалением старого ID и старого запроса.

**Plans:** провести расширенное тестирование всех функций API, а также нефункциональное тестирование.

**Recommedations:**

-проверить функцию получения ID GET-запросом по фильтрам first/lastname и checkin/checkout date;

-уточнить, как должна создаваться запись с аналогичными предыдущему запросу данными.

**Bugs statistics:** 

3 bugs: High Priority, Major Severity

