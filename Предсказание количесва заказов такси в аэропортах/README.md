## Предсказание количества заказов такси в аэропортах

## Задача
Необходимо построить модель, которая спрогнозирует количесво заказов такси в аэропортах на следующий час.  

## Навыки и инструменты
*pandas, sklearn, catboost, xgboost, lightgbm hyperopt, pandas_profiling, numpy, Matplotlib, StatsModels,
машинное обучение*

## Выводы
Проанализированы исторические данные о заказах такси в аэропортах.  
Спрогнозировано количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки. 
Построены 5 моделей с разными гиперпараметрами для такого предсказания. Определены самые эффективные модели по валидационной выборке.
Все они прошли порог RSME на тестовой выборке в 48 пунктов.

