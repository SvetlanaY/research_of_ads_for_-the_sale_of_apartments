# Исследование объявлений о продаже квартир

**Входные данные** - данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 

**Цель исследования** установить параметры, которые позволят построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 

**Результаты исследования** выявить факторы, влияющие на рыночную стоимость объектов недвижимости.

**Ход исследования**
Данные получаем из файла `https://code.s3.yandex.net/datasets/real_estate_data.csv`. О качестве данных ничего не известно. Поэтому понадобится обзор данных. 
Таким образом, исследование пройдёт по следующим этапам:
 1. Обзор данных.
 2. Предобработка данных.
 3. Расчеты и добавление результатов в таблицу.
 4. Исследовательский анализ данных.
 5. Общий вывод.
