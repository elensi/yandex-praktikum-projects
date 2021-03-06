# Отток клиентов фитнес-клуба

Основная задача проекта - спрогнозировать вероятность оттока клиентов клуба.  

1. Проведен исследовательский анализ данных (EDA);
2. Построены 2 модели прогнозирования оттока;
3. Проведена кластеризация клиентов.


## Данные  

- Данные пользователя за предыдущий до проверки факта оттока месяц;
- Информация на основе журнала посещений, покупок и информация о текущем статусе абонемента клиента.

## Задача 


1. Спрогнозировать вероятность оттока (на уровне следующего месяца) для каждого клиента;
2. Сформировать типичные портреты пользователей: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства;
3. Проанализировать основные признаки, наиболее сильно влияющие на отток;
4. Сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами: 
    - выделить целевые группы клиентов;
    - предложить меры по снижению оттока;
    - определить другие особенности взаимодействия с клиентами. 


## Выводы

Обе модели показали себя хорошо. Доля правильных ответов в обоих случаях 0,92. Немного лучше себя показала модель логистической регрессии в метриках точности и полноты.  
На отток клиентов влияют такие факторы как, отдаленность клуба от места работы или жилья, возраст клиентов, рекомендации и партнерские программы


## Статус проекта  
Проект завершен


## Библиотеки, которые были использованы в проекте  
sklearn, pandas, matplotlib, numpy, seaborn, plotly, scipy, math
