# ToDo List App
## Особенность
>Приложение должно предоставлять **REST API** для выполнения **CRUD** операций с задачами и пользователями.

## To do
- [ ] Документация
- [ ] Тесты
- [ ] BD clients
- [ ] Реализовать валидацию входящих данных.
- [ ] Логирование действий (создание, обновление, удаление).
- [ ] Реализовать фильтрацию задач по статусу.

## Оглавление📚


Пользователи:

GET /users - получить список всех пользователей

GET /users/{id} - получить информацию о конкретном пользователе

POST /users - создать нового пользователя

PUT /users/{id} - обновить информацию о пользователе

DELETE /users/{id} - удалить пользователя

Задачи:

GET /tasks - получить список всех задач

GET /tasks/{id} - получить информацию о конкретной задаче

POST /tasks - создать новую задачу

PUT /tasks/{id} - обновить информацию о задаче

DELETE /tasks/{id} - удалить задачу


## FastAPI
ASGI/WSGI подход