### Имеются данные о стоимости недвижимости в Мельбурне.
### Каждая строчка – это объект недвижимости, по которому известны некоторые параметры и его цена.
### Задачи: 
   #### 1. Проанализировать данные 
   #### 2. Прогнозирование стоимости недвижимости с помощью различных моделей машинного обучения
### Данный датасет имеет достаточное количество категориальных текстовых столбцов. Поэтому в данной задаче будем использовать CatBoost.
### Параметры объекта:
### Suburb – Район
### Address – адрес
### Rooms – количество комнат
### Type – тип объекта:
#### h - house,cottage,villa, semi,terrace;
#### u - unit, duplex;
#### t - townhouse.
### Price – цена объекта
### Method – метод продажи объекта:
#### S - property sold;
#### SP - property sold prior;
#### PI - property passed in;
#### VB - vendor bid;
#### SA - sold after auction.
### SellerG – имя риэлтора
### Date – дата продажи объекта
### Distance – расстояние до центрального района в километрах
### Postcode – почтовый индекс
### Bedrooms2 – количество спален
### Bathroom – количество ванных комнат
### Car – количество парковочных мест
### Landsize – площадь прилегающей территории
### BuildingArea – площадь самого объекта
### YearBuilt – год постройки
### CouncilArea – округ
### Lattitude – широта
### Longtitude – долгота
### Regionname – еще одно административное деление на подобие округа
### Propertycount – не совсем ясно что, возможно количество объектов в округе
### id – id объекта
### Ниже указаны ссылки на источники дополнительных данных.
### Широта и долгота по районам (Suburb) с почтовым индексом: https://www.matthewproctor.com/australian_postcodes
### Широта и долгота по районам (Suburb) для построения карты: https://data.gov.au/geoserver/vic-suburb-locality-boundaries-psma-administrative-boundaries/wfs?request=GetFeature&typeName=ckan_af33dd8c_0534_4e18_9245_fc64440f742e&outputFormat=json
