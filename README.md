# Оглавление
1. [Sessions](#Sessions)
    1. [SessionsAdd](#SessionsAdd)
2. [Users](#Users)
    1. [UsersAdd](#UsersAdd)
# Sessions
Действия с сессиями
            
## SessionsAdd
### :orange_book: `PUT` **sessions/add**
Добавление новой сессии
            
#### Parameters
| Parameter | Value | Description | Data Type |
|-|-|-|-|
| user | (not required) | login or email | string |
| password | (required) | password | string |
| email | (not required) | login or email | string |
#### Response
| Code | Description |
|-|-|
| 200 | token |
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
| surname | (not required) | surname and firstname only | string |
| firstname | (not required) | surname and firstname only | string |
| patronymic | (not required) | FIO only | string |
#### Response
| Code | Description |
|-|-|
| 200 | Created |
| 500 | Failed |
