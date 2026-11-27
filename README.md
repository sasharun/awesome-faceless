# Awesome Faceless Content Creation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🌐 **English** | [简体中文](README.zh-CN.md) | [Español](README.es.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

[![Stars](https://img.shields.io/github/stars/sasharun/awesome-faceless?style=social)](https://github.com/sasharun/awesome-faceless)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Last update](https://img.shields.io/badge/last%20update-2026--11-blue.svg)](https://github.com/sasharun/awesome-faceless)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)

> **100+ curated AI tools & open-source pipelines** for **faceless YouTube**, TikTok, and Shorts creators — scripting, TTS & local open-source voices, next-gen text-to-video (Kling / Seedance / Veo / Wan / Hailuo / Runway), editing, automation, SEO, and **2026–2027 YPP monetization rules**.
>
> Keywords people actually search: *faceless YouTube channel*, *YouTube automation*, *AI voiceover*, *open-source TTS*, *text to video*, *Shorts clipper*, *AI video pipelines*.

**🔗 Full directory with reviews & stacks:** [faceless.directory](https://faceless.directory) (100+ tools)  
**📩 Want to suggest a tool?** Open a [Tool Submission Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml) or a [Pull Request](CONTRIBUTING.md).

Build a profitable channel **without showing your face**: Research & scripts → voiceover → visuals / B-roll / animation → editing & captions → publishing → analytics.

---

## Why This List

Most "AI tool dumps" mix dead startups with affiliate spam. This list is **actively verified and curated for faceless workflows only**:

- Sorted by job-to-be-done (`research → script → voice → video → edit → distribute`)
- Honest pricing + **open-source / self-hosted alternatives** so you can build a `$0`, `$30–60`, or pro stack
- Dead tools pruned (e.g. **Play.ht** shut down Dec 2025 after Meta's PlayAI acquisition; **LOVO AI** filed Chapter 7 bankruptcy May 2026; **OpenAI Sora** was discontinued Mar 2026)
- Kept current for late 2026: **Kling 3/4, Seedance 2.5, Wan 3.0, Veo 3.1, MiniMax H3, Kokoro-82M / Qwen3-TTS, and Coding-Agent video pipelines**

---

## Contents

- [🚨 YouTube Monetization & AI Policy (2026–2027)](#-youtube-monetization--ai-policy-20262027)
- [⚡ Quick Start Stacks](#-quick-start-stacks)
- [📝 Scripting & Niche Research](#-scripting--niche-research)
- [🎙️ Voice & Text-to-Speech](#️-voice--text-to-speech)
  - [Commercial TTS & Voice Cloning](#commercial-tts--voice-cloning)
  - [Open-Source & Local TTS ($0/mo)](#open-source--local-tts-0mo)
- [🎬 Video Generation](#-video-generation)
- [✂️ Video Editing, Captions & Clips](#️-video-editing-captions--clips)
- [🖼️ Thumbnails & Graphics](#️-thumbnails--graphics)
- [🎵 Music & SFX](#-music--sfx)
- [⚡ Automation & Publishing](#-automation--publishing)
- [📊 Analytics & SEO](#-analytics--seo)
- [📁 Organization](#-organization)
- [🛠️ Open-Source Pipelines & Agent Skills](#️-open-source-pipelines--agent-skills)
- [📚 Guides & Tutorials](#-guides--tutorials)
- [🎯 Channel Ideas & CPM Benchmarks](#-channel-ideas--cpm-benchmarks)
- [🔗 Communities](#-communities)
- [🤝 Contributing](#-contributing)

---

## 🚨 YouTube Monetization & AI Policy (2026–2027)

Before you spend on automation tools, check YouTube's official rules so your channel does not get demonetized:

1. **YPP Ads & Premium Entry Thresholds Double on Feb 1, 2027** ([Official YouTube Help](https://support.google.com/youtube/answer/12843009)):
   - New applicants from **Feb 1, 2027** need **1,000 subscribers + 8,000 qualified watch hours** (past 365 days) **or 20M qualified Shorts views** (past 90 days) — up from 4,000 hours / 10M Shorts.
   - Already in YPP? Your status stays, **provided you accept the updated terms in YouTube Studio by Jan 31, 2027**. Monthly Shorts Creator Pool payouts also require maintaining 10M qualified Shorts views over 90 days starting Feb 1, 2027.
   - Early access (fan funding / Shopping) stays at 500 subs + 3,000 hours or 3M Shorts views.
2. **"Inauthentic Content" Policy (Renamed from Repetitious Content)** ([Official YPP Policy](https://support.google.com/youtube/answer/1311392)):
   - Faceless channels and AI tools are **explicitly allowed** — YouTube bans *mass-produced, templated, interchangeable videos with no original perspective, script, or narrative*.
   - **Rule of thumb:** If a reviewer opens 10 of your uploads and sees one generic template with nouns swapped, you fail YPP review. Invest in original scripts, pacing, visual storytelling, and clear human editorial direction.
3. **Mandatory Synthetic Media Disclosure** ([Official Disclosure Guide](https://support.google.com/youtube/answer/14328491)):
   - Check the "altered or synthetic content" label in YouTube Studio whenever visuals/audio depict realistic people, places, or events that did not happen. Disclosure does **not** hurt reach or YPP eligibility.

---

## ⚡ Quick Start Stacks

Copy a stack, ship your first 5 videos before automating.

| Stack | Monthly $ | Pipeline |
|---|---|---|
| **Zero budget ($0)** | $0 | ChatGPT / Gemini free → **Kokoro-82M** or CapCut voice → CapCut / DaVinci Resolve + **Clips Kitty** → Canva free |
| **Cash-cow starter** | ~$30–60 | Claude / ChatGPT → **ElevenLabs** or **Fish Audio** → CapCut + **Kling / Hailuo** B-roll → Canva + **Feed Thumbnail** |
| **Shorts & Clipping machine** | ~$30–70 | **GetYouTubeTranscript** + Claude → ElevenLabs → **Seedance / Kling** B-roll → **Opus Clip / Submagic** or **Clips Kitty** → Metricool |
| **Pro automation** | $100+ | Claude scripts → ElevenLabs / Cartesia → **Kling / Seedance / Veo / Runway** → Descript → **n8n / Make** → VidIQ |
| **Self-hosted open-source** | API / GPU only | Local LLM / API → **Qwen3-TTS / Kokoro-82M** → **Wan 3.0 / MoneyPrinterTurbo / Orkas-VideoStudio** → FFmpeg |

**Rule of thumb:** spend first on **script & hook quality** (passes YPP + drives watch time), then **voice naturalness** (retention), then **thumbnails** (CTR), and only last on expensive video models.

---

## 📝 Scripting & Niche Research

Tools for niche discovery, competitor teardown, scripts, titles, and hooks.

| Tool | Description | Pricing | Review |
|---|---|---|---|
| [ChatGPT](https://chatgpt.com/) | Scripts, titles, hooks, outline iteration | Freemium | [Review](https://faceless.directory/directory/chatgpt) |
| [Claude](https://claude.ai/) | Long-form narration scripts with less generic tone | Freemium | [Review](https://faceless.directory/directory/claude) |
| [Gemini](https://gemini.google.com/) | Research, multimodal video review, script drafts | Freemium | — |
| [Grok](https://x.ai/) | Fast ideation, real-time trend-aware drafts | Freemium | — |
| [GetYouTubeTranscript](https://getyoutubetranscript.com/) | Pull timestamped transcripts of top niche videos for hook/structure research | Freemium | — |
| [NicheCue](https://facelessyoutubeniches.com/) | Free dated topic library & script outlines for faceless B-roll/TTS channels | Free | — |
| [Jasper](https://jasper.ai/) | Marketing-oriented copy & brand voice | From $49/mo | [Review](https://faceless.directory/directory/jasper) |
| [Copy.ai](https://copy.ai/) | Workflow templates for hooks and descriptions | Freemium | [Review](https://faceless.directory/directory/copyai) |
| [Writesonic](https://writesonic.com/) | Writer with web-grounded research features | Freemium | [Review](https://faceless.directory/directory/writesonic) |

**Pro tip:** Pull 5 winning competitor transcripts with GetYouTubeTranscript, study their pacing/retention beats, then draft original scripts in Claude.

---

## 🎙️ Voice & Text-to-Speech

Narration quality is the #1 retention lever for faceless channels.

### Commercial TTS & Voice Cloning

| Tool | Description | Pricing | Review |
|---|---|---|---|
| [ElevenLabs](https://elevenlabs.io/) | Industry-leading narration, voice cloning, SFX & dubbing | From $5/mo | [Review](https://faceless.directory/directory/elevenlabs) |
| [Cartesia](https://cartesia.ai/) | Ultra-low latency, natural expressive speech | Paid / free tier | — |
| [Fish Audio](https://fish.audio/) | Strong voice cloning & multi-speaker narration, creator-friendly pricing | Freemium | — |
| [MiniMax Audio](https://www.minimax.io/audio) | Expressive multilingual speech & voice cloning at competitive API rates | Freemium | — |
| [Murf AI](https://murf.ai/) | Studio voiceovers + light timing editor | From $19/mo | [Review](https://faceless.directory/directory/murf) |
| [WellSaid](https://www.wellsaid.io/) | Studio-grade corporate & explainer voices | Paid | [Review](https://faceless.directory/directory/wellsaid) |
| [Speechify](https://speechify.com/) | Natural voices, speed control, dubbing | Freemium | [Review](https://faceless.directory/directory/speechify) |
| [OpenAI TTS](https://developers.openai.com/api/docs/guides/text-to-speech) | Reliable API voices for automated pipelines | Pay-as-you-go | — |

### Open-Source & Local TTS ($0/mo)

| Project | Description | License |
|---|---|---|
| [Kokoro-82M](https://github.com/hexgrad/kokoro) | 82M-param lightweight TTS, fast even on CPU, 54 voices across 8+ languages | Apache-2.0 |
| [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) | Multilingual streaming TTS (10 languages) with 3-second zero-shot voice cloning | Apache-2.0 |
| [IndexTTS](https://github.com/index-tts/index-tts) | Industrial-grade controllable zero-shot TTS (★25k+, strong Chinese & English) | Open source |
| [CosyVoice](https://github.com/QwenAudio/CosyVoice) | Multilingual expressive voice generation & cloning with emotion control (★24k+) | Apache-2.0 |

> **Deprecated tools removed:** **Play.ht** permanently shut down on Dec 31, 2025 after Meta acquired PlayAI; **LOVO AI** filed Chapter 7 bankruptcy in May 2026. Migrate existing workflows to ElevenLabs, Fish Audio, MiniMax Audio, or Kokoro-82M / Qwen3-TTS.

---

## 🎬 Video Generation

Text/image-to-video models, character-consistent studios, avatars, and script-to-video tools.

| Tool | Description | Pricing | Review |
|---|---|---|---|
| [Kling AI](https://klingai.com/) | Kling 3/4-class motion & multi-shot sequences; top pick for Shorts B-roll | Freemium | — |
| [Dreamina (Seedance)](https://dreamina.capcut.com/) | ByteDance Seedance 2.0/2.5; excels at image-to-video & multi-reference character consistency | Freemium | — |
| [Google Veo](https://deepmind.google/models/veo/) | Veo 3.1 flagship cinematic text/image-to-video with native audio | Paid / Gemini plans | — |
| [Alibaba Wan](https://wan.video/) | Wan 3.0 cloud & open-weight video generation; strong 1080p price-to-quality | Freemium / OSS | — |
| [MiniMax Hailuo](https://hailuoai.video/) | Hailuo / H3 models; fast, cost-effective T2V & I2V with native audio | Freemium | — |
| [Runway](https://runway.com/) | Gen-4 / Gen-4.5 video generation + pro camera/motion controls | From $12/mo | [Review](https://faceless.directory/directory/runway) |
| [Luma Dream Machine](https://lumalabs.ai/) | Fast cinematic generations & keyframe transitions | Freemium | — |
| [Higgsfield AI](https://higgsfield.ai/) | Character-consistent faceless animated episode & camera-control studio | Freemium / from $15/mo | — |
| [Vidu](https://www.vidu.com/) | Reference-to-video with strong character consistency (popular for anime/comics) | Freemium | — |
| [PixVerse](https://pixverse.ai/) | Fast social-ready T2V/I2V clips and effects | Freemium | — |
| [Magic Hour](https://magichour.ai/) | All-in-one AI video generation, video-to-video, face swap & lip sync | Freemium | — |
| [Pika](https://pika.art/) | Fast creative clips and visual effects | Freemium | [Review](https://faceless.directory/directory/pika) |
| [InVideo AI](https://invideo.io/) | Idea/script → full faceless video with stock + generative clips | Freemium / paid | [Review](https://faceless.directory/directory/invideo) |
| [Pictory](https://pictory.ai/) | Script or blog URL → narrated stock-footage video | Paid / trial | [Review](https://faceless.directory/directory/pictory) |
| [Fliki](https://fliki.ai/) | Text-to-video + multilingual AI voices | Freemium | [Review](https://faceless.directory/directory/fliki) |
| [HeyGen](https://heygen.com/) | AI avatars, voice cloning & 175+ language video translation | Freemium / paid | [Review](https://faceless.directory/directory/heygen) |
| [Synthesia](https://synthesia.io/) | Structured presenter avatars for explainers & corporate training | Paid / free tier | [Review](https://faceless.directory/directory/synthesia) |
| [D-ID](https://d-id.com/) | Photo → talking presenter avatar | Freemium | [Review](https://faceless.directory/directory/d-id) |
| [Lumen5](https://lumen5.com/) | Blog-to-video for branded explainers | Freemium | [Review](https://faceless.directory/directory/lumen5) |

> **Note:** OpenAI discontinued the Sora consumer app and Sora 2 API in March 2026. For high-motion B-roll and character consistency today, combine **Kling**, **Seedance (Dreamina)**, **Veo**, **Wan**, **Hailuo**, or **Runway**.

---

## ✂️ Video Editing, Captions & Clips

NLE editors, word-by-word captioning, and long-to-Shorts clipping tools.

| Tool | Description | Pricing | Review |
|---|---|---|---|
| [CapCut](https://capcut.com/) | Fast editor, auto-captions, templates (desktop/mobile/web) | Freemium | [Review](https://faceless.directory/directory/capcut) |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | Pro-grade NLE, color & Fusion motion graphics | Free / $295 Studio | [Review](https://faceless.directory/directory/davinci) |
| [Descript](https://descript.com/) | Edit video by editing the text transcript | Freemium / paid | [Review](https://faceless.directory/directory/descript) |
| [Adobe Premiere Pro](https://www.adobe.com/products/premiere.html) | Industry-standard timeline editor | Paid | [Review](https://faceless.directory/directory/premiere) |
| [Final Cut Pro](https://www.apple.com/final-cut-pro/) | Fast Mac pro editor | $299 one-time | [Review](https://faceless.directory/directory/finalcut) |
| [VEED](https://veed.io/) | Browser editor + AI subtitles & clean audio | Freemium | [Review](https://faceless.directory/directory/veed) |
| [Kapwing](https://kapwing.com/) | Collaborative online editor & subtitling | Freemium | [Review](https://faceless.directory/directory/kapwing) |
| [Opus Clip](https://opus.pro/) | Long video → viral Shorts with virality scoring | Freemium / from $15/mo | [Review](https://faceless.directory/directory/opus-clip) |
| [Clips Kitty](https://github.com/ColinGPT9/clips-studio) | Open-source local Opus Clip alternative (Ollama + Whisper, $0 fees) | Free (AGPL-3.0) | — |
| [Submagic](https://www.submagic.co/) | Dynamic hook-style captions & B-roll for Shorts | Paid | — |
| [Vizard](https://vizard.ai/) | AI clipping & repurposing for social channels | Freemium | — |
| [Munch](https://www.munchstudio.com/) | AI repurposing & trend-matched clips | Paid | — |
| [Karaoke Captions](https://karaokecaptions.com/) | On-device word-by-word captions & SRT/VTT editor, no watermark | Freemium | — |

**Pro tip:** Start with CapCut or DaVinci Resolve; use **Clips Kitty** (local/free) or **Opus Clip** when repurposing long-form videos/streams into daily Shorts.

---

## 🖼️ Thumbnails & Graphics

CTR lives or dies on a clear focal point and 2–4 readable words.

| Tool | Description | Pricing | Review |
|---|---|---|---|
| [Midjourney](https://midjourney.com/) | Stylized thumbnails, characters & visual scenes | From $10/mo | [Review](https://faceless.directory/directory/midjourney) |
| [ChatGPT (GPT Image)](https://chatgpt.com/) | Photoreal & text-accurate images directly inside ChatGPT (replaces DALL·E 3) | Freemium | [Review](https://faceless.directory/directory/dalle) |
| [FLUX (Black Forest Labs)](https://bfl.ai/) | High-fidelity open-weight & API image models | Varies / OSS | — |
| [Ideogram](https://ideogram.ai/) | Crisp, readable typography inside generated images | Freemium | [Review](https://faceless.directory/directory/ideogram) |
| [Recraft](https://www.recraft.ai/) | Style-consistent vectors, illustrations & brand sets | Freemium | — |
| [Canva](https://canva.com/) | Fast layout, bold thumbnail text & reusable templates | Freemium | [Review](https://faceless.directory/directory/canva) |
| [Leonardo.ai](https://leonardo.ai/) | Fine-grained style & character asset control | Freemium | [Review](https://faceless.directory/directory/leonardo) |
| [Adobe Firefly](https://firefly.adobe.com/) | Commercially safe generative fill in Adobe stack | Freemium | [Review](https://faceless.directory/directory/firefly) |
| [Photoshop](https://www.adobe.com/products/photoshop.html) | Final color pop, cutouts & pro polish | Paid | [Review](https://faceless.directory/directory/photoshop) |
| [Feed Thumbnail](https://feedthumbnail.com/youtube-thumbnail-size) | Free browser preview of how your thumbnail looks in real YouTube feeds | Free | — |

---

## 🎵 Music & SFX

Always verify YouTube Content ID clearance before publishing monetized videos.

| Tool | Description | Pricing |
|---|---|---|
| [Suno](https://suno.com/) | AI background tracks & songs (paid tier required for commercial rights) | Freemium |
| [Udio](https://www.udio.com/) | AI music generation with strong vocals & instrumentals | Freemium |
| [Epidemic Sound](https://www.epidemicsound.com/) | Content-ID cleared music & SFX for YouTube channels | Subscription |
| [Artlist](https://artlist.io/) | Royalty-free music, SFX & stock footage licensing | Subscription |
| [Pixabay Music](https://pixabay.com/music/) | Free music tracks (always check individual license / Content ID notes) | Free |

---

## ⚡ Automation & Publishing

| Tool | Description | Pricing | Review |
|---|---|---|---|
| [n8n](https://n8n.io/) | Open-source / self-hostable workflow automation (best cost at scale) | Free OSS / Cloud | [Review](https://faceless.directory/directory/n8n) |
| [Make](https://make.com/) | Visual scenario builder, cheaper than Zapier for high-step pipelines | Freemium / from $9/mo | [Review](https://faceless.directory/directory/make) |
| [Zapier](https://zapier.com/) | Broadest SaaS app integrations, fastest no-code glue | Freemium / from $20/mo | [Review](https://faceless.directory/directory/zapier) |
| [Repurpose.io](https://repurpose.io/) | Cross-post video formats across YouTube, TikTok, IG & Facebook | Paid | [Review](https://faceless.directory/directory/repurpose) |
| [Metricool](https://metricool.com/) | Multi-platform scheduling + analytics (YT / TikTok / IG) | Freemium | — |
| [Buffer](https://buffer.com/) | Clean social scheduling for solo creators | Freemium | [Review](https://faceless.directory/directory/buffer) |
| [Hootsuite](https://hootsuite.com/) | Team social management & approvals | Paid | [Review](https://faceless.directory/directory/hootsuite) |

**Pro tip:** Automate **after** 5–10 manual uploads prove CTR and AVD (average view duration). Automating a format that does not hold attention just burns API credits faster.

---

## 📊 Analytics & SEO

| Tool | Description | Pricing | Review |
|---|---|---|---|
| [YouTube Studio](https://studio.youtube.com/) | Official retention graphs, CTR, A/B thumbnail tests & revenue (start here) | Free | — |
| [TubeBuddy](https://tubebuddy.com/) | YT SEO, keyword explorer & A/B testing | Freemium | [Review](https://faceless.directory/directory/tubebuddy) |
| [VidIQ](https://vidiq.com/) | Competitor outlier tracking & keyword research | Freemium | [Review](https://faceless.directory/directory/vidiq) |
| [Social Blade](https://socialblade.com/) | Public channel growth & subscriber estimates | Free | [Review](https://faceless.directory/directory/socialblade) |
| [Google Trends](https://trends.google.com/trends/) | Search interest & YouTube topic demand check | Free | — |

---

## 📁 Organization

| Tool | Description | Pricing | Review |
|---|---|---|---|
| [Notion](https://www.notion.com/) | Content calendar, script templates & channel SOPs | Freemium | [Review](https://faceless.directory/directory/notion) |
| [Airtable](https://airtable.com/) | Relational production database (pairs nicely with Make/n8n) | Freemium | [Review](https://faceless.directory/directory/airtable) |
| [ClickUp](https://clickup.com/) | Multi-channel task management for editor/scriptwriter teams | Freemium | [Review](https://faceless.directory/directory/clickup) |
| [Trello](https://trello.com/) | Simple kanban board (`Idea → Script → Voice → Edit → Published`) | Freemium | [Review](https://faceless.directory/directory/trello) |

---

## 🛠️ Open-Source Pipelines & Agent Skills

Active GitHub projects that generate, edit, or clip faceless videos end-to-end (great for cutting SaaS bills or building custom channels).

| Project | What It Does | Highlights |
|---|---|---|
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | Topic/keyword → script, voice, stock/AI visuals, subtitles & HD short video | ★145k+, bilingual EN/ZH, active |
| [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2) | Automated YouTube Shorts & social content workflows in Python | ★32k+ |
| [linyqh/NarratoAI](https://github.com/linyqh/NarratoAI) | All-in-one AI movie/video commentary & auto-editing pipeline | ★11k+ |
| [kaomei/stickman-video-director](https://github.com/kaomei/stickman-video-director) | AI Agent Skill (Claude Code / Codex) turning scripts into animated stickman videos | ★7.5k+, active |
| [cporter202/automate-faceless-content](https://github.com/cporter202/automate-faceless-content) | End-to-end automation blueprints for short-form & long-form faceless YouTube | ★3.3k+, active |
| [xuanyustudio/LocalMiniDrama](https://github.com/xuanyustudio/LocalMiniDrama) | Local open-source AI short drama & motion comic studio (supports Seedance 2) | ★2.5k+, active |
| [gyoridavid/short-video-maker](https://github.com/gyoridavid/short-video-maker) | MCP-driven short video generator (Kokoro TTS + Whisper + Remotion) | ★1.5k+ |
| [ColinGPT9/clips-studio](https://github.com/ColinGPT9/clips-studio) | **Clips Kitty**: local open-source Opus Clip alternative (Ollama + Whisper) | ★620+, active |
| [Orkas-AI/Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) | Coding agents (Claude Code / Codex / Cursor) edit timelines & render checked MP4s | ★350+, MIT, active |
| [Dark2C/Viral-Faceless-Shorts-Generator](https://github.com/Dark2C/Viral-Faceless-Shorts-Generator) | Containerized trending topics → script → TTS → FFmpeg Shorts | ★120+ |
| [aruntemme/n8n-faceless-youtube](https://github.com/aruntemme/n8n-faceless-youtube) | Ready-to-import n8n workflow templates for faceless YouTube | n8n |
| [reelstyles/reelstyles-free](https://github.com/reelstyles/reelstyles-free) | 9 free film style kits; a coding agent animates and renders the MP4 locally | ★4, MIT, last push 24 Nov 2026 |

**Prompt & Agent Skill Libraries:**
- [ZeroLu/awesome-seedance](https://github.com/ZeroLu/awesome-seedance) — Curated Seedance 2.0/2.5 prompts and video workflows
- [UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) — Script, storyboard & video-prompt skills for AI short dramas and faceless stories

---

## 📚 Guides & Tutorials

Deep-dive playbooks hosted on [faceless.directory](https://faceless.directory):

### Getting Started
- [How to Start a Faceless YouTube Channel](https://faceless.directory/blog/how-to-start-faceless-youtube-channel)
- [20 Faceless YouTube Channel Ideas That Make Money](https://faceless.directory/blog/faceless-youtube-channel-ideas-2025)
- [The Ultimate FREE AI Tool Stack for Faceless YouTube](https://faceless.directory/blog/zero-budget-faceless-youtube-guide)

### Workflow & Tools
- [AI Voice Comparison: ElevenLabs vs Murf (Legacy Play.ht Notes)](https://faceless.directory/blog/elevenlabs-vs-murf-vs-play)
- [AI Video Generators Compared: Pika vs Runway & Next-Gen Models](https://faceless.directory/blog/pika-vs-runway-vs-sora)
- [CapCut for Faceless Videos](https://faceless.directory/blog/capcut-faceless-video-editing)

### Advanced & Monetization
- [Faceless YouTube Automation Guide](https://faceless.directory/blog/faceless-youtube-automation-guide)
- [10-Minute-a-Day Factory with Zapier](https://faceless.directory/blog/automated-workflow-zapier-ai)
- [YouTube Shorts SEO](https://faceless.directory/blog/youtube-shorts-seo-uncovered)
- [7 Revenue Streams Beyond AdSense](https://faceless.directory/blog/faceless-youtube-monetization)
- [Affiliate Strategies for Faceless Channels](https://faceless.directory/blog/affiliate-marketing-faceless-channels)
- [YouTube AI Rules & Demonetization Risks](https://faceless.directory/blog/youtube-ai-monetization-traps)

### Niche Playbooks
- [Reddit Stories Channel](https://faceless.directory/blog/reddit-stories-youtube-channel-guide)
- [Horror Narration](https://faceless.directory/blog/horror-narration-channel-guide)
- [AI News Channel](https://faceless.directory/blog/ai-news-channel-guide)
- [Meditation & Sleep (High CPM)](https://faceless.directory/blog/meditation-sleep-channel-guide)

---

## 🎯 Channel Ideas & CPM Benchmarks

*(Indicative US/Tier-1 AdSense ranges; actual RPM varies heavily by audience geography and watch time.)*

| Niche | Typical CPM Range | Difficulty | Core Stack |
|---|---|---|---|
| **Finance / Investing** | $15–40 | Hard | Claude, ElevenLabs, CapCut / Motion graphics |
| **Tech & AI Explainers** | $8–20 | Medium | Screen recording + Claude + ElevenLabs / Kokoro |
| **True Crime / Documentaries** | $6–15 | Medium | Deep research + narration + Kling/Runway B-roll |
| **Educational Explainers / Stickman** | $6–15 | Medium | Original scripts + `stickman-video-director` / Motion |
| **Meditation & Sleep** | $5–15 | Easy | Ambient audio + slow loops (avoid pure repetition) |
| **Horror & Mystery Narration** | $4–10 | Easy | Original stories + ElevenLabs/Fish + dark visuals |
| **Gaming Lore & Essays** | $3–8 | Medium | Gameplay footage + commentary |
| **Reddit / Story Shorts** | $2–8 | Easy | TTS + gameplay/AI B-roll (high YPP scrutiny — add original commentary) |

---

## 🔗 Communities

- [r/NewTubers](https://reddit.com/r/NewTubers) — Early-stage YouTube growth & feedback
- [r/PartneredYoutube](https://reddit.com/r/PartneredYoutube) — Monetized creators & YPP policy updates
- [r/youtubers](https://reddit.com/r/youtubers) — General YouTube creator community
- [r/FacelessYouTube](https://www.reddit.com/r/FacelessYouTube/) — Faceless channel discussions
- [Indie Hackers](https://indiehackers.com/) — Business & monetization side of creator ops

---

## 🤝 Contributing

PRs and tool suggestions are welcome — please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

- **Good submission:** active product or open-source repo, clean official URL (no UTM/affiliate tracking), concise job-to-be-done, honest pricing.
- **Submit via Issue:** [Suggest a tool here](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml).
- **Translations:** Help keep `README.zh-CN.md`, `README.es.md`, `README.ja.md`, and `README.ko.md` sharp!

If this list saves you hours of research, **star the repo** so other creators can find it.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Public domain (CC0 1.0).

---

**Maintained for [Faceless Directory](https://faceless.directory)** — tools, stacks, and playbooks for faceless creators.

[![Star History Chart](https://api.star-history.com/svg?repos=sasharun/awesome-faceless&type=Date)](https://star-history.com/#sasharun/awesome-faceless&Date)
