Исследование поведения пользователей приложения по продаже продуктов питания

Цель исследования:

- узнать, как пользователи доходят до покупки. Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах? На каких именно?
- анализ результов A/A/B-эксперимента - повлияет ли изменение шрифта в приложении на поведение пользователей.

Ход исследования:

1.Изучение общей информации файла с данными.

2.Предобработка данных.

3.Анализ и проверка данных.

4.Изучение воронки событий.

5.Анализ результатов эксперимента.

6.Общий вывод.

Входные данные - запись логов. Каждая запись в логе — это действие пользователя или событие.

Путь к файлу - /datasets/logs_exp.csv.

Описание данных:

EventName — название события;

DeviceIDHash — уникальный идентификатор пользователя;

EventTimestamp — время события;

ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.
