## Цель проекта: Предсказывать поведение, чтобы удерживать клиентов. 

### Содержание.
#### Каждая строка представляет клиента, каждый столбец содержит атрибуты клиента, описанные в столбце Метаданные.

### Набор данных включает информацию о:
#### Клиенты, которые ушли в течение последнего месяца — колонка называется «Отток».
#### Услуги, на которые подписался каждый клиент: телефон, несколько линий, Интернет, онлайн-безопасность, онлайн-резервное копирование, защита устройства, техническая поддержка, потоковое телевидение и фильмы.
#### Информация об учетной записи клиента — как долго он был клиентом, контракт, способ оплаты, безбумажный биллинг, ежемесячные платежи и общие платежи.
#### Демографическая информация о клиентах — пол, возрастной диапазон, наличие партнеров и иждивенцев.

### Лучшая модель CatBoostClassiffier = {eval_metric = 'AUC',loss_function='Logloss'} с базовыми гиперпараметрами.

#### Метрики оценки модели CatBoost:
#### Model(CatBoostClassifier)
#### Precision_yes - 0.7
#### Recall_yes - 0.53
#### F1_yes - 0.6
#### Accuracy - 0.81
#### Precision_no - 0.84
#### Recall_no - 0.92
#### F1_no - 0.88
#### AUC - 0.84