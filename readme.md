**Idea del Proyecto:**

Kamazon es un proyecto de programación diseñado para el aprendizaje universitario, inspirado en la idea de negocio de Amazon. El proyecto se enfoca en la creación de una aplicación web que permita a los usuarios registrados comprar productos de diversas categorías, así como a los vendedores publicar productos y gestionar sus ventas.

---
**Colaboradores:**
- [Christian Pin](https://github.com/Crisblue1324) 
- [Roger Cornejo](https://github.com/Rcornejom06/)
---
**Tecnologias Utilizadas:**
- Python
- Django
- HTML
- Tailwind CSS
- JavaScript
---
**Instalacion:**
1. Clonar el repositorio
```bash
git clone https://github.com/aterana3/Kamazon-Proyecto-6to-semestre.git
```
2. Instalar las dependencias
```bash
pip install -r dependencias.txt
```
3. Crear database en postgres
4. Configurar el archivo settings.py
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': '{nombre de la base de datos}',
        'USER': '{usuario}',
        'PASSWORD': '{contraseña}',
        'HOST': '{host}',
        'PORT': '{puerto}',
    }
}
```
5. Crear migraciones
```bash
python manage.py makemigrations / python manage.py makemigrations <app_name>
python manage.py migrate
```
6. Crear superusuario
```bash
python manage.py createsuperuser
```
7. Correr el servidor
```bash
python manage.py runserver 0.0.0.0:8000
```
8. Librerias para la IA
```bash
pip install numpy
pip install nltk
pip install tensorflow
pip install keras
```