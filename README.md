# TurnedUp - Plataforma de Música.
Trabajo integrador Programación-01 UdeSA/DigitalHouse.

Aplicación web para explorar música en tiempo real integrada con la API de Deezer (es así que, para que esta funcione se debe descargar y correr el código y luego requerir permiso en el siguiente link: https://cors-anywhere.herokuapp.com/https://api.deezer.com/chart). Permite descubrir canciones, álbumes y artistas del chart global, reproducir previews directamente en el navegador y armar una playlist personalizada.

Funcionalidades:
Home con ranking de canciones, álbumes y artistas del chart global en tiempo real
Búsqueda de música con resultados por canción, álbum y artista, e ítems recomendados en pantalla de resultados
Vista de detalle por canción, álbum y artista con reproductor embebido de Deezer
Explorador de géneros con artistas asociados a cada uno
Playlist personal con persistencia en localStorage y opción de limpiar favoritos
Validación de formulario de búsqueda en el cliente

Tecnologías y herramientas evaluadas:
Frontend: HTML5, CSS3, JavaScript ES6 (vanilla, sin frameworks)
Consumo de APIs: Fetch API, Deezer REST API (charts, búsqueda, tracks, álbumes, artistas, géneros)
Navegación entre vistas: URLSearchParams para paso de parámetros entre páginas HTML
Persistencia: Web Storage API (localStorage) para gestión de playlist
Reproductor: Deezer Widget embebido via <iframe>
Proxy CORS: cors-anywhere para resolución de restricciones cross-origin
