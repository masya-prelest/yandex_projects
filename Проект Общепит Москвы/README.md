# Исследования рынка общепита в Москве для принятия решения об открытии нового заведения  


Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами.  

Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ
результатов A/B-теста, построил графики кумулятивной выручки, среднего чека,
конверсии по группам, а затем посчитал статистическую значимость различий конверсий
и средних чеков по сырым и очищенным данным. На основании анализа мной было
принято решение о нецелесообразности дальнейшего проведения теста.  

В работе использованы: Python и библиотеки Pandas, Matplotlib, SciPy, а также A/B-тестирование и проверка статистических гипотез. 


### Описание данных  
Таблица `rest_data`:   
`id` — идентификатор объекта;  
`object_name` — название объекта общественного питания;  
`chain` — сетевой ресторан;  
`object_type` — тип объекта общественного питания;  
`address  — адрес;  
`number` — количество посадочных мест.  