# CMF
Data Analysis Course
## CIAN_project
parsing and data analysis of [cian.ru](http://www.cian.ru/)

## Что ещё можно и нужно сделать:
* учесть исключённые квартиры
* исключить из рассмотрения выбросы: очень дорогие квартиры
* произвести замену пропущенных значений по округам:
  * пропущенные числовые значения заменять на среднее по объектам выборки
  * пропуск в значениях площади заменять весовым средним, исходя из знания общей площади квартиры и остальных известных значений
  * пропущенные по факту категориальные значения заменять: 
    * на самые популярные значения 
    * на новые значения
    * сделать случайный выбор из выборочного распределения заначений
* сделать dummy-кодирование для категориального признака District
* feature engineering

 
