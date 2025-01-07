# Game Wishlist App

## Descripción
Game Wishlist App es una aplicación web y móvil que permite a los usuarios gestionar una lista de videojuegos. Los usuarios pueden:
- Agregar videojuegos que quieren jugar o han jugado.
- Ordenar juegos por género o año de lanzamiento.
- Puntuar juegos con estrellas.
- Configurar recordatorios para lanzamientos futuros.

## Tecnologías
Este proyecto utiliza las siguientes tecnologías:
- **Frontend Web**: React
- **Frontend Móvil**: React Native
- **Backend**: Node.js con Express
- **Base de Datos**: PostgreSQL

## Funcionalidades principales
- Gestión de usuarios con registro e inicio de sesión (incluyendo OAuth).
- Creación y gestión de listas personalizadas de videojuegos.
- Búsqueda y filtrado de videojuegos.
- Puntuaciones y recordatorios.

## Requisitos previos
Antes de empezar, asegúrate de tener instalados:
- Node.js y npm/yarn
- PostgreSQL
- Git

## Instalación
1. Clona este repositorio:
   ```
   git clone https://github.com/jiyo101/game-wishlist-app.git
   ```
2. Accede al directorio del proyecto:
   ```
   cd game-wishlist-app
   ```
3. Configura las dependencias del backend:
   - Ve al directorio del backend:
   ```
   cd backend
   ```
   - Instala las dependencias:
   ```
   npm install
   ```
4. Configura las dependencias del frontend:
   - Ve al directorio del frontend:
   ```
   cd ../frontend
   ```
   - Instala las dependencias:
   ```
   npm install
   ```

## Uso
1. Configura la base de datos:
   - Crea un archivo .env en el directorio del backend con las credenciales de tu base de datos. Ejemplo:
   ```
   DB_HOST=localhost
   DB_PORT=5432
   DB_USER=tu_usuario
   DB_PASSWORD=tu_contraseña
   DB_NAME=game_wishlist
   ```
2. Inicia el backend:
   - Ve al directorio del backend (si no estás ya ahí):
   ```
   cd backend
   ```
   - Inicia el servidor:
   ```
   npm start
   ```
3. Inicia el frontend:
   - Ve al directorio del frontend:
   ```
   cd ../frontend
   ```
   - Inicia la aplicación:
   ```
   npm start
   ```

## Organización del proyecto
El proyecto está dividido en los siguientes directorios:
- **`backend/`**: Contiene el código del servidor y la API.
- **`frontend/`**: Contiene el código del cliente web.
- **`mobile/`**: (Opcional) Contendrá el código de la app móvil si decides desarrollarla.

## Contribución
Si deseas contribuir, abre un issue o envía un pull request. ¡Toda ayuda es bienvenida!

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.












   
