# Предсказание оттока сотрудников
[IPYNB](https://github.com/lil-scripter/practicum_projects/blob/bd5e74298118f4e41ff8cf820a918a2310c6e6e5/8-ML-HR_analytics/8-ML-HR_analytics.ipynb)
## Описание проекта
Компания предоставила данные с характеристиками сотрудников компании. Среди них — уровень удовлетворённости сотрудника работой в компании.

**Цель**

Предсказать отток сотрудников компании с учётом уровня удовлетворённости сотрудника.

**Задачи**
1. Построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика.
2. Построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.

## Стек
pandas, numpy, matplotlib, seaborn, sklearn, scipy

## Общие выводы
Увольнение сотрудника из компании связано с уровнем его удовлетворённости работой в компании. Проведение опросов среди всех работников слишком энергоёмко, поэтому была предложена разработка моделей машинного обучения, которые будут предсказывать удовлетворённость сотрудников работой в компании и предсказывать увольнение сотрудника.

Обучена модель регрессии SVC, которая предсказывает уровень удовлетворённости сотрудников с метрикой SMAPE равной 13.68%.
Наиболее значимым признаком для модели является заработная плата, чем она выше, тем выше значения уровня удовлетворённости.
Составлен портрет сотрудника, который с большей вероятностью уволится из компании.

С учётом предсказанного уровня удовлетворённости работников и фактических данных работников была обучена модель логистической регрессии LogisticRegression, которая предсказывает увольнение сотрудников с точностью 92.1%.

Составлены рекомендации для поддержания удовлетворённости сотрудников.
