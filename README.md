# Определение стоимости автомобилей

## Описание проекта
Условный сервис по продаже автомобилей разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Необходимо построить модель для определения стоимости. 

Заказчику важны:

- качество предсказания;
- скорость предсказания;
- время обучения.


## Stack
- Pandas
- Numpy
- Seaborn
- Scikit-learn 
- LGBMRegressor
- CatBoostRegressor
- XGBRegressor


## Вывод

Были обучены модели:
- `LinearRegression`;
- `RandomForestRegressor`;
- `CatBoostRegressor`;
- `LGBMRegressor`;
- `XGBRegressor`.

Наилучший результат, в совокупности со всеми метриками качества заказчика, показала модель `XGBRegressor` с закодированными данными с помошью Ordinal Encoder.
