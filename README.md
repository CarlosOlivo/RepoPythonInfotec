# Sistema de Login en Flask — RepoPythonInfotec

Este proyecto es una aplicación web sencilla de inicio de sesión desarrollada con Flask. Está diseñada para ser clara, moderna y fácil de modificar, ideal para demostraciones, pruebas o aprendizaje de autenticación básica en Python.

## Características principales

- **Autenticación en memoria:** Los usuarios están definidos en el código, no se utiliza base de datos.
- **Interfaz moderna y responsiva:** Incluye modo oscuro, iconos y fuentes modernas.
- **Gestión de sesión:** Al iniciar sesión, se guarda el usuario en la sesión de Flask.
- **Mensajes flash:** Notificaciones para éxito, error y cierre de sesión.
- **Cache busting:** Los archivos estáticos se actualizan automáticamente en el navegador.
- **Código y comentarios en español.**

## Estructura del proyecto

```
RepoPythonInfotec/
│
├── app.py                  # Aplicación principal Flask, rutas y lógica
├── requirements.txt        # Dependencias (solo Flask)
├── static/
│   ├── style.css           # Estilos personalizados y modo oscuro
│   └── bg-highres.svg      # Imagen de fondo
├── templates/
│   ├── login.html          # Formulario de login con modo oscuro
│   └── welcome.html        # Página de bienvenida tras login
├── README.md               # Este archivo
├── GITHUB_GUIDE.md         # Guía rápida de uso de Git/GitHub
└── Prompts.md              # Ejemplos y prompts para Copilot
```

## Cómo funciona

1. **Usuarios:** Definidos en el diccionario `USERS` dentro de `app.py`. Ejemplo:
   ```python
   USERS = {
   	 "usuario1": {"password": "1234", "email": "usuario1@email.com"},
   	 ...
   }
   ```
2. **Login:** El usuario ingresa su nombre y contraseña en `login.html`. Si son correctos, se guarda en la sesión y se redirige a `welcome.html`.
3. **Sesión:** Se utiliza `Flask session` para mantener el usuario autenticado.
4. **Logout:** El usuario puede cerrar sesión, eliminando sus datos de la sesión.
5. **Mensajes:** Se muestran mensajes de éxito o error usando `flash`.

## Instalación y ejecución

1. Instala las dependencias:
   ```powershell
   pip install -r requirements.txt
   ```
2. Ejecuta la aplicación:
   ```powershell
   python app.py
   ```
3. Abre tu navegador en [http://localhost:5000](http://localhost:5000)

## Personalización

- **Agregar usuarios:** Edita el diccionario `USERS` en `app.py`.
- **Modificar estilos:** Edita `static/style.css`.
- **Cambiar textos o estructura:** Modifica los archivos en `templates/`.

## Credenciales de ejemplo

Consulta el archivo `README.md` original o el código en `app.py` para ver los usuarios y contraseñas disponibles.

## Notas

- El proyecto es solo para demostración. No usar en producción.
- La clave secreta está hardcodeada por simplicidad.
- No hay registro de usuarios ni recuperación de contraseña.
