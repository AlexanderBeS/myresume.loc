# myresume.loc

Сервис по созданию резюме.

## Страницы

1. Аутентификация.
2. Регистрация.
3. Главная страница.
4. Страница просмотра своих резюме.
5. Страница просмотра одного резюме.
6. Страница редактирования резюме.
7. Страница просмотра всех резюме (даже удаленных).

## Роли:

Guest, User, Admin.

## Права и доступ:

### Guest:

1. Просмотр главной страницы.
2. Страница авторизации/регистрации.

### User:

1. Просмотр созданных резюме.
2. Создание резюме.
3. Редактирование резюме.
4. Удаление резюме.
5. Скачать резюме в pdf формате.

### Admin:

1. Просмотр всех резюме (даже удаленных).
2. Редактирование не удаленных резюме.
3. Восстановление удаленного резюме.
4. Полное удаление резюме.
 
## Таблицы в БД:

![Image alt](https://github.com/AlexanderBeS/myresume.loc/blob/master/screenshots/db.PNG)

## Некоторые ф-ции:

1. Пункты в меню разделяются по доступности на 3 вида: Guest, User, Admin.
2. Настроен вывод ошибок при создании или редактировании резюме.
3. Настроена подгрузка данных в форму, которые были в форме до ошибки.
4. Валидация полей ввода.
5. При регистрации пользователю ему автоматически присваивается группа User.

## Роуты

![Image alt](https://github.com/AlexanderBeS/myresume.loc/blob/master/screenshots/routes.PNG)


## Пример ссылок:

<p>
<br>http://myresume.loc/
<br>http://myresume.loc/login
<br>http://myresume.loc/register
<br>http://myresume.loc/logout
<br>http://myresume.loc/resumes
<br>http://myresume.loc/resumes/1
<br>http://myresume.loc/resumes/1/edit
<br>http://myresume.loc/resumes/create
<br>http://myresume.loc/resumes/admin/all
<br>http://myresume.loc/resumes/download/1
</p>



## Api

### Вывод всех резюме:

![Image alt](https://github.com/AlexanderBeS/myresume.loc/blob/master/screenshots/apigetallresumes.PNG)


### Вывод одного резюме:

![Image alt](https://github.com/AlexanderBeS/myresume.loc/blob/master/screenshots/apiget1resume.PNG)

### Удаление резюме

![Image alt](https://github.com/AlexanderBeS/myresume.loc/blob/master/screenshots/apiresumedelete.PNG)
