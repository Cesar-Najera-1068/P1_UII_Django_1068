# P1_UII_Django_1068
Configuraciones basicas para trabajar con el framework de Django.
## Procedimiento
 1. Crear carpeta de trabajo (Central de camiones)Luna Turquesa1068
 2. Abrir con VS Code la carpeta
 3. Abrir terminal de VS Code
 4. Verificar que esta python y su version en terminal --> python --version
 5. Link VS Code Django --> https://code.visualstudio.com/docs/python/tutorial-django
 6. Crear el entorno de trabajo --> py -3 -m venv .venv .venv\scripts\activate
 7. Activar el entorno de trabajo --> .venv\scripts\activate.bat
 8. Seleccionar interprete de python --> Presione F1
 9. Actualizar Pip --> python -m pip install --upgrade pip
 10. Instalar Django --> python -m pip install django
 11. Creando el proyecto --> django-admin startproject web_project .
 12. Realizar migracion al proyecto --> python manage.py migrate
 13. Ejecutar el servidor --> python manage.py runserver
     Me trabajo el proyecto http://127.0.0.1:8000/
