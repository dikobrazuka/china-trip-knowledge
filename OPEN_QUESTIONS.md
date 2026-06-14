# Open Questions



## Source Open Questions

# 26. Список открытых вопросов

| Вопрос | Почему важен | Что нужно сделать | Приоритет |
|---|---|---|---|
| Где ночевать в Shanghai 20–21? | Прилёт, багаж, старт маршрута | Найти/подтвердить бронь | Высокий |
| Где ночевать в Shanghai 28–01? | Disney и вылет PVG | Забронировать | Высокий |
| Где ночёвки Zhangjiajie 22–24? | После Tianmen и перед Furong | Проверить Trip.com/забронировать | Высокий |
| Куплен ли внутренний flight to Zhangjiajie? | Без него рушится 21–22 июня | Найти билет/купить | Высокий |
| Как попасть в Wugongshan hotel до закрытия cableway? | Критический риск | Связаться с отелем, пересобрать день | Высокий |
| Где оставить багаж перед Wugongshan? | Нельзя тащить 23 кг | Найти storage/отель/такси | Высокий |
| Купить ли Early Park Entry Pass? | Disney day quality | Проверить цену/доступность | Средний |
| Что делать 30 июня вместо Zhujiajiao? | Последний день | Выбрать Shanghai city plan | Средний |
| Нужен ли Dragon Boat plan? | Был интерес | Проверить дату/место актуально | Низкий/средний |
| Нужна ли термуха? | Wugongshan night | Проверить прогноз | Средний |

---

## Technical Planning Debt

# 25. Технический долг планирования

- Нет подтверждённого Shanghai hotel 20–21 июня.
- Нет подтверждённого Shanghai hotel 28 июня–1 июля.
- Нет подтверждённых Zhangjiajie hotels 22–24 июня в доступных письмах.
- Нет найденного подтверждения внутреннего flight to Zhangjiajie.
- Нет точных train tickets Furong → Changsha → Pingxiang.
- Нет точного train ticket Shangrao/Wangxian → Hangzhou.
- Нет Hangzhou → Shanghai переезда 28 июня.
- Нет Disneyland ticket на 29 июня.
- Нет подтверждения Tianmen Mountain tickets.
- Нет подтверждения Zhangjiajie National Forest Park tickets.
- Нет Glass Bridge ticket.
- Не решён багаж на Wugongshan.
- Не подтверждено, как попасть в Wugongshan hotel после 17:00.
- Не проверен прогноз погоды на Zhangjiajie/Wugongshan/Wangxian.
- Не оформлен backup plan на дождь/туман.
- Не исправлен Disney timing: 13:00 плохо сочетается с Early Entry.

---

## Conflicts That Require Resolution

# 24. Конфликты данных

| Вопрос | Вариант А | Вариант Б | Предполагаемое текущее состояние | Что проверить |
|---|---|---|---|---|
| Дата Disney | Ранее 22 июня / в середине маршрута | 29 июня в календаре | 29 июня | Купить билет |
| Beijing | Был в старом маршруте | Пользователь убрал после Furong | Beijing архив | Не возвращать без прямого запроса |
| Wugongshan arrival | Календарь: прибытие 17:00 | Отель: cableway closes 17:00 | Конфликт критический | Сдвинуть логистику |
| Furong hotel name | 12C Stream & Mountain View | Twelve Cities Baiyujing... | Название изменено | Использовать актуальное и адрес |
| Pingxiang Wugong booking | Старая бронь 1 519,44 ₽ | Новая бронь 6 155,19 ₽ | Старая отменена, новая активна | Проверить Trip.com orders |
| Hangzhou checkout | 28.06 до 14:00 | 28.06 нужен Shanghai до Disney | Нужен переезд/новый отель | Забронировать Shanghai |
| Zhangjiajie hotels | Есть XIADUO 21–22 | Ночи 22–24 не найдены | Разрыв | Проверить Trip.com |
| XIADUO check-in | До 00:00 | Календарь прибытие 04:30 | Риск late check-in | Написать отелю |

---
