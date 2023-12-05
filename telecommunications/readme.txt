# Прогнозирование оттока клиентов

[ipynb](ссылка_на_гитхаб)

## Описание проекта

Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах. Таким образом, нам необходимо на основании предоставленных исторических данных о поведении клиентов и расторжении договоров с оператором спрогнозировать, уйдёт клиент от оператора в ближайшее время или нет.

## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- **numpy**
- **phik**
- **seaborn**
- sklearn.metrics.**accuracy_score**
- sklearn.metrics.**roc_auc_score**
- sklearn.metrics.**confusion_matrix**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.preprocessing.**StandardScaler**
- sklearn.compose.**make_column_transformer**
- sklearn.pipeline.**make_pipeline**
- sklearn.ensemble.**RandomForestClassifier**
- catboost.**CatBoostClassifier**
- lightgbm.**LGBMClassifier**
- lightgbm.**train**
- joblib.**dump**
- joblib.**load**

## 

## Общий вывод

Цель проекта (разработать модель для решения задачи классификации, позволяющую при заданной точности метрики AUC-ROC не более 0.85 прогнозировать уход клиента) была успешно достигнута с помощью модели LGBMClassifier с гиперпараметрами {'max_depth': 10, 'n_estimators': 180}; метрика AUC-ROC на тестовых данных соответствует ограничениям проекта. Дополнительно были предложены рекомендации по повышению точности модели.