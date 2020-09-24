# Задача
На основе данных о посещениях сайта Яндекс.Афиши изучить, 
как люди пользуются продуктом, когда они начинают покупать, 
сколько денег приносит каждый клиент, когда он окупается. 
Сделать когортный анализ, расчитать Retention rate, ROI, ROMI, LTV, CAC

# Данные
## Таблица visits (лог сервера с информацией о посещениях сайта):
Uid — уникальный идентификатор пользователя \
Device — категория устройства пользователя \
Start Ts — дата и время начала сессии \
End Ts — дата и время окончания сессии \
Source Id — идентификатор рекламного источника, из которого пришел пользователь \
## Таблица orders (информация о заказах):
Uid — уникальный id пользователя, который сделал заказ \
Buy Ts — дата и время заказа \
Revenue — выручка Яндекс.Афиши с этого заказа \
## Таблица costs (информация о затратах на маркетинг):
source_id — идентификатор рекламного источника \
dt — дата \
costs — затраты на этот рекламный источник в этот день \

# Используемые библиотеки
pandas, numpy, matplotlib, seaborn