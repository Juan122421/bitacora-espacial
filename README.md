# Bitácora Espacial

Portal de noticias de exploración espacial hecho con React y Vite (JavaScript).
Permite buscar noticias por tema y abrirlas. Todo el diseño sale de un sistema
CSS propio, sin frameworks.

## Cómo correrlo

1. Clona el repositorio e instala las dependencias:

   npm install

2. Copia el archivo de variables de entorno:

   cp .env.example .env

3. Inicia el servidor de desarrollo:

   npm run dev

   Abre http://localhost:5173

## API

Usa la [Spaceflight News API](https://api.spaceflightnewsapi.net/v4/docs/).
Es gratuita y no requiere clave. La URL base se configura en `.env`
con la variable `VITE_API_URL`.