# Project: Store
Высоконагруженный магазин


Тестовое задание, реализация ИМ, с нагрузкой в 10 000 запросов в минуту (~150 в секунду)


#### Установка

    git clone https://github.com/a-f-larionov/store.git

#### Запуск docker

    docker-compose up

#### Запуск локально

    Локальный профиль -Dspring.profiles.active=local


#### Демо

    Открываем страницу http://localhost:8080/
    Логин: admin
    Пароль: admin


#### Отчёт по Apache AB Стресс Тестированию:
    Server:
    Ubuntu 18.04 Bionic Beaver
    SSD 10Gb    
    Memory : 1Gb
    CPU: 2Ghz 1 Core
# 
    Запрос клиента: 10 000 запросов 52 секунды
    Запрос списка товаров: 10 000 запросов 72 секунды
    Запрос создания товара(успешный): 10 000 запросов 73 секунды

Функционал:
  - Пользователей.
  - Ролевого доступа.
  - Список товаров.
    - Добавление\удаление\редактирование товара администратором.
  - Создание покупок авторизованным пользователем.

