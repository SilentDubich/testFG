Тестовое задание получено 23 июля в 15:56.
Выполнил задание: Дубов Кирилл Александрович, kirill.dubov.2012@mail.ru
##Реализованы все функции по тз, а именно:
1) Сортировка по столбцам
2) Пагинация
3) Поиск нужной записи в таблице, но немного не по ТЗ, а именно поиск происходит без нажатия на кнопку "Найти"
4) Вывод дополнительной информации о пользователе, однако не под таблицей, а под записью
5) Добавление записи в начало таблице, также реализована валидация формы добавления
6) Индикатор загрузки, пока идет запрос на сервер

##Ответы на вопросы:

Q: Почему дополнительная информация не под таблицей, а под строкой?

A: Так несколько удобнее по той причине, что не нужно скроллить страницу вниз для того, чтобы просмотреть информацию

Q: Почему поиск происходит без нажатия на кнопку

A: Таким образом поиск происходит быстрее и нет надобности дополнительно нажимать на кнопку таким образом улучшается UX

Q: Как проводилось тестирование

A: Непосредственно во время работы проводились ручные тесты и в случай ошибок использовался дебаггер, позднее основные методы были покрыты тестами

Q: Почему выбран этот набор библиотек

A: axios - маленькая и удобная библиотека для асинхронных запросов, Redux - полезная библиотека для управления состоянием, 
которая позволяет отделять всю бизнес-логику от Ui
