---
layout: post
title:  "Проекты для прокачки"
date:   2017-05-15
excerpt: "Список в соновном состоящий из проектов вхяодящих в программы 
 обучения."
project: true
tag: 
- RoR
- medaved
- project
- training
comments: false
---
# [ReactCalendar](https://reactcalendarius.herokuapp.com/)
 
 Календарь-ежедневник, с возможность сохранять задачи, указав описание,
 дату, время. Интерфейс написан при помощи React.
 
## Стек:
    - RoR 5.0
    - Devise
    - Haml
    - React-Rails
    - PostgreSQl
    - Heroku
    - Moment.js
    
 [Github](https://github.com/medaved/reactcalendar)   

# [MessageBoard](https://github.com/medaved/messageboard)

 Доска объявлений, под объявлением можно оставлять коментарии.
 Для регистрации юзеров использовался Devise.

## Стек:
    - RoR 4.2
    - Devise
    - Haml
    - Sqlite3
    
 [Github](https://github.com/medaved/messageboard)   

# Rest Api
{% capture images %}
 /assets/img/posts/2017-05-15-training-projects-1.png
 /assets/img/posts/2017-05-15-training-projects-2.png
{% endcapture %}
{% include gallery images=images caption="Тестовое задание" cols=2 %}

## Результат:

 [Github](https://github.com/medaved/restblog)
 
## Ссылка на [heroku](https://blogpart1.herokuapp.com/), работает только API

    Для начала, надо получить "токен" запросом на:
    https://blogpart1.herokuapp.com/sessions
    тело POST:
    {"sessions":{"nickname":"test","password":"123456"}}
    В ответ придет "токен" который нужно вставить в header параметром X-Api-Key : токен, так же, в заголовке должен быть указан CONTENT-TYPE: application/vnd.api+json. 
