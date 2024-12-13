# Информационная система для сети кофеен

## Описание проекта

Этот проект представляет собой микросервисную информационную систему для автоматизации процессов сети кофеен. Система реализует ключевые функции, такие как регистрация пользователей, управление меню, обработка заказов, программа лояльности, аналитика и уведомления.
Функциональность

    Регистрация и управление пользователями: Реализована регистрация, аутентификация и авторизация пользователей с использованием JWT токенов.
    Управление меню: Просмотр и редактирование позиций меню, фильтрация по категориям и диапазону цен.
    Обработка заказов: Создание, обновление заказов и изменение их статусов.
    Программа лояльности: Начисление и списание бонусных баллов, уведомления о состоянии бонусов.
    Аналитика: Получение финансовых отчетов, анализ продаж, статистика.
    Управление уведомлениями: Создание и отображение сообщений для пользователей, включая обновления заказов и бонусов.

## Микросервисы и репозитории

Сервис beans-profile: регистрация, аутентификация пользователей.
[Репозиторий](https://github.com/ChaoticGoodAdmi/java-beans-profile)

Сервис beans-menu: просмотр и редактирование позиций меню.
[Репозиторий](https://github.com/ChaoticGoodAdmi/java-beans-menu)

Сервис beans-order: просмотр и обновление заказов.
[Репозиторий](https://github.com/ChaoticGoodAdmi/java-beans-order)

Сервис beans-loyalty: управление программой лояльности.
[Репозиторий](https://github.com/ChaoticGoodAdmi/java-beans-loyalty)

Сервис beans-insight: получение финансовой отчетности.
[Репозиторий](https://github.com/ChaoticGoodAdmi/java-beans-insight)

Сервис beans-journal: управление сообщениями пользователей.
[Репозиторий](https://github.com/ChaoticGoodAdmi/java-beans-journal)

### Технологии

1. Архитектура: микросервисы с низкой связанностью.
2. Контейнеризация: Docker. 
3. Оркестрация: Kubernetes. 
4. Мониторинг и наблюдаемость: Prometheus, Grafana, OpenTelemetry. 
5. Асинхронное взаимодействие: Kafka. 
6. Базы данных: PostgreSQL, MongoDB, ClickHouse, Redis.

### Особенности

* Полностью контейнеризированная инфраструктура с автоматическим масштабированием.
* Событийно-ориентированная архитектура для асинхронной обработки данных.
* Поддержка CI/CD для автоматического развертывания и тестирования.

### Перспективы

* Интеграция с мобильным приложением.
* Расширение функциональности программы лояльности.
* Внедрение механизмов прогнозирования спроса и улучшение мониторинга.