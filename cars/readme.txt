# Определение стоимости автомобилей

[ipynb](ссылка_на_гитхаб)

## Описание проекта

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. Имеются исторические данные: технические характеристики, комплектации и цены автомобилей. Необходимо построить модель для определения стоимости на основаии сравнения показателей нескольких моделей. Мы будем использовать RandomForestRegressor, CatBoostRegressor и LGBMRegressor, находя оптимальные гиперпараметры для каждой модели по критериям заказчика.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- sklearn.metrics.**mean_squared_error**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**train_test_split**
- sklearn.compose.**make_column_transformer**
- sklearn.pipeline.**make_pipeline**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.preprocessing.**StandardScaler**
- catboost.**CatBoostRegressor**
- lightgbm.**LGBMRegressor**
- lightgbm.**train**

## 

## Общий вывод

Была изучена общая информация по данным, произведена подготовка данных, обучение трех моделей с замером времени обучения и их предсказаний, лучшей была выбрана CatBoost