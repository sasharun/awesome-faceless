# Awesome Creación de Contenido Sin Rostro (Faceless) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🌐 [English](README.md) | [简体中文](README.zh-CN.md) | **Español** | [日本語](README.ja.md) | [한국어](README.ko.md)

[![Stars](https://img.shields.io/github/stars/sasharun/awesome-faceless?style=social)](https://github.com/sasharun/awesome-faceless)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Last update](https://img.shields.io/badge/last%20update-2026--11-blue.svg)](https://github.com/sasharun/awesome-faceless)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)

> **Más de 100 herramientas de IA y pipelines open source** curados para crear **canales de YouTube sin rostro (automatización de YouTube)**, TikTok y Shorts: guiones, voces/TTS comerciales y locales gratis, generación de video (Kling / Seedance / Veo / Wan / Hailuo / Runway), edición, automatización, SEO y las **políticas de monetización YPP 2026–2027**.
>
> Términos clave: *canales sin rostro*, *automatización de YouTube*, *YouTube faceless*, *voz con IA*, *texto a video*, *Shorts con IA*, *TTS open source*.

**🔗 Directorio completo con reseñas y stacks (EN):** [faceless.directory](https://faceless.directory)  
**📩 ¿Quieres sugerir una herramienta?** Abre un [Tool Submission Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml) o un [Pull Request](CONTRIBUTING.md).

Construye un canal rentable **sin mostrar tu cara**: Investigación y guion → locución con IA → B-roll / video / animación → edición y subtítulos → publicación → analítica.

---

## Por qué esta lista

Muchas listas de herramientas IA mezclan servicios cerrados con enlaces de afiliado. Esta lista se **verifica y actualiza activamente** solo para flujos *faceless*:

- Ordenada por etapa real del proceso (`investigación → guion → voz → video → edición → distribución`)
- Precios transparentes + **alternativas open source gratis** para empezar con `$0`, `$30–60/mes` o escala pro
- Herramientas cerradas eliminadas (**Play.ht** cerró en dic. 2025 tras la adquisición de PlayAI por Meta; **LOVO AI** se declaró en bancarrota Capítulo 7 en mayo 2026; **OpenAI Sora** fue descontinuado en marzo 2026)
- Actualizada a finales de 2026: **Kling 3/4, Seedance 2.5, Wan 3.0, Veo 3.1, MiniMax H3, Kokoro-82M / Qwen3-TTS y pipelines con agentes**

---

## Contenido

- [🚨 Monetización de YouTube y Política de IA (2026–2027)](#-monetización-de-youtube-y-política-de-ia-20262027)
- [⚡ Stacks rápidos para empezar](#-stacks-rápidos-para-empezar)
- [📝 Guiones e Investigación de Nichos](#-guiones-e-investigación-de-nichos)
- [🎙️ Voz y Text-to-Speech (TTS)](#️-voz-y-text-to-speech-tts)
  - [TTS Comercial y Clonación de Voz](#tts-comercial-y-clonación-de-voz)
  - [TTS Open Source y Local ($0/mes)](#tts-open-source-y-local-0mes)
- [🎬 Generación de Video](#-generación-de-video)
- [✂️ Edición de Video, Subtítulos y Clips](#️-edición-de-video-subtítulos-y-clips)
- [🖼️ Miniaturas y Gráficos](#️-miniaturas-y-gráficos)
- [🎵 Música y Efectos de Sonido](#-música-y-efectos-de-sonido)
- [⚡ Automatización y Publicación](#-automatización-y-publicación)
- [📊 Analítica y SEO](#-analítica-y-seo)
- [📁 Organización](#-organización)
- [🛠️ Pipelines Open Source y Agent Skills](#️-pipelines-open-source-y-agent-skills)
- [📚 Guías y Tutoriales (EN)](#-guías-y-tutoriales-en)
- [🎯 Ideas de Nichos y CPM Referencial](#-ideas-de-nichos-y-cpm-referencial)
- [🔗 Comunidades](#-comunidades)
- [🤝 Contribuir](#-contribuir)

---

## 🚨 Monetización de YouTube y Política de IA (2026–2027)

Antes de invertir en automatización, revisa las reglas oficiales para evitar la desmonetización:

1. **Los requisitos de entrada al YPP (anuncios y Premium) se duplican el 1 de febrero de 2027** ([Ayuda oficial de YouTube](https://support.google.com/youtube/answer/12843009)):
   - Desde el **1 de feb. de 2027**, los nuevos canales necesitarán **1,000 suscriptores + 8,000 horas de reproducción válidas** (últimos 365 días) **o 20M de vistas válidas de Shorts** (últimos 90 días), frente a 4,000 horas / 10M Shorts anteriores.
   - Si ya estás en el YPP, mantienes tu estado **aceptando los nuevos términos en YouTube Studio antes del 31 de enero de 2027**. Además, los pagos mensuales del Shorts Creator Pool requerirán mantener 10M de vistas válidas en 90 días desde feb. 2027.
   - El acceso anticipado (membresías / Shopping) se mantiene en 500 suscriptores + 3,000 horas o 3M vistas de Shorts.
2. **Política de «Contenido no auténtico» (*Inauthentic Content*)** ([Políticas YPP](https://support.google.com/youtube/answer/1311392)):
   - Los canales sin rostro y el uso de IA **están permitidos**. Lo que YouTube desmonetiza es el contenido **producido en masa, genérico o con plantillas repetitivas** sin aporte editorial ni narrativa original.
3. **Etiquetado obligatorio de contenido sintético realista** ([Guía oficial](https://support.google.com/youtube/answer/14328491)):
   - Activa la casilla de contenido alterado o sintético en YouTube Studio cuando uses escenas o voces realistas generadas por IA. YouTube indica que **declararlo no penaliza el alcance ni la monetización**.

---

## ⚡ Stacks rápidos para empezar

Publica tus primeros 5 videos manualmente antes de automatizar.

| Stack | Presupuesto/mes | Flujo recomendado |
|---|---|---|
| **Presupuesto $0** | $0 | ChatGPT / Gemini gratis → **Kokoro-82M** o voz de CapCut → CapCut / DaVinci Resolve + **Clips Kitty** → Canva gratis |
| **Inicio rentable** | ~$30–60 | Claude / ChatGPT → **ElevenLabs** o **Fish Audio** → CapCut + B-roll en **Kling / Hailuo** → Canva + **Feed Thumbnail** |
| **Máquina de Shorts** | ~$30–70 | **GetYouTubeTranscript** + Claude → ElevenLabs → **Seedance / Kling** → **Opus Clip / Submagic** o **Clips Kitty** → Metricool |
| **Automatización Pro** | $100+ | Guiones en Claude → ElevenLabs / Cartesia → **Kling / Seedance / Veo / Runway** → Descript → **n8n / Make** → VidIQ |
| **100% Open Source local** | Solo API / GPU | LLM local / API → **Qwen3-TTS / Kokoro-82M** → **Wan 3.0 / MoneyPrinterTurbo / Orkas-VideoStudio** → FFmpeg |

**Regla de oro:** invierte primero en **guion y gancho (hook)**, luego en **naturalidad de la voz** (retención) y **miniaturas** (CTR); deja los modelos de video más caros para el final.

---

## 📝 Guiones e Investigación de Nichos

| Herramienta | Descripción | Precio | Reseña |
|---|---|---|---|
| [ChatGPT](https://chatgpt.com/) | Guiones, títulos, ganchos e iteración rápida de ideas | Freemium | [Review](https://faceless.directory/directory/chatgpt) |
| [Claude](https://claude.ai/) | Guiones largos con tono más natural y menos genérico | Freemium | [Review](https://faceless.directory/directory/claude) |
| [Gemini](https://gemini.google.com/) | Investigación, análisis multimodal de videos y borradores | Freemium | — |
| [Grok](https://x.ai/) | Ideación rápida con contexto de tendencias actuales | Freemium | — |
| [GetYouTubeTranscript](https://getyoutubetranscript.com/) | Extrae transcripciones con marcas de tiempo de videos virales para estudiar su estructura | Freemium | — |
| [NicheCue](https://facelessyoutubeniches.com/) | Biblioteca gratuita de temas y esquemas para canales faceless | Gratis | — |
| [Jasper](https://jasper.ai/) | Copywriting orientado a marketing | Desde $49/mes | [Review](https://faceless.directory/directory/jasper) |
| [Copy.ai](https://copy.ai/) | Plantillas para ganchos y descripciones | Freemium | [Review](https://faceless.directory/directory/copyai) |
| [Writesonic](https://writesonic.com/) | Redacción asistida con búsqueda web | Freemium | [Review](https://faceless.directory/directory/writesonic) |

---

## 🎙️ Voz y Text-to-Speech (TTS)

### TTS Comercial y Clonación de Voz

| Herramienta | Descripción | Precio | Reseña |
|---|---|---|---|
| [ElevenLabs](https://elevenlabs.io/) | Referente en narración natural en español/inglés, clonación, SFX y doblaje | Desde $5/mes | [Review](https://faceless.directory/directory/elevenlabs) |
| [Cartesia](https://cartesia.ai/) | Latencia ultrabaja y voces expresivas | Pago / plan gratis | — |
| [Fish Audio](https://fish.audio/) | Clonación de voz sólida y precios accesibles para creadores | Freemium | — |
| [MiniMax Audio](https://www.minimax.io/audio) | Voces multilingües expresivas y clonación competitiva vía API | Freemium | — |
| [Murf AI](https://murf.ai/) | Locuciones de estudio con editor ligero de tiempos | Desde $19/mes | [Review](https://faceless.directory/directory/murf) |
| [WellSaid](https://www.wellsaid.io/) | Voces corporativas y explicativas de estudio | Pago | [Review](https://faceless.directory/directory/wellsaid) |
| [Speechify](https://speechify.com/) | Voces naturales, control de velocidad y doblaje | Freemium | [Review](https://faceless.directory/directory/speechify) |
| [OpenAI TTS](https://developers.openai.com/api/docs/guides/text-to-speech) | Voces confiables vía API para pipelines automatizados | Pago por uso | — |

### TTS Open Source y Local ($0/mes)

| Proyecto | Descripción | Licencia |
|---|---|---|
| [Kokoro-82M](https://github.com/hexgrad/kokoro) | Modelo ligero de 82M parámetros, rápido incluso en CPU, 54 voces en 8+ idiomas (incl. español) | Apache-2.0 |
| [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) | TTS multilingüe en streaming (10 idiomas, incl. español) con clonación de 3 s | Apache-2.0 |
| [IndexTTS](https://github.com/index-tts/index-tts) | TTS zero-shot controlable de nivel industrial (★25k+) | Open source |
| [CosyVoice](https://github.com/QwenAudio/CosyVoice) | Generación de voz expresiva multilingüe con control emocional (★24k+) | Apache-2.0 |

> **Herramientas retiradas:** **Play.ht** cerró definitivamente el 31 de dic. de 2025 (Meta adquirió PlayAI) y **LOVO AI** entró en bancarrota Capítulo 7 en mayo de 2026.

---

## 🎬 Generación de Video

| Herramienta | Descripción | Precio | Reseña |
|---|---|---|---|
| [Kling AI](https://klingai.com/) | Movimiento realista y secuencias multicámara (Kling 3/4); ideal para B-roll de Shorts | Freemium | — |
| [Dreamina (Seedance)](https://dreamina.capcut.com/) | Seedance 2.0/2.5 de ByteDance; líder en imagen-a-video y consistencia de personajes | Freemium | — |
| [Google Veo](https://deepmind.google/models/veo/) | Veo 3.1 cinematográfico con audio nativo | Pago / planes Gemini | — |
| [Alibaba Wan](https://wan.video/) | Wan 3.0 en la nube y pesos abiertos; excelente relación calidad/precio en 1080p | Freemium / OSS | — |
| [MiniMax Hailuo](https://hailuoai.video/) | Modelos H3 rápidos y económicos con audio nativo | Freemium | — |
| [Runway](https://runway.com/) | Gen-4 / Gen-4.5 con control avanzado de cámara y edición | Desde $12/mes | [Review](https://faceless.directory/directory/runway) |
| [Luma Dream Machine](https://lumalabs.ai/) | Generación cinematográfica rápida y transiciones por fotograma clave | Freemium | — |
| [Higgsfield AI](https://higgsfield.ai/) | Estudio de animación faceless con consistencia de personaje y control de cámara | Desde $15/mes | — |
| [Vidu](https://www.vidu.com/) | Referencia-a-video con buena consistencia para animación e historias | Freemium | — |
| [PixVerse](https://pixverse.ai/) | Clips sociales y efectos rápidos de T2V/I2V | Freemium | — |
| [Magic Hour](https://magichour.ai/) | Generación de video, video-to-video, face swap y lip sync | Freemium | — |
| [Pika](https://pika.art/) | Clips creativos y efectos visuales rápidos | Freemium | [Review](https://faceless.directory/directory/pika) |
| [InVideo AI](https://invideo.io/) | De idea/guion a video completo con stock + clips IA | Freemium / pago | [Review](https://faceless.directory/directory/invideo) |
| [Pictory](https://pictory.ai/) | Convierte artículos o guiones en video narrado | Pago / prueba | [Review](https://faceless.directory/directory/pictory) |
| [Fliki](https://fliki.ai/) | Texto a video con voces IA en español y decenas de idiomas | Freemium | [Review](https://faceless.directory/directory/fliki) |
| [HeyGen](https://heygen.com/) | Avatares IA y traducción/doblaje de video a 175+ idiomas | Freemium / pago | [Review](https://faceless.directory/directory/heygen) |
| [Synthesia](https://synthesia.io/) | Avatares presentadores para videos educativos y corporativos | Pago / prueba gratis | [Review](https://faceless.directory/directory/synthesia) |
| [D-ID](https://d-id.com/) | Convierte una foto en presentador animado | Freemium | [Review](https://faceless.directory/directory/d-id) |
| [Lumen5](https://lumen5.com/) | Artículos de blog a video explicativo | Freemium | [Review](https://faceless.directory/directory/lumen5) |

> **Nota:** OpenAI descontinuó la app y API de **Sora** en marzo de 2026.

---

## ✂️ Edición de Video, Subtítulos y Clips

| Herramienta | Descripción | Precio | Reseña |
|---|---|---|---|
| [CapCut](https://capcut.com/) | Editor rápido, subtítulos automáticos y plantillas (PC/móvil/web) | Freemium | [Review](https://faceless.directory/directory/capcut) |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | Editor profesional gratuito, color y gráficos en movimiento | Gratis / $295 Studio | [Review](https://faceless.directory/directory/davinci) |
| [Descript](https://descript.com/) | Edita video editando el texto de la transcripción | Freemium / pago | [Review](https://faceless.directory/directory/descript) |
| [Adobe Premiere Pro](https://www.adobe.com/products/premiere.html) | Estándar profesional de edición | Pago | [Review](https://faceless.directory/directory/premiere) |
| [Final Cut Pro](https://www.apple.com/final-cut-pro/) | Editor profesional rápido para Mac | $299 pago único | [Review](https://faceless.directory/directory/finalcut) |
| [VEED](https://veed.io/) | Editor en navegador con subtítulos IA | Freemium | [Review](https://faceless.directory/directory/veed) |
| [Kapwing](https://kapwing.com/) | Editor colaborativo online y subtitulado | Freemium | [Review](https://faceless.directory/directory/kapwing) |
| [Opus Clip](https://opus.pro/) | Corta videos largos en Shorts con puntuación de viralidad | Freemium / desde $15/mes | [Review](https://faceless.directory/directory/opus-clip) |
| [Clips Kitty](https://github.com/ColinGPT9/clips-studio) | Alternativa local open source a Opus Clip (Ollama + Whisper, $0) | Gratis (AGPL-3.0) | — |
| [Submagic](https://www.submagic.co/) | Subtítulos dinámicos y B-roll para Shorts/Reels | Pago | — |
| [Vizard](https://vizard.ai/) | Recorte y reutilización automática de videos largos | Freemium | — |
| [Munch](https://www.munchstudio.com/) | Clips automáticos alineados con tendencias | Pago | — |
| [Karaoke Captions](https://karaokecaptions.com/) | Subtítulos palabra por palabra locales sin marca de agua | Freemium | — |

---

## 🖼️ Miniaturas y Gráficos

| Herramienta | Descripción | Precio | Reseña |
|---|---|---|---|
| [Midjourney](https://midjourney.com/) | Miniaturas artísticas y escenas estilizadas | Desde $10/mes | [Review](https://faceless.directory/directory/midjourney) |
| [ChatGPT (GPT Image)](https://chatgpt.com/) | Imágenes realistas y texto legible directo en ChatGPT | Freemium | [Review](https://faceless.directory/directory/dalle) |
| [FLUX (Black Forest Labs)](https://bfl.ai/) | Modelos de imagen open-weight y API de alta fidelidad | Variable / OSS | — |
| [Ideogram](https://ideogram.ai/) | Excelente tipografía legible dentro de la imagen | Freemium | [Review](https://faceless.directory/directory/ideogram) |
| [Recraft](https://www.recraft.ai/) | Vectores e ilustraciones con estilo consistente de marca | Freemium | — |
| [Canva](https://canva.com/) | Plantillas rápidas y texto llamativo para miniaturas | Freemium | [Review](https://faceless.directory/directory/canva) |
| [Leonardo.ai](https://leonardo.ai/) | Control fino de estilo y activos visuales | Freemium | [Review](https://faceless.directory/directory/leonardo) |
| [Adobe Firefly](https://firefly.adobe.com/) | Relleno generativo comercialmente seguro en Adobe | Freemium | [Review](https://faceless.directory/directory/firefly) |
| [Photoshop](https://www.adobe.com/products/photoshop.html) | Retoque final, recortes y contraste profesional | Pago | [Review](https://faceless.directory/directory/photoshop) |
| [Feed Thumbnail](https://feedthumbnail.com/youtube-thumbnail-size) | Vista previa gratuita de tu miniatura en el feed real de YouTube | Gratis | — |

---

## 🎵 Música y Efectos de Sonido

| Herramienta | Descripción | Precio |
|---|---|---|
| [Suno](https://suno.com/) | Música generada por IA (plan de pago requerido para uso comercial) | Freemium |
| [Udio](https://www.udio.com/) | Generación musical IA de alta calidad | Freemium |
| [Epidemic Sound](https://www.epidemicsound.com/) | Música y SFX libres de reclamos Content ID para YouTube | Suscripción |
| [Artlist](https://artlist.io/) | Licencias de música, SFX y metraje de stock | Suscripción |
| [Pixabay Music](https://pixabay.com/music/) | Pistas gratuitas (verifica siempre licencia y Content ID) | Gratis |

---

## ⚡ Automatización y Publicación

| Herramienta | Descripción | Precio | Reseña |
|---|---|---|---|
| [n8n](https://n8n.io/) | Automatización open source / autoalojada (mejor costo a escala) | Gratis OSS / Cloud | [Review](https://faceless.directory/directory/n8n) |
| [Make](https://make.com/) | Flujos visuales, más económico que Zapier para pipelines largos | Freemium / desde $9/mes | [Review](https://faceless.directory/directory/make) |
| [Zapier](https://zapier.com/) | Mayor catálogo de integraciones sin código | Freemium / desde $20/mes | [Review](https://faceless.directory/directory/zapier) |
| [Repurpose.io](https://repurpose.io/) | Publicación cruzada automática entre YouTube, TikTok e IG | Pago | [Review](https://faceless.directory/directory/repurpose) |
| [Metricool](https://metricool.com/) | Programación y analítica multiplataforma | Freemium | — |
| [Buffer](https://buffer.com/) | Programación sencilla para creadores independientes | Freemium | [Review](https://faceless.directory/directory/buffer) |
| [Hootsuite](https://hootsuite.com/) | Gestión de redes sociales para equipos | Pago | [Review](https://faceless.directory/directory/hootsuite) |

---

## 📊 Analítica y SEO

| Herramienta | Descripción | Precio | Reseña |
|---|---|---|---|
| [YouTube Studio](https://studio.youtube.com/) | Retención, CTR, pruebas A/B de miniaturas e ingresos oficiales | Gratis | — |
| [TubeBuddy](https://tubebuddy.com/) | SEO para YouTube, palabras clave y pruebas A/B | Freemium | [Review](https://faceless.directory/directory/tubebuddy) |
| [VidIQ](https://vidiq.com/) | Detección de videos *outliers* y análisis de competencia | Freemium | [Review](https://faceless.directory/directory/vidiq) |
| [Social Blade](https://socialblade.com/) | Estadísticas públicas de crecimiento de canales | Gratis | [Review](https://faceless.directory/directory/socialblade) |
| [Google Trends](https://trends.google.com/trends/) | Demanda de búsqueda y tendencias en YouTube por país | Gratis | — |

---

## 📁 Organización

| Herramienta | Descripción | Precio | Reseña |
|---|---|---|---|
| [Notion](https://www.notion.com/) | Calendario editorial, guiones y SOPs del canal | Freemium | [Review](https://faceless.directory/directory/notion) |
| [Airtable](https://airtable.com/) | Base de datos de producción ideal para conectar con n8n/Make | Freemium | [Review](https://faceless.directory/directory/airtable) |
| [ClickUp](https://clickup.com/) | Gestión de tareas para equipos multicanal | Freemium | [Review](https://faceless.directory/directory/clickup) |
| [Trello](https://trello.com/) | Tablero kanban simple (`Idea → Guion → Voz → Edición → Publicado`) | Freemium | [Review](https://faceless.directory/directory/trello) |

---

## 🛠️ Pipelines Open Source y Agent Skills

| Proyecto | Qué hace | Destacado |
|---|---|---|
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | Tema → guion, voz, metraje, subtítulos y video HD | ★145k+, activo |
| [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2) | Automatización de Shorts y contenido social en Python | ★32k+ |
| [linyqh/NarratoAI](https://github.com/linyqh/NarratoAI) | Comentario de películas/videos y edición automática con IA | ★11k+ |
| [kaomei/stickman-video-director](https://github.com/kaomei/stickman-video-director) | Skill de Agente IA (Claude Code / Codex) para videos animados estilo stickman | ★7.5k+, activo |
| [cporter202/automate-faceless-content](https://github.com/cporter202/automate-faceless-content) | Guías y flujos para automatizar videos cortos y largos sin rostro | ★3.3k+, activo |
| [xuanyustudio/LocalMiniDrama](https://github.com/xuanyustudio/LocalMiniDrama) | Estudio local open source de minidramas y cómics animados (soporta Seedance 2) | ★2.5k+, activo |
| [gyoridavid/short-video-maker](https://github.com/gyoridavid/short-video-maker) | Generador de videos cortos vía MCP (Kokoro + Whisper + Remotion) | ★1.5k+ |
| [ColinGPT9/clips-studio](https://github.com/ColinGPT9/clips-studio) | **Clips Kitty**: alternativa local gratis a Opus Clip (Ollama + Whisper) | ★620+, activo |
| [Orkas-AI/Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) | Agentes de código editan líneas de tiempo y renderizan MP4 verificados | ★350+, MIT, activo |
| [Dark2C/Viral-Faceless-Shorts-Generator](https://github.com/Dark2C/Viral-Faceless-Shorts-Generator) | Tendencias → guion → TTS → FFmpeg Shorts en Docker | ★120+ |
| [aruntemme/n8n-faceless-youtube](https://github.com/aruntemme/n8n-faceless-youtube) | Plantillas n8n listas para canales faceless | n8n |

**Bibliotecas de prompts y skills:**
- [ZeroLu/awesome-seedance](https://github.com/ZeroLu/awesome-seedance) — Prompts y flujos curados para Seedance 2.0/2.5
- [UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) — Skills de guion, storyboard y prompts para historias y cortos IA

---

## 📚 Guías y Tutoriales (EN)

Artículos detallados alojados en [faceless.directory](https://faceless.directory):

- **Primeros pasos:** [How to Start a Faceless YouTube Channel](https://faceless.directory/blog/how-to-start-faceless-youtube-channel) · [20 Faceless Channel Ideas](https://faceless.directory/blog/faceless-youtube-channel-ideas-2025) · [FREE AI Stack](https://faceless.directory/blog/zero-budget-faceless-youtube-guide)
- **Comparativas y flujo:** [AI Voice Comparison](https://faceless.directory/blog/elevenlabs-vs-murf-vs-play) · [AI Video Models Compared](https://faceless.directory/blog/pika-vs-runway-vs-sora) · [CapCut for Faceless](https://faceless.directory/blog/capcut-faceless-video-editing)
- **Monetización y SEO:** [Automation Guide](https://faceless.directory/blog/faceless-youtube-automation-guide) · [YouTube Shorts SEO](https://faceless.directory/blog/youtube-shorts-seo-uncovered) · [7 Revenue Streams](https://faceless.directory/blog/faceless-youtube-monetization) · [YouTube AI Rules & Demonetization Risks](https://faceless.directory/blog/youtube-ai-monetization-traps)

---

## 🎯 Ideas de Nichos y CPM Referencial

*(Rangos orientativos de AdSense en EE. UU./Tier-1; el CPM en mercados hispanohablantes varía mucho según el país de la audiencia: España y EE. UU. hispano pagan significativamente más que LATAM promedio.)*

| Nicho | CPM Tier-1 aprox. | Dificultad | Stack base |
|---|---|---|---|
| **Finanzas personales / Inversión** | $15–40 | Alta | Claude, ElevenLabs, CapCut / gráficos |
| **Tecnología e IA explicada** | $8–20 | Media | Captura de pantalla + Claude + ElevenLabs / Kokoro |
| **True Crime / Documentales** | $6–15 | Media | Investigación profunda + narración + Kling/Runway |
| **Explicativos / Animación Stickman** | $6–15 | Media | Guiones propios + `stickman-video-director` |
| **Meditación y Sueño** | $5–15 | Baja | Audio ambiental + visuales lentos (evita loops idénticos) |
| **Terror y Misterio** | $4–10 | Baja | Relatos originales + ElevenLabs/Fish + B-roll oscuro |
| **Lore de videojuegos** | $3–8 | Media | Gameplay + análisis narrado |
| **Historias de Reddit / Shorts** | $2–8 | Baja | Alta revisión YPP — añade comentario original |

---

## 🔗 Comunidades

- [r/NewTubers](https://reddit.com/r/NewTubers) · [r/PartneredYoutube](https://reddit.com/r/PartneredYoutube) · [r/youtubers](https://reddit.com/r/youtubers) · [r/FacelessYouTube](https://www.reddit.com/r/FacelessYouTube/) · [Indie Hackers](https://indiehackers.com/)

---

## 🤝 Contribuir

¡PRs y sugerencias son bienvenidos! Consulta [CONTRIBUTING.md](CONTRIBUTING.md) o envía una herramienta mediante [este formulario de Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml) (URL oficial limpia, sin parámetros UTM ni spam de afiliados).

Si esta lista te ahorró horas de búsqueda, **dale una Star al repositorio**.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Dominio público (CC0 1.0).

---

**Mantenido por [Faceless Directory](https://faceless.directory)**

[![Star History Chart](https://api.star-history.com/svg?repos=sasharun/awesome-faceless&type=Date)](https://star-history.com/#sasharun/awesome-faceless&Date)
