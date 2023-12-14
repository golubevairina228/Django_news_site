Creation of a news site
=======================

Requirements
---------------
asgiref==3.7.2

Django==4.2.7

django-taggit==5.0.1

Pillow==10.1.0

sqlparse==0.4.4

typing_extensions==4.8.0

tzdata==2023.3

Launch
------------

pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver

Review
-------------
После запуска мы можем либо зарегистрироваться на странице /news/register/, либо войти в профиль, если он уже существует на странице /news/login/.

<img width="552" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/44db30df-2ac7-481a-9ac1-9dbe70a846da">

<img width="567" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/0795aacd-a7c8-490d-94b7-051db3c49eab">

После этого мы попадаем на главную страницу, где можем посмотреть новости, редактировать свои новости, поделиться новостью, оставить комментарий или выйти из аккаунта.

<img width="940" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/e6a85668-838d-4031-8bdb-99ea3176db25">

На главной странице показываются последние 5 новостей, а остальные на следующих страницах.

<img width="944" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/c8da3b77-0eed-4073-a031-1af5107d5143">

Админ может создавать новые новости и редактировать новости всех пользователей(как на самом сайте, так и в Django-админке.

<img width="955" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/5554e2b9-cab4-4ddf-9390-831eda8763f1">

<img width="946" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/3edecf77-4b4d-4efe-9221-3536deffebd4">

<img width="927" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/48091ce6-bad5-454d-9cf9-a9d9870b4db6">


Новость выглядит следующим образом:

<img width="938" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/f4cf40c8-209d-42f3-9f2e-c6649c7e7e34">


У всех новостей есть тег, можно осуществить поиск по какому-либо тегу.

<img width="951" alt="image" src="https://github.com/golubevairina228/Django_news_site/assets/67825357/82af2846-894c-4df6-9a1c-fa68925785ff">


