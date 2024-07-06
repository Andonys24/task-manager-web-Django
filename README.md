# Task Manager Web App

Este es un proyecto de aplicación web para gestionar tareas, desarrollado con Django.

## Características

- **Inicio de Sesión:** Permite a los usuarios registrados iniciar sesión para gestionar sus tareas.
- **Registro de Usuario:** Nuevo usuario puede registrarse para obtener una cuenta.
- **Gestión de Tareas:** Agregar nuevas tareas y ver detalles de cada tarea.
- **Interfaz Responsiva:** Diseño adaptable para su uso en dispositivos móviles y de escritorio.

## Tecnologías Utilizadas

- **Backend:** Python, Django
- **Frontend:** HTML, CSS (usando plantillas Django)
- **Base de Datos:** SQLite (por defecto en Django)

## Instalación

Para ejecutar esta aplicación localmente, sigue estos pasos:

1. Clona este repositorio:

   ```bash
   git clone https://github.com/Andonys24/task-manager-web-Django.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd task-manager-web-Django
   ```

3. Instala las dependencias necesarias:

   ```bash
   pip install -r requirements.txt
   ```

4. Aplica las migraciones a la base de datos:

   ```bash
   python manage.py migrate
   ```

5. Inicia el servidor local:

   ```bash
   python manage.py runserver
   ```

6. Accede a la aplicación en tu navegador web: `http://localhost:8000/`

## Estructura del Proyecto

La estructura básica del proyecto es la siguiente:

```
proyectoweb/
├── base/
│   ├── migrations/
│   │   ├── 0001_initial.py
│   │   └── __init__.py
│   ├── static/
│   │   └── css/
│   │       └── principal.css
│   ├── templates/
│   │   └── base/
│   │       ├── login.html
│   │       ├── principal.html
│   │       ├── registro.html
│   │       ├── tarea.html
│   │       ├── tarea_confirm_delete.html
│   │       ├── tarea_form.html
│   │       └── tarea_list.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── __init__.py
├── proyectoweb/
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── __init__.py
├── db.sqlite3
├── manage.py
└── requirements.txt

```

## Autor

Desarrollado por [Andonys24](https://github.com/Andonys24).