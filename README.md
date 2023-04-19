# Оглавление
1. [Sessions](#Sessions)
    1. [SessionsAdd](#SessionsAdd)
    1. [SessionsDelete](#SessionsDelete)
2. [Users](#Users)
    1. [UsersAdd](#UsersAdd)
    1. [UsersDelete](#UsersDelete)
# Sessions
Действия с сессиями
            
## SessionsAdd
### :orange_book: `PUT` **sessions/add**
Добавление новой сессии
            
#### Parameters
| Parameter | Value | Description | Data Type |
|-|-|-|-|
| user | (required) | login or email | string |
| password | (required) | password | string |
#### Response
| Code | Description |
|-|-|
| 200 | token |
| 500 | Failed |
## SessionsDelete
### :closed_book: `DELETE` **sessions/delete**
Удаление сессии
            
#### Parameters
| Parameter | Value | Description | Data Type |
|-|-|-|-|
| token | (required) | token of session | string |
#### Response
| Code | Description |
|-|-|
| 200 | Deleted |
| 500 | Failed |
# Users
Действия с пользователями
            
## UsersAdd
### :orange_book: `PUT` **users/add**
Добавление нового пользователя
            
#### Parameters
| Parameter | Value | Description | Data Type |
|-|-|-|-|
| user | (required) | login | string |
| password | (required) | password | string |
| email | (required) | email | string |
#### Response
| Code | Description |
|-|-|
| 200 | Created |
| 500 | Failed |
## UsersDelete
### :closed_book: `DELETE` **users/delete**
Удаление пользователя по токену сессии
            
#### Parameters
| Parameter | Value | Description | Data Type |
|-|-|-|-|
| token | (required) | token of session | string |
#### Response
| Code | Description |
|-|-|
| 200 | Deleted |
| 500 | Failed |
