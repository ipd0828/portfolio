# Классификация отзывов (отбор токсичных)

[Google Colab](https://drive.google.com/file/d/1EuVKONpoghtmZSUJZwy9x63ea8aha6G6/view?usp=sharing)    [ipynb](https://github.com/ipd0828/portfolio/blob/main/Project-4/Классификация%20отзывов.ipynb)

## Описание проекта

Требуется анализировать комментарии пользователей и выделять токсичные, чтобы отправить на модерацию.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**
- Pipeline, make_pipeline
- GridSearchCV
- torch
- transformers
- tqdm import notebook
- AutoModel, AutoTokenizer
- toxic-BERT, BERT

## Вывод

Была проведена исследовательская работа по обработке текстов и обучению, выбору модели для определения токсичных комментариев с использованием toxic-BERT. Логистическая регрессия справилась с задачей лучше остальных моделей.
