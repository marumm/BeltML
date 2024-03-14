# Задание для позиции "Программист-стажер в области Аналитики Больших данных и Искусственного интеллекта"

Построить модель прогнозирования продаж, которая учитывает день недели и акцию.
Описание колонок:

## sales_raw.csv:
* date
* item_id - Код товара
* qnty - Количество продаж за день 


## discounts_raw.csv

* item_id - Код товара
* promo_type_code - Код типа акции
* sale_price_before_promo - Цена до акции
* sale_price_time_promo - Цена на акцию
* date_start - Дата начала акции
* date_end - Дата окончания акции

* Item - Код товара
* DateBegin - Начало акции
* DateEnd - Конец акции

## Необходимо получить прогнозы, в которых имеются такие поля predictions.csv:
* date
* item_id
* prediction

прогноз должен быть построен на январь 2024 года по всем товарам, которые участвовали в продажах в декабре 2023.

## Метрика оценки качества прогноза
RMSE