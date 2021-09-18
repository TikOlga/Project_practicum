# Проекты выполненные во время обучения по направлению "Аналитик данных"
## Принятие решений на основе данных. Приоритизация гипотез, A/B-тест
[AB-test](https://github.com/TikOlga/Project_practicum/tree/main/AB-test)

Задача: увеличение выручки интернет - магазина, на основе предоставленных данных.  

Предоставлены: файл с гипотезами, файл с заказами, файл с визитами.

***Cтек: pandas, scipy.stats, numpy, matplotlib, приоритезация гипотез*** 

Проект содержит:
- приоритезацию гипотез ICE, RICE;
- кумулятивную выручку по группам А и В;
- кумулятивный средний чек по группам А и В;
- относительное изменение кумулятивного среднего чека группы В к группе А;
- кумулятивную конверсию по группам;
- относительное изменение кумулятивной конверсии группы В к группе А;
- расчет статистической значимости различий в конверсии по "сырым" данным между группами;
- расчет статистической значимости различий в среднем чеке заказа между группами по "сырым" данным;
- расчет статистической значимости различий в конверсии между группами по "очищенным" данным;
- расчет статистической значимости различий в среднем чеке заказа между группами по "очищенным" данным;
- вывод. По результатам принято решение остановить тест. 



## Анализ клиентов регионального банка.

Задача: выделить портрет клиентов, которые склонны уходить.

Предоставлен датасет с данными клиентов.

***Cтек: numpy, seaborn, matplotlib, pandas, scipy.stats***
Проект содержит:
- исследовательский анализ данных:
  - количество оставшихся и ушедших клиентов;
  - сколько клиентов и из кахих городов;
- катигоризованны данные (крединтый скоринг, возраст, баланс и заработная плата) и
разбиты на оставшихся и ушедших, приведены их относительные и абсолюные величины а также постороены графики;
- сформулированны и проверены статистические гипотезы;
- сделаны выводы, составлен портрет, даны рекомендации.
