# Оглавление
1. [Users](#Users)
    1. [UsersAdd](#UsersAdd)
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
