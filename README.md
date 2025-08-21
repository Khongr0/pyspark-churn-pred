# pyspark-churn-pred
предсказание оттока клиентов компании (PySpark, MlLib)
## Цель проекта
- Исследовать данные клиентов телеком-компании.
- Построить модели машинного обучения (Logistic Regression, Random Forest, GBT).
- Сравнить метрики (Accuracy, F1, Precision, Recall).
- Сохранить модели.
## Данные
- Источник: [Kaggle Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- Описание: информация о клиентах, тарифах, платежах и оттоке (Churn).
## Результаты
Лучшая модель GBT
| ACC=0.7981 | F1=0.7917 | P=0.7887 | R=0.7981
