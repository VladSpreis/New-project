Итоговый проект (пример) курса "Машинное обучение в бизнесе"

Стек:

ML: sklearn, pandas, numpy API: flask Данные: с kaggle - https://www.kaggle.com/datasets/ulrikthygepedersen/airlines-delay
Задача: Будет ли задержка авиарейса исходя из данных о запланированном вылете. Бинарная классификация

Используемые признаки:

Flight- Идентификатор рейса(float64)
Time- Время отправления(float64)
Length- Продолжительность полета(float64)
Airline- Идентификатор авиакомпании(object)
AirportFrom- Из какого аэропорта вылетел рейс(object)
AirportTo- В какой аэропорт вылетел рейс(object)
DayOfWeek- День недели полета(int64)
Class- С задержкой (1) или нет (0)(int64)
Преобразования признаков: OHEEncoder, StandardScaler

Модель: logreg
