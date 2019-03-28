# ITSvit’s Comments Backend

## Description

Вам необходимо реализоавать Backend часть для работы с комментариями.

## Requirements

-   ESlint;
-   Express.js / Hapi.js;
-   REST API;
-   Node 10+;
-   Docker / docker-compose;
-   SQL / NoSQL database.

## Would be a plus

-   Unit Tests

## API

| Description                                         | Method | Endpoint            |
| --------------------------------------------------- | ------ | ------------------- |
| Перечень всех комментариев                          | GET    | /api/comments/      |
| Получить описание выбранного комментария            | GET    | /api/comments/{id}/ |
| Создание нового комментария                         | POST   | /api/comments/      |
| Обновление текста или автора выбранного комментария | PUT    | /api/comments/{id}/ |
| Удалить выбранный комментарий                       | DELETE | /api/comments/{id}/ |

### Создание нового комментария (params)

```json
{
	"author": "string",
	"text": "string"
}
```

### Обновление текста или автора выбранного комментария (params)

```json
{
	"author": "string",
	"text": "string"
}
```

## How to deliver?

Создать Pull Request на ветку master.
