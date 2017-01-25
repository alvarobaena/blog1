# blog1

django-admin startproject mysite

python manage.py migrate

python manage.py runserver

//python manage.py createsuperuser

python manage.py startapp 'app'

En mysite/settings.py añadir la app instalada.

En 'app'/models.py añadimos el modelo.

python manage.py makemigrations 'app'

python manage.py migrate 'app'

En 'app'/admin.py añadir con import el modelo.

Mirar mysite/urls.py y configurar con 'app'

Y en 'app'/urls.py añadimos las urls de las views

Posteriormente añadimos las vistas

Y creamos el .html correspondiente
