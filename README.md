Минипроект по пандас 

Задания <br />
Импортируйте библиотеку pandas как pd. Загрузите датасет bookings.csv с разделителем ;. Проверьте размер таблицы, типы переменных, а затем выведите первые 7 строк, чтобы посмотреть на данные.
Приведите названия колонок к нижнему регистру и замените пробелы на знак нижнего подчеркивания.
Пользователи из каких стран совершили наибольшее число успешных бронирований? Укажите топ-5.
На сколько ночей в среднем бронируют отели разных типов?
Иногда тип номера, полученного клиентом (assigned_room_type), отличается от изначально забронированного (reserved_room_type). Такое может произойти, например, по причине овербукинга. Сколько подобных наблюдений встретилось в датасете?
Проанализируйте даты запланированного прибытия. – На какой месяц чаще всего успешно оформляли бронь в 2016? Изменился ли самый популярный месяц в 2017?– Сгруппируйте данные по годам и проверьте, на какой месяц бронирования отеля типа City Hotel отменялись чаще всего в каждый из периодов
Посмотрите на числовые характеристики трёх переменных: adults, children и babies. Какая из них имеет наибольшее среднее значение?
Создайте колонку total_kids, объединив children и babies. Для отелей какого типа среднее значение переменной оказалось наибольшим?
Создайте переменную has_kids, которая принимает значение True, если клиент при бронировании указал хотя бы одного ребенка (total_kids), в противном случае – False. Посчитайте отношение количества ушедших пользователей к общему количеству клиентов, выраженное в процентах (churn rate). Укажите, среди какой группы показатель выше.



Описание данных <br />
· Hotel – тип отеля (City Hotel или Resort Hotel) <br />
· Is canceled – бронирование было отменено (1) или нет (0); не отмененное считается успешным <br />
· Lead time – количество дней, прошедших между датой бронирования и датой прибытия <br />
· Arrival full date – полная дата прибытия <br />
· Arrival date year – год прибытия <br />
· Arrival date month – месяц прибытия <br />
· Arrival date week number – номер недели прибытия <br />
· Arrival date day of month – день прибытия <br />
· Stays in weekend nights – количество выходных (суббота или воскресенье), которые гость забронировал для проживания в отеле <br />
· Stays in week nights – количество дней (с понедельника по пятницу), которые гость забронировал для проживания в отеле <br />
· Stays total nights – общее число забронированных ночей (сумма двух предыдущих колонок) <br />
· Adults – число взрослых <br />
· Children – число детей <br />
· Babies – число младенцев <br />
· Meal – выбранный тип питания <br />
· Country – страна происхождения клиента <br />
· Reserved room type – тип зарезервированного номера <br />
· Assigned room type – тип полученного номера (может отличаться от забронированного) <br />
· Customer type – тип бронирования <br />
· Reservation status – значение последнего статуса брони: Canceled - было отменено клиентом; Check-Out - клиент зарегистрировался, но уже покинул отель; No-Show - клиент не зарегистрировался и сообщил администрации отеля причину <br />
· Reservation status date – дата обновления статуса <br />
