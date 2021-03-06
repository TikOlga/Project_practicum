# Проекты выполненные во время обучения по направлению "Аналитик данных"
## [Принятие решений на основе данных. Приоритизация гипотез, A/B-тест](https://github.com/TikOlga/Project_practicum/blob/main/AB-test.ipynb)

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



## [Анализ клиентов регионального банка.](https://github.com/TikOlga/Project_practicum/blob/main/bank_clients.ipynb)

Задача: выделить портрет клиентов, которые склонны уходить.

Предоставлен датасет с данными клиентов.

***Cтек: numpy, seaborn, matplotlib, pandas, scipy.stats***

Проект содержит:
- исследовательский анализ данных:
  - количество оставшихся и ушедших клиентов;
  - сколько клиентов и из кахих городов;
- категоризованны данные (крединтый скоринг, возраст, баланс и заработная плата) и
разбиты на оставшихся и ушедших, приведены их относительные и абсолюные величины а также постороены графики;
- сформулированны и проверены статистические гипотезы;
- сделаны выводы, составлен портрет клиента, даны рекомендации.


## [Анализ бизнес-показателей.](https://github.com/TikOlga/Project_practicum/blob/main/business_indicators.ipynb)

Задача: помочь маркетологам снизить расходы - отказаться от невыгодных источников трафика и перераспределить бюджет. 

Предоставлены данные: визитов, покупок, данные по рекламным кампаниям и расходы на них.

***Cтек: numpy, seaborn, matplotlib, pandas, продуктовые метрики (DAU, WAU, MAU)***

Проект содержит:
- рассчет продуктовых метрик(DAU, WAU, MAU);
- количество посещений сайта в день;
- расчет сколько времени пользователи проводят на сайте;
- расчет Retention Rate;
- расчет сколько времени в среднем проходит с момента первого посещения сайта до совершения покупки;
- среднее количество покупок на одного покупателя за 6 месяцев;
- рассчет среднего чека;
- LTV;
- расчет среднего САС на одного покупателя;
- расчет ROMI по когортам в разрезе источников;
- сделаны выводы по проделанному анализу, даны рекомендации.
