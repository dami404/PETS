Тестовое задание:

-html\css\javascript
* Используя [NASA API](https://api.nasa.gov/) создать страницу на которой выводится актуальная [Astronomy Picture of the Day](https://apod.nasa.gov) с названием и коипрайтом. Под актуальным фото вывести шесть случайных прьевью для других дат. По клику на актуальное фото или превью, открывать изображение высокого качества в новой вкладке.

* Добавить внизу страницы кнопку "Показать ещё". При клике на кнопку через апи загрузить ещё 6 случайных фото и добавить их к тем что уже выведены в виде превью.

* Не выводить одно и тоже фото несколько раз.

-PHP
* Добавить возможность оценить фото(рейтинг от 1 до 10).
* Хранить данные о рейтинге в базе данных.
* Вывести текущий рейтинг(среднее арифметическое всех оценок).

-Трудности, с которыми столкнулся при выполнении:

*Проблема: получение данных с формы. У  меня не передавались данные с формы, их просто не видела программа. Решение: т.к форма создавалась при загрузке картинки, нужно следить за тем, чтобы данные с нее считывались сразу после загрузки, иначе выдает ошибку.

*Проблема: addEventListener не работает. addEventListener не работал, когда я передавал данные с формы на сервер. Решение: после исправления ошибки с получением данных, эта ошибка также устранилась

*Проблема: сохранение даты в бд. Дату я сохранял в формате "гггг-мм-дд". БД ругалась на такой формат. Решение: я заменил "-" на "", и поместил получившееся число в БД

*Проблема: возвращаемое значение из БД. Из БД возвращается тип object. Решение: приведение типов, я перевел object в array, а далее работал уже с элементами массива.

Мне понравилось, работать с АПИ, особенно когда есть нормальная документация. Узнал много новых функций в php и как использовать на нем БД. Если в моей карьере все проекты будут такими- я готов работать хоть до 80 лет)
