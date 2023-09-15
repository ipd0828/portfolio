# Прогнозирование оттока клиентов телеком компании

[Тетрадка ipynb](https://github.com/aq2003/Portfolio/)

## Описание проекта

Для оператора связи построена модель прогнозирования ухода клиента. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**
- seaborn
- matplotlib
- train_test_split
- OneHotEncoder
- OrdinalEncoder
- StandardScaler
- Pipeline
- GridSearchCV
- confusion_matrix
- phik


## Вывод

Проведена предобработка данных, созданы новые признаки. Проведен анализ, на основе которого, часть признаков отсеяно. Построены модели с поиском гиперпараметров по сетке и кроссвалидацией: Логистической регрессии, Случайного леса и градиентного бустинга CatBoost. 
В качестве рабочей модели, удовлетворяющей требованиям заказчика, выбрана модель CatBoost.
