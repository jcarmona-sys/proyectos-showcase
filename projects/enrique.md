# Enrique

Bot musical multiusuario para Discord con reproduccion, comandos slash,
lenguaje natural, notas de voz, TTS en espanol, memoria y estadisticas.

Repositorio original: `jcarmona-sys/enrique`  
Visibilidad del codigo: privado

## Funcionalidades

- Entrada automatica al canal de voz del usuario.
- Busqueda por cancion, artista, enlace YouTube y fuentes compatibles.
- Resolucion de enlaces Spotify mediante metadatos y busqueda equivalente.
- Cola independiente por servidor.
- Pausa, reanudacion, siguiente, anterior, repeticion y salida.
- Historial de canciones.
- Embed Now Playing con miniatura, duracion, solicitante y estado.
- Comandos slash y solicitudes escritas en lenguaje natural.
- Transcripcion local de notas de voz con Vosk.
- Escucha continua opcional tras entrar al canal.
- TTS configurable en espanol.
- Memoria personal, gustos musicales, cumpleanos y estadisticas.
- Permisos antiabuso por canal, rol o permisos de servidor.

## Captura

![Vista funcional de Enrique](../assets/screenshots/enrique/overview.png)

## Comandos representativos

| Comando | Uso |
| --- | --- |
| `/unete` | Entrar al canal de voz |
| `/reproducir` | Buscar o agregar musica |
| `/pausar` / `/reanudar` | Control de reproduccion |
| `/siguiente` / `/anterior` | Navegar cola e historial |
| `/cola` | Consultar canciones pendientes |
| `/enrique` | Solicitud escrita en lenguaje natural |
| `/voz` | Solicitud dictada mediante archivo |
| `/perfil` | Estadisticas personales |
| `/anotar` / `/notas` | Memoria personal |

## Stack

| Area | Tecnologia |
| --- | --- |
| Bot | Python, discord.py |
| Audio | yt-dlp, FFmpeg |
| Voz | Vosk, TTS configurable |
| Datos | SQLite local |
| Calidad | Diagnostico y pruebas unitarias |

## Seguridad

El bot requiere token de Discord y configuracion por entorno. La ficha publica
no incluye tokens, logs, memoria local ni datos de servidores.
