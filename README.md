# Portfolio
В данном репозитории хранятся мои проекты в области Data Science. Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессия "Специалист по Data Science".

| № | Название проекта | Описание | Используемые библиотеки | Целевая метрика | Метрика на валидационной выборке | Метрика на тестовой выборке |
| :---------------------- | :---------------------- | :---------------------- | :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| 1 | [Определение температуры стали на этапах лигирования](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Предсказание%20конечной%20температуры%20стали) | Построение моделей, которые предсказывают конечную температуру стали при ее лигировании в зависимости от ряда факторов.| *pandas, sklearn, catboost, xgboost, hyperopt, pandas_profiling, pyod* | MAE < 6 | MAE_val = 5.52 |  MAE_test = 5.8 |
| 2 | [Определение возраста человека по фотографии](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Определение%20возраста%20человека%20по%20фотографии) | Построение модели,  которая по фотографии определит приблизительный возраст человека.| *keras, pandas, numpy* | MAE <= 8 | MAE_val = 6,21 |  MAE_test = 6,63 |
| 3 | [Предсказание количества заказов такси в аэропортах](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Предсказание%20количесва%20заказов%20такси%20в%20аэропортах) | Построение модели,  которая спрогнозирует количесво заказов такси в аэропортах в следующий час.| *pandas, sklearn, catboost, xgboost, lightgbm hyperopt, pandas_profiling* | RMSE <= 48 | RMSE_val = 0.006 |  RMSE_test = 43 |
| 4 | [Классификация текстовых комментариев на позитивные и негативные](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Классификация%20текстовых%20комментариев%20на%20позитивные%20и%20негативные) | Построение модели для классификации комментариев на позитивные и негативные | *pandas, sklearn, catboost, nltk, transformers, torch, tqdm, hyperopt* | F1 >= 0.75 |   |   F1 = 0.78 |
| 5 | [Выбор лучшей модели для предсказания стоимости автомобиля](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Выбор%20лучшей%20модели%20для%20предсказания%20стоимости%20автомобиля%20Данные) | Построение нескольких моделей для определения стоимости автомобиля и выброр лучшей из них по нескольким кретериям | *pandas, sklearn, catboost, lightboost, XGBoos, hyperopt*| RMSE | RMSE_val = 1715|  RMSE_test = 1753 |
| 6 | [Предсказание коэффициента восстановления золота из золотосодержащей руды](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Предсказание%20коэффициента%20восстановления%20золота%20из%20золотосодержащей%20руды) | Построение модель для предсказания коэффициента восстановления золота из золотосодержащей руды | *pandas, sklearn, hyperopt*| sMAPE | sMAPE = 5.69  | sMAPE = 7.95 |
| 7 | [Предсказание оттока клиетов из банка](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Предсказание%20оттока%20клиентов%20из%20банка) | Нужно спрогнозировать, уйдёт ли клиент из банка в ближайшее время или нет | *pandas, sklearn, matplotlib*| F1>=0.59 | F1_val = 0.62 | F1_test = 0.59 |
| 8 | [Определение региона, где добыча нефти принесет наибольшую прибыль](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Определение%20региона%2C%20где%20добыча%20нефти%20принесет%20наибольшую%20прибыль) | Нужно построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски. | *pandas, sklearn, matplotlib*|  |  |  |
