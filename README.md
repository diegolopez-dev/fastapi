# API con FastAPI: Autenticación y Registro de Usuario

Este proyecto consiste en una API construida con FastAPI que ofrece funcionalidades de autenticación y registro de usuario. Proporciona endpoints para que los usuarios puedan registrarse, iniciar sesión, realizar otras acciones relacionadas con la autenticación.

## Instalación

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias del proyecto utilizando el comando `pip install -r requirements.txt`.

## Uso

Una vez instaladas las dependencias, puedes iniciar la API ejecutando el archivo 
`main.py`. La API estará disponible en `http://localhost:8000`.

A continuación, se detallan algunos de los endpoints disponibles:

- `POST /users`: Permite ver los usuarios registrados en la plataforma.
- `POST /user/me`: Permite ver a un usuario registrado en la plataforma.
- `POST /login`: Permite a un usuario iniciar sesión y obtener un token JWT.

## Documentación

Para explorar todos los endpoints disponibles y sus respectivas descripciones, puedes acceder a la documentación interactiva de laAPI en `http://localhost:8000/docs`.
