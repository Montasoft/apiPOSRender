# apiPOS
desarrollo de un backend para un sistema de punto de venta POS

Crear el entorno virtual
    python3 -m venv env

Activar el entorno virtual
    source env/bin/activate


Instalar requiremen.txt
    pip install -r requirements.txt

Crear migraciones
    python manege.py makemigrations
    python manege.py migrate

Crear el superusuario
    python manage.py createsuperuser
    ingresar nombre y contraseña

ejecutar el servidor
    python manage.py runserver
    