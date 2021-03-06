# Исследование надёжности заёмщиков — анализ банковских данных

**Цель исследования:**  

Выявление влияния показателей (количество детей, семейное положение, уровень дохода, цель кредита) на факт погашения кредита клиентом в срок для дальнейшего построения модели кредитного скоринга.

## Входные данные:

Статистика о платежеспособности клиента:

-	*children* — количество детей в семье
-	*days_employed* — общий трудовой стаж в днях
-	*dob_years* — возраст клиента в годах
-	*education* — уровень образования клиента
-	*education_id* — идентификатор уровня образования
-	*family_status* — семейное положение
-	*family_status_id* — идентификатор семейного положения
-	*gender* — пол клиента
-	*income_type* — тип занятости
-	*debt* — имел ли задолженность по возврату кредитов
-	*total_income* — ежемесячный доход
-	*purpose* — цель получения кредита

## Используемые библиотеки:
*pandas*, *PyMystem3*

## Результаты
Полученные данные очищены от выбросов, пропусков и дубликатов, а также преобразованы разные форматы данных.
Скорректированы типы данных на соответствующие хранящимся данным, выделены леммы в значениях столбца и осуществлена категоризация данных.
Определена доля кредитоспособных клиентов. Проанализировано влияние семейного положения, количества детей клиента, уровня дохода и цели кредита на факт возврата кредита в срок. 
