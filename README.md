Описание проекта
Сеть отелей добавила на свой сайт возможность забронировать номер без предоплаты, однако, если клиент отменял бронирование, то компания получала убыток. Чтобы решить эту проблему, необходимо предложить модель, которая предсказывает отказ от брони. Затраты на разработку определены в размере 0.4 млн., эффект от внедрения модели в виде роста выручки должен быть как минимум не менее указанных затрат.

В рамках проекта выполнено:

Предобработка данных
исследование категориальных и количественных признаков
OHE кодирование
Проверка на мультиколлинеарность
Масштабирование
Рассчитаны бизнесс-показатели до внедрения системы
Сформулирована ML задача, обоснован выбор метрики
Рассмотрены модели классификации
LogisticRegression
DecisionTree
RandomForest
Проведен подбор гиперпараметров для лучшей модели и тестирование
Рассчитаны бизнесс-показатели с учетом внедрения модели, сделан вывод о целесообразности внедрения
Сформулирован "портрет ненадежного клиента"
Результаты

Основная задача - предложить модель, которая позволит увеличить выручку сети отелей, предсказывая отказ от бронирования и позволяя минимизировать потери, предлагая гостю внести депозит. По результатам тестирования лучшую метрику f1 = 0.57 показала логистическая регрессия. На тестовых данных расчет бизнесс-показателей после применения модели показал прирост выручки на 5.8 млн., что значительно превышает затраты на внедрение, определенные в размере 0.4 млн..

Портрет ненадежного клиента:

чем больше время между датой бронирования и датой прибытия - тем больше вероятность отказа
зона наиболее высокого риска отказа, когда подтверждение о бронировании получено в диапазоне от 28 до 47 дней.
гость из популярной страны
прибытие назначено на пятницу
высокий сезон (лето)
без младенцев
трое детей от 3-х до 14 лет
без взрослых или 3-е взрослых
не требуется место для парковки
тип питания FB или SC
канал дтистрибуции TA/TO
тип заказчика Transient
без специальных отметок (требований)
