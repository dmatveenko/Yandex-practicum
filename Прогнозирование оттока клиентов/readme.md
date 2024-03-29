# Прогнозирование оттока клиентов
**Постановка задачи:**  

На основании исторических данных о поведении клиентов и расторжении договоров с банком необходимо спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Отбор наилучшей модели ведется по значению метрики F1.

Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

**Описание признаков в датасете:**  
Признаки:
* RowNumber — индекс строки в данных;
* CustomerId — уникальный идентификатор клиента;
* Surname — фамилия;
* CreditScore — кредитный рейтинг;
* Geography — страна проживания;
* Gender — пол;
* Age — возраст;
* Tenure — сколько лет человек является клиентом банка;
* Balance — баланс на счёте;
* NumOfProducts — количество продуктов банка, используемых клиентом;
* HasCrCard — наличие кредитной карты;
* IsActiveMember — активность клиента;
* EstimatedSalary — предполагаемая зарплата.  

Целевой признак:
* Exited — факт ухода клиента.
