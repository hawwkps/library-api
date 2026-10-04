# Library API

OpenAPI 3.1 контракт сервиса «Библиотека»: книги, читатели, выдачи.

## Файлы

- `openapi.yaml` — контракт API
- `STYLE.md` — правила проектирования API
- `REVIEW.md` — саморевью контракта по чек-листу

## Просмотр документации

Откройте `openapi.yaml` в редакторе с поддержкой OpenAPI (например, расширение
"OpenAPI (Swagger) Editor" в VS Code) или вставьте содержимое файла в
[Swagger Editor](https://editor.swagger.io/).

## Основные ресурсы

- `GET/POST /books`, `GET/PUT/DELETE /books/{id}` — книги
- `GET/POST /readers`, `GET/PUT/DELETE /readers/{id}` — читатели
- `GET/POST /loans`, `GET /loans/{id}`, `POST /loans/{id}/return` — выдачи