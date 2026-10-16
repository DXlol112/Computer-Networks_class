# Домашние задание № 15

## Что надо было сделать

Дай определение терминам:

- HTTP (расшифруй и объясни назначение)
- HTTPS — чем отличается от HTTP?
- Клиент-серверная модель — что это?
- Идемпотентность — что означает?

### 2.1. Разбери запрос

Дан HTTP-запрос:

```http
POST /api/users HTTP/1.1
Host: example.com
Content-Type: application/json
Authorization: Bearer eyJhbGciOiJIUzI1NiIs...
Content-Length: 58

{"name": "Иван", "email": "ivan@mail.com"}
```

Ответь на вопросы:

- Какой метод используется?
- Какой путь (endpoint) запрашивается?
- Какая версия HTTP?
- Что означает заголовок Content-Type?
- Что означает заголовок Authorization?
- Где находится тело запроса?

Дан HTTP-ответ:

```http
HTTP/1.1 201 Created
Content-Type: application/json
Location: /api/users/42

{"id": 42, "name": "Иван", "email": "ivan@mail.com"}
```

Ответь:

- Что означает статус-код 201?
- Зачем нужен заголовок Location?
- Что находится в теле ответа?

### 2.3. Собери запрос сам

Составь HTTP-запрос для:

- Получения списка всех товаров
- Создания нового товара с именем "Ноутбук" и ценой 50000
- Удаления товара с id=7
- Обновления товара с id=3 (изменить цену на 45000)

## Решение

### Термины

- HTTP (Hypertext Transfer Protocol) — протокол обмена данными между клиентом и сервером.
- HTTPS — HTTP но с шифрованием TLS.
- Клиент-серверная модель — клиент отправляет запрос, а сервер обрабатывает его и возвращает ответ.
- Идемпотентность — повтор одинакового запроса даёт тот же эффект на сервере, что и один запрос.

### 2.1

HTTP-запрос

1. Метод — `POST`.
2. Путь — `/api/users`.
3. Версия — `HTTP/1.1`.
4. `Content-Type: application/json` указывает, что тело запроса содержит JSON.
5. `Authorization` передаёт Bearer-токен для проверки доступа.
6. Тело находится после пустой строки: `{"name": "Иван", "email": "ivan@mail.com"}`.

HTTP-ответ

1. `201 Created` означает, что новый ресурс успешно создан.
2. `Location` указывает адрес созданного пользователя: `/api/users/42`.
3. В теле — JSON с данными пользователя: id, имя и email.

### 2.3

```http-запрос
GET /api/products HTTP/1.1
Host: example.com

POST /api/products HTTP/1.1
Host: example.com
Content-Type: application/json
Content-Length: 42

{"name": "Ноутбук", "price": 50000}

DELETE /api/products/7 HTTP/1.1
Host: example.com

PATCH /api/products/3 HTTP/1.1
Host: example.com
Content-Type: application/json
Content-Length: 16

{"price": 45000}
```
