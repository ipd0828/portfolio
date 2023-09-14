# Улучшение процесса обогащения  
[Тетрадка ipynb](https://github.com/ipd0828/portfolio/blob/main/Project-2/Обогащение%20золота.ipynb)
## Описание проекта
Создана модель машинного обучения (регрессии), которые предсказывают коэффициент восстановления золота из золотосодержащей руды. Модель помогает оптимизировать производство, чтобы не выполнять убыточные операции.
## Инструменты:
- python
- pandas
- numpy
- scipy
- sklearn.model_selection.cross_val_score
- sklearn.metrics.mean_squared_error
- sklearn.metrics.mean_absolute_error
- sklearn.preprocessing.StandardScaler
- sklearn.linear_model.LinearRegression
- sklearn.tree.DecisionTreeRegressor
- sklearn.ensemble.RandomForestRegressor
- matplotlib
- sklearn.model_selection.GridSearchCV
- sklearn.dummy.DummyRegressor
- sklearn.metrics.make_scorer
  ## Общий вывод
В связи с отсутствием необходимой информации об обогащении золотосодержащей руды, процедуре флотации и иных данных о производстве. Собрана информация о бизнес-процессе в сети интернет, проведена предобработка и анализ признаков DataFrame. Создана метрика качества, с помощью поиска гиперпараметров по сетке GridSearchCV и кросс-валидации обучены модели для стадий грубой и тонкой очистки. Далее проведена проверка лучших моделей на тестовом наборе и выбрана одна для запуска в производство.
