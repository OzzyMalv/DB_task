# Db task

## В базе данных имеется таблица: products - id[int, autoincrement], name[varchar], price[float], rating[float]

Необходимо написать минимальное API для реализации CRUD(create, read, update, delete) операций.

1.  При входе на сайт отображается содержимое таблицы из бд в виде html-таблицы. Первая строка таблицы соответствует названиями колонок в таблице бд.
2.  В дополнительных ячейках строк таблицы добавить кнопки для операций - update, delete.
3.  При клике на edit - открывается попап с формой для обновления строки таблицы. Текущие данные должны быть проставлены в форму. При самбите формы - появляется лоадинг бар и отправляется ajax-запрос на обновление данных в бд. При успешном или неуспешном обновлении должно выводиться сообщение пользователю.
4.  При клике на delete - должно происходить удаление строки в бд через ajax.
5.  Ниже таблицы должны быть кнопка для создания новой строки в бд, аналогично при клике появляется попап с формом добавления данных и при сабмите выполняется ajax-запрос для добавления.
6.  При клике на ячейки шапки таблицы должны происходить сортировка по соответствующему полю. Дополнение - 1-ый клик сортировка asc, 2-ой клик сортировка desc. Визуально с помощью стрелочки отобразить направление активной сортировки.
7.  Методы сортировки не должны перезагружать страницу.
8.  В урл после сортировки должны записываться сортировочные параметры. При открытии полученной ссылки в браузере изначальные данные должны сортироваться в соответствии значений в ссылке.
