# Kaggle Competitions
# Проект 3. [SF-DST] Booking reviews

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Представьте, что вы работаете датасаентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов нахождения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель играет нечестно, и его стоит проверить.

:arrow_up:[к оглавлению](_)

### Какой кейс решаем?    
Поставлена задача построение модели, которая предсказывает рейтинг отеля.

**Условия соревнования:**  
* Данное соревнование является бессрочным и доступно для всех потоков.
* Срок выполнения соревнования устанавливается индивидуально в каждом потоке.
* Тестовая выборка представлена в LeaderBoard целиком.
* Делаем реальный ML продукт, который потом сможет нормально работать на новых данных.

**Метрика качества**     
Результаты оцениваются по метрике MAPE.
Для каждого id отеля в наборе тестовых данных вы должны предсказать рейтинг отеля для reviewer_score переменной. Файл должен содержать заголовок и иметь следующий формат:
* reviewer_score,id
* 1,1
```python reviewer_score,id
  1,1```

**Что практикуем**     
Делаем реальный ML продукт, который потом сможет нормально работать на новых данных.


### Краткая информация о данных
База с выгрузкой предоставляется с образцом ноутбука. 
  
:arrow_up:[к оглавлению](.README.md#Оглавление)


### Этапы работы над проектом  
Задание выполнено, отправлено на проверку.
https://www.kaggle.com/code/motoborgrus/proj-3-hotels/edit/run/103728182

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
Получен Score: 12.69324. Занял 69 место из 126, но это не чисто мои заслуги :)

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
Получил первый опыт работы с ML моделями. Не совсем красиво оформил мультиколлинеарность, но уже и так затянул с опытами отправляю на проверку.

:arrow_up:[к оглавлению](.README.md#Оглавление)
