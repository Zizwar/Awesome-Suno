# Awesome Suno [![Awesome](https://awesome.re/badge.svg)]([https://awesome.re](https://github.com/Zizwar/Awesome-Suno))

> A curated list of awesome open-source projects related to Suno AI, the innovative music generation platform.

## Contents

- [Introduction](#introduction)
- [List of Projects](#list-of-projects)
  - [Python](#python)
  - [TypeScript/JavaScript](#typescriptjavascript)
  - [Go](#go)
  - [C++](#c)
  - [C#](#c-1)
  - [PHP](#php)
  - [Dart](#dart)
  - [Other](#other)
- [Web Tools, Services and Applications](#web-tools-services-and-applications)
- [Additional Resources](#additional-resources)
- [How to Contribute](#how-to-contribute)

## Introduction

Suno AI is revolutionizing the music industry with its advanced AI-powered music generation capabilities. This list aims to gather the best open-source projects related to Suno AI, providing developers and enthusiasts with valuable resources to explore, contribute, and build upon this exciting technology.

## List of Projects

### Python
- [danny-englander/suno-ai-downloader](https://github.com/danny-englander/suno-ai-downloader) - A robust downloader toolkit featuring parallel processing (threading) for accelerated bulk exports. Uniquely, it preserves song metadata (prompts, model versions) in sidecar text files and handles file organization with structured naming.
- [sergio11/lyric_wave_architecture](https://github.com/sergio11/lyric_wave_architecture) - An experimental AI music composition platform that orchestrates multiple models. It integrates Suno-AI Bark for voice cloning with AudioCraft for melody and Stable Diffusion for cover art, managed via Apache Airflow DAGs. A blueprint for complex generative media workflows.
- [WaveGenAI/phonira](https://github.com/WaveGenAI/phonira) - An open-source audio model implementation based on MusicGen. While not a direct Suno client, it is frequently used in the Suno ecosystem for post-processing and extending AI-generated audio capabilities.
- [SocAIty/SpeechCraft](https://github.com/SocAIty/SpeechCraft) - A library for text-to-speech and voice cloning using the Suno Bark model.
- [Goapiai/Suno-API](https://github.com/Goapiai/Suno-API) - A simple and fast API for integrating with Suno AI in AI applications.
- [SunoAI-API/Suno-API](https://github.com/SunoAI-API/Suno-API) - An unofficial Suno AI API based on Python and FastAPI. It currently supports generating songs, lyrics, etc.
- [yihong0618/SunoSongsCreator](https://github.com/yihong0618/SunoSongsCreator) - High quality songs generation using https://www.suno.ai/. Reverse engineered API.
- [Malith-Rukshan/Suno-API](https://github.com/Malith-Rukshan/Suno-API) - SunoAI Unofficial Python API Library and REST API for Suno.ai --- Create Music with Generative AI!
- [imyizhang/Suno-API](https://github.com/imyizhang/Suno-API) - Unofficial API for Suno AI: make a song with Suno using v3.
- [SunoApi/SunoApi](https://github.com/SunoApi/SunoApi) - SunoAPI Unofficial Suno AI client, currently supports the generation of music, access to music information and other functions.
- [bradsec/barkwebui](https://github.com/bradsec/barkwebui) - A Python Flask-based web UI designed to facilitate the generation of text-to-speech using Suno AI's Bark.
- [Malith-Rukshan/Suno-AI-BOT](https://github.com/Malith-Rukshan/Suno-AI-BOT) - Suno API Based AI Music Generator Telegram Bot. Example for SunoAI Python Library.
- [SatyrDiamond/suno-dl](https://github.com/SatyrDiamond/suno-dl) - Suno AI Downloader
- [cmathgit/ai-gospel-music-api](https://github.com/cmathgit/ai-gospel-music-api) - Using AI to generate biblically accurate gospel songs, among other genres, and music videos.
- [qu-gg/suno-ai-radio](https://github.com/qu-gg/suno-ai-radio) - Simple POC using Selenium and OBS to host an AI radio station where each song is generated on-the-fly using Suno.
- [Alpaca4610/nonebot-plugin-suno](https://github.com/Alpaca4610/nonebot-plugin-suno) - Self-use Suno AI composition plugin.
- [GentlemanHu/ComfyUI-SunoAI](https://github.com/GentlemanHu/ComfyUI-SunoAI) - ComfyUI Node wrapper of SunoAI API
- [musa-atlihan/sunoai-bark](https://github.com/musa-atlihan/sunoai-bark) - Docker container for suno-ai bark model
- [EA914/Suno-AI-Prompt-Dictation](https://github.com/EA914/Suno-AI-Prompt-Dictation) - Python program that allows you to dictate a prompt and then generates songs from Suno AI based on the transcription of that prompt.
- [TheProof68/music-ai-base](https://github.com/TheProof68/music-ai-base) - Generate music with AI (GPT system), basic version with plans to advance like suno.ai

### TypeScript/JavaScript
- [elizaos-plugins/plugin-suno](https://github.com/elizaos-plugins/plugin-suno) - A dedicated plugin for the ElizaOS agent framework. Enables AI agents to autonomously generate music, extend tracks, and manage custom generation parameters (tags, style) through conversation or self-triggers.
- [zh30/get-suno-lyric](https://github.com/zh30/get-suno-lyric) - A specialized Chrome extension for extracting synchronized lyrics from Suno. It intercepts lyric data to export .lrc and .srt files, enabling the creation of karaoke videos or translated music content.
- [QosmoInc/Spot-if-AI](https://github.com/QosmoInc/Spot-if-AI) - A browser-based detection tool for analyzing Spotify tracks. It uses the SONICS model via ONNX Runtime to estimate the probability that a song was generated by Suno or Udio.
- [blib-la/bark-web-ui](https://github.com/blib-la/bark-web-ui) - A web interface built with Next.js to experience the Bark model directly from the browser.
- [stefanionescu/suno-music-discord-bot](https://github.com/stefanionescu/suno-music-discord-bot) - A Discord bot that transforms images and videos into songs using Suno AI.
- [gcui-art/suno-api](https://github.com/gcui-art/suno-api) - Use API to call the music generation AI of suno.ai, and easily integrate it into agents like GPTs.
- [Alvin-Liu/suno-music-generator](https://github.com/Alvin-Liu/suno-music-generator) - A text-based rapid music creation website based on suno.ai.
- [tsui66/suno-ai-music](https://github.com/tsui66/suno-ai-music) - Suno Music Downloader & Music MV Generator.
- [MelohubAI/suno-ai-proxy](https://github.com/MelohubAI/suno-ai-proxy) - Unofficial Suno AI nodejs API
- [hissincn/suno-ai](https://github.com/hissincn/suno-ai) - Create high quality songs from suno.ai by Javascript API.
- [AuYuHui/one-suno](https://github.com/AuYuHui/one-suno) - suno.ai API
- [Sprheany/ai-song](https://github.com/Sprheany/ai-song) - An AI music website developed based on Next.js and Suno AI.
- [jontonsoup4/suno-clone](https://github.com/jontonsoup4/suno-clone) - A clone of the Suno AI website UI using NextJS and Tailwind
- [Darosss/dc-suno-based-bot](https://github.com/Darosss/dc-suno-based-bot) - Discord bot that can play music from YouTube + Suno AI. (Use at own risk, made for fun)
- [onlinedear/suno-ai](https://github.com/onlinedear/suno-ai) - Suno AI project
- [Zizwar/suno-ma](https://github.com/Zizwar/suno-ma) - Suno AI React Native for Android and iOS
- [Zizwar/sunoma](https://github.com/Zizwar/sunoma) - Livestream trend music from Suno AI to YouTube
- [minsixhao/SunoAi](https://github.com/minsixhao/SunoAi) - SunoAi interface
- [Zizwar/suno-deno](https://github.com/Zizwar/suno-deno) - Suno-Deno is a library for interacting with the Suno AI music generation service, designed for Deno

### Go
- [wengchaoxi/one-suno-api](https://github.com/wengchaoxi/one-suno-api) - A unified, high-performance Suno API gateway built in Go. It aggregates multiple third-party API providers behind a single interface, offers weighted round-robin load balancing, and Docker deployment. Ideal for developers building scalable applications on top of Suno.
- [hellodword/suno-radio](https://github.com/hellodword/suno-radio) - Converts Suno playlists into a continuous, randomized music radio stream. It generates an OGG stream compatible with standard media players and provides a REST API for managing playlist sources. Perfect for creating self-hosted AI radio stations.
- [Calcium-Ion/new-api](https://github.com/Calcium-Ion/new-api) - AI model interface management and distribution system, supporting multiple large models for OpenAI format calls, Midjourney Proxy, Suno, Rerank, compatible with easy payment protocol.
- [Suno-API/Suno-API](https://github.com/Suno-API/Suno-API) - This is an unofficial Suno AI API based on Golang. It currently supports generating songs, lyrics, and OpenAI Chat.

### C++
- [PABannier/bark.cpp](https://github.com/PABannier/bark.cpp) - Suno AI's Bark model in C/C++ for fast text-to-speech
- [azkadev/bark](https://github.com/azkadev/bark) - WIP Library Text To Speech From Suno AI's Bark in C/C++ for fast inference

### C#
- [GwyrddGlas/Suno-Downloader](https://github.com/GwyrddGlas/Suno-Downloader) - Download any song from suno.ai

### PHP
- [YunzhiYike/Suno-SDK](https://github.com/YunzhiYike/Suno-SDK) - This is an unofficial Suno API based on PHP; it provides support for all Suno interfaces.

### Dart
- [AllenTom/SunoGenerator](https://github.com/AllenTom/SunoGenerator) - A client for Suno to use AI music generator

### Other
- [kesperinc/suno-ai_bark](https://github.com/kesperinc/suno-ai_bark) - Jupyter Notebook for Suno AI Bark
- [pawan418/suno-ai](https://github.com/pawan418/suno-ai) - Jupyter Notebook for Suno AI
- [AIDM7350/Group-Project-Suno](https://github.com/AIDM7350/Group-Project-Suno) - From Text to Tune: Unveiling the Power of Suno AI in Song Generation
- [Malintha-Senadheera/suno-bark-ai](https://github.com/Malintha-Senadheera/suno-bark-ai) - Jupyter Notebook for Suno Bark AI

## Web Tools, Services and Applications
- [SunoPrompt.com](https://sunoprompt.com/) - An advanced web-based prompt engineering tool that helps users construct precise style descriptions. It generates structured inputs (genre, mood, instruments) to maximize the quality of Suno's outputs.
- [Suno Meta Tags Creator](https://sunometatagcreator.com/) - A visual builder for Suno's metatag system (e.g., `[Verse]`, `[Chorus]`, `[Mellow Vocals]`). Includes an AI lyric generator optimized for Suno's structural requirements.
- [Suno Manager](https://chromewebstore.google.com/detail/suno-manager/bhfnejgfonhlaalgnhcphpjbbifidpki) - A powerful browser extension for managing large libraries. It allows filtering, organizing, and bulk downloading of songs (MP3/WAV) along with their JSON metadata, operating entirely on the client side.
- [AIMusixer (AI music maker)](https://suno-ai.me) - A website for creating music using Suno from text or audio recordings.
- [AI Song Generator (Music Maker)](https://musicmaker.im/ai-song-generator/) - A song generator based on Suno AI v4 to create complete music tracks from text descriptions.
- [Yanyutin753/pictureChange](https://github.com/Yanyutin753/pictureChange) - Plugin for chatgpt-on-wechat project, supporting Baidu AI and Stable Diffusion WebUI for image processing, providing multiple model choices, supporting image-to-image and text-to-image custom templates. Suno music AI can convert images and text to music.
- [MuratGuelr/sunoai-music-player](https://github.com/MuratGuelr/sunoai-music-player) - Suno AI - Online Music Player Made By Murat Guler

## Additional Resources
- [develephant/suno-songtags](https://github.com/develephant/suno-songtags) - Collected song tags for helping steer Suno AI.

## How to Contribute

We welcome contributions from the community! If you would like to add your project to this list, please follow these steps:

1. Fork this repository.
2. Add your project to the appropriate section in the `README.md` file.
3. Submit a Pull Request with a clear description of the changes you have made.