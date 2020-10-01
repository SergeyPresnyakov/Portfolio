# Portfolio
В данном репозитории хранятся мои проекты в области Data Science. Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессия "Специалист по Data Science".

| № | Название проекта | Описание | Используемые библиотеки | Целевая метрика | Метрика на валидационной выборке | Метрика на тестовой выборке |
| :---------------------- | :---------------------- | :---------------------- | :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| 1 | [Определение температуры стали на этапах лигирования](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Предсказание%20конечной%20температуры%20стали) | Построение моделей, которые предсказывают конечную температуру стали при ее лигировании в зависимости от ряда факторов.| *pandas, sklearn, catboost, xgboost, hyperopt, pandas_profiling, pyod* | MAE < 6 | MAE_val = 5.52 |  MAE_test = 5.8 |
| 2 | [Определение возраста человека по фотографии](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Определение%20возраста%20человека%20по%20фотографии) | Построение модели,  которая по фотографии определит приблизительный возраст человека.| *keras, pandas, numpy* | MAE <= 8 | MAE_val = 6,21 |  MAE_test = 6,63 |
| 3 | [Предсказание количества заказов такси в аэропортах](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Предсказание%20количесва%20заказов%20такси%20в%20аэропортах) | Построение модели,  которая спрогнозирует количесво заказов такси в аэропортах в следующий час.| *pandas, sklearn, catboost, xgboost, lightgbm hyperopt, pandas_profiling* | RMSE <= 48 | RMSE_val = 0.006 |  RMSE_test = 43 |
| 4 | [Классификация текстовых комментариев на позитивные и негативные](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Классификация%20текстовых%20комментариев%20на%20позитивные%20и%20негативные) | Построение модели для классификации комментариев на позитивные и негативные | *pandas, sklearn, catboost, nltk, transformers, torch, tqdm, hyperopt* | F1 >= 0.75 |   |   F1 = 0.78 |
| 5 | [Выбор лучшей модели для предсказания стоимости автомобиля](https://github.com/SergeyPresnyakov/Portfolio/tree/master/Выбор%20лучшей%20модели%20для%20предсказания%20стоимости%20автомобиля%20Данные) | Необходимо построить несколько моделей для определения стоимости автомобиля и выбрать лучшую по следующим кретериям: Качество предсказания, Скорость предсказания Время обучения| *pandas, sklearn, catboost, lightboost, XGBoos, hyperopt*| RMSE | RMSE_val = 0|  RMSE_test = |
