# Статус проекта:
## Завершен

# Описание проекта
Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. 
Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. 
Постройте модель для такого предсказания.


## Цель исследования
Значение метрики RMSE на тестовой выборке должно быть не больше 48.

# Вывод
В ходе выполнения проектной работы было проведено изучение и анализ данных, ресемплирование данных по одному часу.

Была проведена декомпозиция временных рядов, сравнение показателей за весь период собранный в датасете и за один месяц.

Мы провели обучение и тестирование линейных моделей.

Лучший результат на тестовой выборке показала модель RandomForestRegressor.

Метрика составила 42.475, что ниже 48. Цель исследования достигнута.

# Стек
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
