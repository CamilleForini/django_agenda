Iniciar o projeto Django

```
python -m venv venv
venv\Scripts\activate
pip install django
django-admin startproject project .
python manage.py startapp contact
python manage.py runserver
D:\Meus_Documentos\Documents\PROGRAMAÇÃO\python_codes\django_agenda
```

Configurar o git

```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT
```
python manage.py makemigrations
python manage.py migrate