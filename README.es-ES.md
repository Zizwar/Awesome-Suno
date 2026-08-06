

# Awesome Suno [![Awesome](https://awesome.re/badge.svg)]([https://awesome.re](https://github.com/Zizwar/Awesome-Suno))

> Una lista curada de proyectos increíbles de código abierto relacionados con Suno AI, la innovadora plataforma de generación musical.

## Contenido

- [Introducción](#introducción)
- [Lista de Proyectos](#lista-de-proyectos)
  - [Python](#python)
  - [TypeScript/JavaScript](#typescriptjavascript)
  - [Go](#go)
  - [C++](#c)
  - [C#](#c-1)
  - [PHP](#php)
  - [Dart](#dart)
  - [Otros](#otros)
- [Herramientas, Servicios y Aplicaciones Web](#herramientas-servicios-y-aplicaciones-web)
- [Recursos Adicionales](#recursos-adicionales)
- [Cómo Contribuir](#cómo-contribuir)

## Introducción

Suno AI está revolucionando la industria de la música con sus avanzadas capacidades de generación musical impulsadas por IA. Esta lista tiene como objetivo recopilar los mejores proyectos de código abierto relacionados con Suno AI, proporcionando a desarrolladores y entusiastas recursos valiosos para explorar, contribuir y desarrollar sobre esta emocionante tecnología.

## Lista de Proyectos

### Python
- [danny-englander/suno-ai-downloader](https://github.com/danny-englander/suno-ai-downloader) - Un kit de herramientas de descarga robusto que cuenta con procesamiento paralelo (hilos) para acelerar las exportaciones masivas. Preserva de forma única los metadatos de las canciones (prompts, versiones del modelo) en archivos de texto de respaldo y gestiona la organización de archivos con nombres estructurados.
- [sergio11/lyric_wave_architecture](https://github.com/sergio11/lyric_wave_architecture) - Una plataforma experimental de composición musical con IA que orquesta múltiples modelos. Integra Suno-AI Bark para clonación de voz con AudioCraft para melodías y Stable Diffusion para portadas de álbumes, gestionada mediante DAGs de Apache Airflow. Una plantilla para flujos de trabajo complejos de medios generativos.
- [WaveGenAI/phonira](https://github.com/WaveGenAI/phonira) - Una implementación de modelo de código abierto basada en MusicGen. Aunque no es un cliente directo de Suno, se utiliza frecuentemente en el ecosistema Suno para el postprocesamiento y la extensión de las capacidades de audio generadas por IA.
- [SocAIty/SpeechCraft](https://github.com/SocAIty/SpeechCraft) - Una biblioteca para texto a voz y clonación de voz utilizando el modelo Suno Bark.
- [Goapiai/Suno-API](https://github.com/Goapiai/Suno-API) - Una API simple y rápida para integrar con Suno AI en aplicaciones de IA.
- [SunoAI-API/Suno-API](https://github.com/SunoAI-API/Suno-API) - Una API no oficial de Suno AI basada en Python y FastAPI. Actualmente admite la generación de canciones, letras, etc.
- [yihong0618/SunoSongsCreator](https://github.com/yihong0618/SunoSongsCreator) - Generación de canciones de alta calidad utilizando https://www.suno.ai/. API de ingeniería inversa.
- [Malith-Rukshan/Suno-API](https://github.com/Malith-Rukshan/Suno-API) - Biblioteca API de Python no oficial y API REST para Suno.ai --- ¡Crea música con IA generativa!
- [imyizhang/Suno-API](https://github.com/imyizhang/Suno-API) - API no oficial para Suno AI: crea una canción con Suno usando la v3.
- [SunoApi/SunoApi](https://github.com/SunoApi/SunoApi) - SunoAPI Cliente no oficial de Suno AI, actualmente admite la generación de música, acceso a información musical y otras funciones.
- [bradsec/barkwebui](https://github.com/bradsec/barkwebui) - Una interfaz web basada en Python Flask diseñada para facilitar la generación de texto a voz utilizando Bark de Suno AI.
- [Malith-Rukshan/Suno-AI-BOT](https://github.com/Malith-Rukshan/Suno-AI-BOT) - Bot de Telegram para la generación de música con IA basado en la API de Suno. Ejemplo para la biblioteca Python de SunoAI.
- [SatyrDiamond/suno-dl](https://github.com/SatyrDiamond/suno-dl) - Descargador de Suno AI
- [cmathgit/ai-gospel-music-api](https://github.com/cmathgit/ai-gospel-music-api) - Uso de IA para generar canciones de evangelio bíblicamente precisas, entre otros géneros, y vídeos musicales.
- [qu-gg/suno-ai-radio](https://github.com/qu-gg/suno-ai-radio) - Demostración de concepto (POC) simple usando Selenium y OBS para alojar una estación de radio con IA donde cada canción se genera sobre la marcha usando Suno.
- [Alpaca4610/nonebot-plugin-suno](https://github.com/Alpaca4610/nonebot-plugin-suno) - Plugin de composición de Suno AI para uso personal.
- [GentlemanHu/ComfyUI-SunoAI](https://github.com/GentlemanHu/ComfyUI-SunoAI) - Envoltorio de nodo ComfyUI para la API de SunoAI
- [musa-atlihan/sunoai-bark](https://github.com/musa-atlihan/sunoai-bark) - Contenedor Docker para el modelo suno-ai bark
- [EA914/Suno-AI-Prompt-Dictation](https://github.com/EA914/Suno-AI-Prompt-Dictation) - Programa Python que permite dictar un prompt y luego genera canciones de Suno AI basadas en la transcripción de ese prompt.
- [TheProof68/music-ai-base](https://github.com/TheProof68/music-ai-base) - Genera música con IA (sistema GPT), versión básica con planes para avanzar, como suno.ai

### TypeScript/JavaScript
- [elizaos-plugins/plugin-suno](https://github.com/elizaos-plugins/plugin-suno) - Un plugin dedicado para el  `ElizaOS`. Permite a los agentes de IA generar música de forma autónoma, extender pistas y gestionar parámetros de generación personalizados (etiquetas, estilo) mediante conversaciones o autoactivadores.
- [zh30/get-suno-lyric](https://github.com/zh30/get-suno-lyric) - Una extensión de Chrome especializada para extraer letras sincronizadas de Suno. Intercepta datos de letras para exportar archivos .lrc y .srt, permitiendo la creación de vídeos de karaoke o contenido musical traducido.
- [QosmoInc/Spot-if-AI](https://github.com/QosmoInc/Spot-if-AI) - Una herramienta de detección en el navegador para analizar pistas de Spotify. Utiliza el modelo SONICS a través de ONNX Runtime para estimar la probabilidad de que una canción haya sido generada por Suno o Udio.
- [blib-la/bark-web-ui](https://github.com/blib-la/bark-web-ui) - Una interfaz web construida con Next.js para experimentar con el modelo Bark directamente desde el navegador.
- [stefanionescu/suno-music-discord-bot](https://github.com/stefanionescu/suno-music-discord-bot) - Un bot para Discord que transforma imágenes y vídeos en canciones usando Suno AI.
- [gcui-art/suno-api](https://github.com/gcui-art/suno-api) - Utiliza una API para llamar a la IA de generación musical de suno.ai e integrarla fácilmente en agentes como GPTs.
- [Alvin-Liu/suno-music-generator](https://github.com/Alvin-Liu/suno-music-generator) - Un sitio web de creación musical rápida basado en texto con suno.ai.
- [tsui66/suno-ai-music](https://github.com/tsui66/suno-ai-music) - Descargador de música Suno y Generador de MV musicales.
- [MelohubAI/suno-ai-proxy](https://github.com/MelohubAI/suno-ai-proxy) - API nodejs no oficial de Suno AI
- [hissincn/suno-ai](https://github.com/hissincn/suno-ai) - Crea canciones de alta calidad de suno.ai mediante API de Javascript.
- [AuYuHui/one-suno](https://github.com/AuYuHui/one-suno) - API de suno.ai
- [Sprheany/ai-song](https://github.com/Sprheany/ai-song) - Un sitio web de música con IA desarrollado con Next.js y Suno AI.
- [jontonsoup4/suno-clone](https://github.com/jontonsoup4/suno-clone) - Un clon de la interfaz web de Suno AI usando NextJS y Tailwind
- [Darosss/dc-suno-based-bot](https://github.com/Darosss/dc-suno-based-bot) - Bot de Discord que puede reproducir música de YouTube + Suno AI. (Usar bajo su propio riesgo, hecho por diversión)
- [onlinedear/suno-ai](https://github.com/onlinedear/suno-ai) - Proyecto Suno AI
- [Zizwar/suno-ma](https://github.com/Zizwar/suno-ma) - Suno AI React Native para Android e iOS
- [Zizwar/sunoma](https://github.com/Zizwar/sunoma) - Transmisión en vivo de música de tendencia de Suno AI a YouTube
- [minsixhao/SunoAi](https://github.com/minsixhao/SunoAi) - Interfaz de SunoAi
- [Zizwar/suno-deno](https://github.com/Zizwar/suno-deno) - Suno-Deno es una biblioteca para interactuar con el servicio de generación musical Suno AI, diseñada para Deno

### Go
- [wengchaoxi/one-suno-api](https://github.com/wengchaoxi/one-suno-api) - Una pasarela API unificada y de alto rendimiento para Suno, construida en Go. Agrega múltiples proveedores de API de terceros detrás de una sola interfaz, ofrece balanceo de carga ponderado de 1 por 1 y despliegue con Docker. Ideal para desarrolladores que construyen aplicaciones escalables sobre Suno.
- [hellodword/suno-radio](https://github.com/hellodword/suno-radio) - Convierte las listas de reproducción de Suno en una transmisión de radio musical continua y aleatoria. Genera un flujo OGG compatible con reproductores multimedia estándar y proporciona una API REST para gestionar fuentes de listas de reproducción. Perfecto para crear estaciones de radio con IA autoalojadas.
- [Calcium-Ion/new-api](https://github.com/Calcium-Ion/new-api) - Sistema de gestión y distribución de interfaces de modelos de IA, que admite múltiples modelos grandes para llamadas en formato OpenAI, Midjourney Proxy, Suno, Rerank, compatible con el protocolo de pago fácil.
- [Suno-API/Suno-API](https://github.com/Suno-API/Suno-API) - Esta es una API no oficial de Suno AI basada en Golang. Actualmente admite la generación de canciones, letras, y Chat de OpenAI.

### C++
- [PABannier/bark.cpp](https://github.com/PABannier/bark.cpp) - El modelo Bark de Suno AI en C/C++ para texto a voz rápido
- [azkadev/bark](https://github.com/azkadev/bark) - Biblioteca en desarrollo para texto a voz de Suno AI's Bark en C/C++ para inferencia rápida

### C#
- [GwyrddGlas/Suno-Downloader](https://github.com/GwyrddGlas/Suno-Downloader) - Descarga cualquier canción de suno.ai

### PHP
- [runapi-ai/suno-php](https://github.com/runapi-ai/suno-php) - Un paquete Composer para ejecutar flujos de trabajo de 1 de 1 de Suno, 1 de audio, 1, 1 de 1, y 1 1 a través de RunAPI.
- [YunzhiYike/Suno-SDK](https://github.com/YunzhiYike/Suno-SDK) - Esta es una API no oficial de Suno basada en PHP; admite todas las interfaces de Suno.

### Dart
- [AllenTom/SunoGenerator](https://github.com/AllenTom/SunoGenerator) - Un cliente de Suno para utilizar 1 1 1 1

### Otros
- [kesperinc/suno-ai_bark](https://github.com/kesperinc/suno-ai_bark) - Cuaderno Jupyter para Suno AI Bark
- [pawan418/suno-ai](https://github.com/pawan418/suno-ai) - Cuaderno Jupyter para Suno AI
- [AIDM7350/Group-Project-Suno](https://github.com/AIDM7350/Group-Project-Suno) - De 1 a 1: Descubriendo el 1 De Suno AI en 1 De 1
- [Malintha-Senadheera/suno-bark-ai](https://github.com/Malintha-Senadheera/suno-bark-ai) - Cuaderno Jupyter para Suno Bark AI

## Herramientas, Servicios y Aplicaciones Web
- [SunoPrompt.com](https://sunoprompt.com/) - Una herramienta 1 avanzada en la 1 que ayuda a 1 a construir 1 de 1 precisos. Genera entradas estructuradas (1, 1, 1) para maximizar la calidad de las salidas de Suno.
- [Suno Meta Tags Creator](https://sunometatagcreator.com/) - Un constructor de arrastrar y soltar visual para el sistema de metadatos de Suno con más de 1000 etiquetas categorizadas y una línea de tiempo interactiva de estructura de canciones. Incluye letras con IA en 5 idiomas, 1 de audio y 1, 1 de portada y 1 de vídeo musical.
- [Suno Manager](https://chromewebstore.google.com/detail/suno-manager/bhfnejgfonhlaalgnhcphpjbbifidpki) - Una extensión de navegador 1 para 1 grandes 1. Permite 1, 1, y 1 masivo de canciones (MP3/WAV) junto con sus metadatos JSON, 1 1 1 1 en el 1 .
- [HookGenius](https://hookgenius.app) - Un 1 de 1 para 1 de 1 De Suno. Genera letras de canciones completas con etiquetas de estructura, 1 de 1 1, y 1 listos para copiar y pegar en Suno.
- [AIMusixer (AI music maker)](https://suno-ai.me) - Un sitio web para crear música usando Suno a partir de texto o grabaciones de audio.
- [AI Song Generator (Music Maker)](https://musicmaker.im/ai-song-generator/) - Un generador de canciones basado en Suno AI v4 para crear pistas musicales completas a partir de descripciones de texto.
- [Yanyutin753/pictureChange](https://github.com/Yanyutin753/pictureChange) - Plugin para el proyecto chatgpt-on-wechat que, 1 Baidu AI y Stable Diffusion WebUI para 1 de imágenes, 1 1 de 1 de 1, 1 de 1 a imagen e 1 a 1. La 1 De Suno puede 1 y 1 a 1.
- [MuratGuelr/sunoai-music-player](https://github.com/MuratGuelr/sunoai-music-player) - Suno AI - Reproductor de Música en Línea Hecho por Murat Guler
- [Tunova](https://tunova.ai) - Una API alojada de Suno para desarrolladores: genera canciones completas 1 o MCP, asíncrona con 1, 1 solo en 1 1 (1 1 se 1 1). 1 & 1 de Python y Node (`pip install tunova` / `npm i tunova`).

## Recursos Adicionales
- [develephant/suno-songtags](https://github.com/develephant/suno-songtags) - Etiquetas de canciones recopiladas para ayudar a guiar a Suno AI.

## Cómo Contribuir

¡Damos la 1 a la comunidad! Si desea 1 su 1 a esta lista, siga estos pasos:

1. Realice un 1 de este 1 .
2. Añada su proyecto a la sección correspondiente en el archivo `README.md`.
3. Envíe una 1 de 1 con una descripción clara de los cambios que ha realizado.
