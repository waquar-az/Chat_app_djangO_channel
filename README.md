# Chat_app_djangO_channel for code go to master branch 


This is a chat application based on Django framework.We use Channnels,Redis,Websocket in this project.

Let Folder-Nmae=Waquar

#git init,git status

#setup explian

Waquar> python -m venv env

Waquar>cd env/Scripts

waquar\env\Scripts>

Waquar\env\Scripts\avtivate OR Waquar\env\scripts> Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned

Waquar\env\scripts>.\activate

#virtual environment activited. {env}

{env} Waquar\env\Scripts>

#install django

{env} Waquar\env\Scripts>pip install django

{env} Waquar\env\Scripts>python -m pip install -U channels['daphne']

{env} Waquar\env\Scripts>pip install channels-redis

{env} Waquar\env\Scripts> django-admin startproject Chatweb

{env} Waquar\env\Scripts> cd Chatweb

{env} Waquar\env\Scripts\Chatweb>

{env} Waquar\env\Scripts\Chatweb>django-admin startapp chatapp

#create model for database and migrate

{env} Waquar\env\Scripts\Chatweb>py manage.py makemigrations

{env} Waquar\env\Scripts\Chatweb>py manage.py migrate

#createsuperuser

{env} Waquar\env\Scripts\Chatweb>py manage.py createsuperuser

{env} Waquar\env\Scripts\Chatweb>py manage.py runserver

#push code

git add .

git commit -m 'changes commited'

git branch

git remote add origin http

git push

![Screenshot (886)](https://github.com/waquar-az/Chat_app_djangO_channel/assets/106869966/9a695b04-6579-415a-a706-d2ca734b47bf)


![Screenshot (892)](https://github.com/waquar-az/Chat_app_djangO_channel/assets/106869966/ad1239e0-ee24-4cc6-98b6-cb49d089f5f3)

