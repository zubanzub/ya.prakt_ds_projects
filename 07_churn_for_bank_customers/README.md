# Отток клиентов банка

## Цель исследования:

Построение модели для задачи классификации: спрогнозировать, уйдёт клиент из банка в ближайшее время или нет, исходя из предоставленных исторических данных о поведении клиентов и расторжении договоров с банком.

## Входные данные:
Исторические данные о поведении клиентов и расторжении договоров с банком:  

**Признаки**
- *RowNumber* — индекс строки в данных
- *CustomerId* — уникальный идентификатор клиента
- *Surname* — фамилия
- *CreditScore* — кредитный рейтинг
- *Geography* — страна проживания
- *Gender* — пол
- *Age* — возраст
- *Tenure* — количество недвижимости у клиента
- *Balance* — баланс на счёте
- *NumOfProducts* — количество продуктов банка, используемых клиентом
- *HasCrCard* — наличие кредитной карты
- *IsActiveMember* — активность клиента
- *EstimatedSalary* — предполагаемая зарплата  


**Целевой признак**
- *Exited* — факт ухода клиента

## Используемые библиотеки и модули:
*pandas*, *numpy*, *matplotlib*, *seaborn*, *sklearn*

## Результаты
Проведена предобработка исходного датасета, устранен дисбаланс классов. Спрогнозирована вероятность ухода клиента из банка в ближайшее время: построена модель с предельно большим значением F1-меры с последующей проверкой на тестовой выборке (значение метрики - ). Дополнительно измерен AUC-ROC, соотнесен с F1-мерой. 
