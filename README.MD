#Новостной портал
Это новостной портал в котором можно читать и выкладывать новости

#Описание
Сайт созданый с помощью Flask

#Как начать
1. Склонировать репозиторию
2. Запустить виртуальное окружение
```commandline
python -m venv venv
source venv/Scripts/activate
```
3. Установить requirements.txt
```commandline
pip install requiremenrs.txt
```
4. Создать файл .env и указать настройки
```commandline
DATABASE_URI = sqlite:///db.sqlite3
SECRET_KEY = 'SECRET_KEY'
```

5. Запустить Flask
```commandline
flask run
```