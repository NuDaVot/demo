Report2_Kuliev.ipynb - отчет 

 2.1 Построение модели классификации

Разбиение выборки на обучающую и тестовую: Выборка состоит из 1217 записей. Количество данных достаточно для проведения надлежащего обучения модели. Будет использовано 80% выборки для обучения, что позволит модели получить достаточно информации для корректной работы. Оставшиеся 20% будут использованы, для проверки работоспособности на новых, не изученных данных
Обучение моделей: Случайный лес показал наиболее хорошие результаты на тестовых данных, и именно accuracy = 76% и F1-score = 42%. Он и будет применен в дальнейшем улучшении модели
2.2 Оптимизация модели

Выделение ключевых признаков: ухудшило модель
Понижение размерности: дало существенный прирост
Настройки гиперпараметров модели: не дало результата
Визуализация: отлично определились категории 0 и 3, не отстаёт категории 2 и 4, все же остальные категории определились плохо, так как в изначальном dataframe их было малое количество
Сохранение модели

_Report2_Kuliev.html - отчет 

model.pkl - обученая модель
