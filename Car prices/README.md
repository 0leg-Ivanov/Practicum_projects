# Проект «Определение стоимости автомобилей»

## Задача

Нужно построить модель для определения стоимости автомобиля на основе исторических данных: технические характеристики, комплектации и цены автомобилей.

## Используемые библиотеки

Pandas, numpy, seaborn, matplotlib, scipy, sklearn, category_encoders, lightgbm, catboost, shap

## Данные

 - <b>DateCrawled </b> — дата скачивания анкеты из базы;
 - <b>VehicleType </b> — тип автомобильного кузова;
 - <b>RegistrationYear</b> — год регистрации автомобиля;
 - <b>Gearbox</b> — тип коробки передач;
 - <b>Power</b> —  мощность (л. с.);
 - <b>Model</b> — модель автомобиля;
 - <b>Kilometer</b> — пробег (км);
 - <b>RegistrationMonth</b> — месяц регистрации автомобиля;
 - <b>FuelType</b> — тип топлива;
 - <b>Brand</b> — марка автомобиля;
 - <b>Repaired</b> — была машина в ремонте или нет;
 - <b>DateCreated</b> — дата создания анкеты;
 - <b>NumberOfPictures</b> — количество фотографий автомобиля;
 - <b>PostalCode</b> — почтовый индекс владельца анкеты (пользователя);
 - <b>LastSeen</b> — дата последней активности пользователя;
 - <b>Price</b> — цена (евро) - целевой признак;
