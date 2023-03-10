# 07_Supervised_learning
# Отток клиентов
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

Постройте модель с предельно большим значением *F1*-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте *F1*-меру на тестовой выборке самостоятельно.

Дополнительно измеряйте *AUC-ROC*, сравнивайте её значение с *F1*-мерой.

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)
## Цели проекта
- Проанализировать исторические данные о поведении клиентов банка, расторжении договоров. 
- Спрогнозировать уход клиента из банка.
- Построить модель классификации, метрика качества f1 (минимальное значение 0.59)
- Измерить AUC-ROC, сравнить её значение с f1-мерой.
## Задачи проекта
1 Предобработка данных
2 Исследование задачи и построение классификационной модели
2.1 RandomForestClassifier
2.2 LogisticRegression
2.3 DecisionTreeClassifier
3 Борьба с дисбалансом
3.1 Взвешивание классов class_weight='balanced'
3.2 Метод уменьшения обучающей выборки downsampling 
3.3 Метод увеличения обучающей выборки upsampling
4 Тестирование модели
5 Вывод

## Итог
- Значение метрик f1=0,615, roc_auc = 0.847 на тестовой выборке RandomForest:
