# План API

## Пользователи

GET /api/users

## Авторизация

POST /api/auth/login

POST /api/auth/register

## Избранное

GET /api/favorites

POST /api/favorites

DELETE /api/favorites/{id}

## Товары

GET /api/products

GET /api/products/{id}

POST /api/products

PUT /api/products/{id}

DELETE /api/products/{id}

## Корзина

GET /api/cart

POST /api/cart

DELETE /api/cart/{id}

## Заказы

GET /api/orders

POST /api/orders