Iniciar o projeto django
````
python -m venv ecommerce
. ecommerce/Scripts/activate
pip install django
pip install django-crispy-forms
pip install pillow
django-admin startproject loja .
````
Configurar o git
````
git config --global user.name 'seunome'
git config --global user.email 'seuemail'
git config --global init.defaultBranch main

#configure o gitignore
git init
````
criando apps
````
python manage.py startapp produto
python manage.py startapp pedido
python manage.py startapp perfil
````
criar super user
````
python manage.py migrate
python manage.py cratesuperuser
````