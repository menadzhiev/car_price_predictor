### Предсказание стоимости подержанных автомобилей
----

Проект нацелен на проведение исследования в области анализа вторичного рынка автомобилей, а также на выявление закономерностей и тенденций, присущих данному сектору. 
Данные для нашего проекта были собраны с сайта [cars.com](https://www.cars.com/), на котором публикуются объявления о продаже подержанных машин в США.

Основной целью нашего исследования является разработка модели предсказания стоимости подержанных автомобилей, основанной на проверенных гипотезах и выявленных закономерностях, вытекающих из собранных данных. Наш проект состоит из 6 ключевых этапов, каждый из которых предоставляет из себя отдельную осмысленную часть, решающую определенную задачу исследования.

### Шаг №1: [Сбор данных](https://github.com/menadzhiev/car_price_predictor/blob/main/Сбор%20данных.ipynb)
---
Для получения необходимых характеристик американского рынка подержанных автомобилей мы спарсили данные с сайта [cars.com](https://www.cars.com/), которые в последствии были собраны в [таблицу](https://github.com/menadzhiev/car_price_predictor/blob/main/таблицы%20с%20данными/cars_df.csv), требующую дальнейшей обработки.

### Шаг №2: [Предварительная обработка данных](https://github.com/menadzhiev/car_price_predictor/blob/main/Предобработка%20данных.ipynb)
___
Полученные данные подверглись дополнительной обработке, включающей удаление выбросов, обработку пропущенных значений и приведение данных к удобному для понимания и исследования формату. Этот этап позволил нам получить необходимый для дальнейшего корректного анализа [набор данных](https://github.com/menadzhiev/car_price_predictor/blob/main/таблицы%20с%20данными/cars_df_final.csv).

### Шаг №3: [EDA](https://github.com/menadzhiev/car_price_predictor/blob/main/Визуализация.ipynb)
---
Третий этап проекта представляет из себя разведочный анализ данных, в ходе которого мы исследовали основные закономерности в характеристиках подержанных автомобилей. Были проведены статистический и визуальный анализы с целью выявления взаимосвязей различных параметров со стоимостью машин на вторичном рынке.

### Шаг №4: [Проверка гипотез](https://github.com/menadzhiev/car_price_predictor/blob/main/Гипотезы.ipynb)
---
Исследуемые ранее закономерности помогли нам сформировать ряд гипотез, которые были проверены с помощью всевозможных статистических методов. Действительно ли, американские и европейские автомобили в среднем стоят одинаково, а 90% и более автомобилей ездят на бензине? Именно на эти вопросы Вы найдете ответы в данной части нашего проекта.

### Шаг №5: [Создание новых признаков](https://github.com/menadzhiev/car_price_predictor/blob/main/Создание%20новых%20признаков.ipynb)
---
Пятая часть проекта посвящена созданию новых признаков на основании уже имеющихся характеристик автомобилей на вторичном рынке. Подобная работа с признаками способна улучшить предсказательную способность нашей модели и раскрыть дополнительные закономерности в данных о подержанных автомобилях.

### Шаг №6: [Машинное обучение](https://github.com/menadzhiev/car_price_predictor/blob/main/Машинное%20обучение.ipynb)
---
В заключительной части проекта на основе полученных результатов и выявленных закономерностей мы разработали модель предсказания стоимости подержанных автомобилей. Мы использовали различные методы машинного обучения, такие как построение линейной регрессии и подбор оптимальных гиперпараметров для регуляризации, алгоритм имитации отжига,метод случайного леса, а также градиентый бустинг с целью нахождения оптимальной модели, способной выдавать точные и надежные предсказания.

___

Благодарим Вас за проявленный интерес к нашему проекту! Держите котика)

С уважением,

команда разработчиков😋

В лице Менаджиева Максима и Зарянкиной Варвары

<div align="center">
    <img src="https://imgur.com/JAVmJYB.jpg" alt="ФЭН делает проект по андану">
</div>

