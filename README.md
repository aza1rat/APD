# Оглавление
1. [Users](#Users)
	1. [UsersAdd](#UsersAdd)
# Users
## UsersAdd
### :orange_book: `PUT` **users/add** 
Добавление нового пользователя
#### Parameters

| Parameter | Value | Description | Data Type |
|-|-|-|-|
| user | (required) | login | string |
| password | (required) | password | string |
| email | (required) | email | string |
| surname & firstname | (not required) | surname | string |
| surname & firstname | (not required) | firstname | string |
| surname & firstname & patronymic | (not required) | patronymic | string |
#### Responce
| Code | Description |
|-|-|
| 200 | Created|
| 500 | Failed |
