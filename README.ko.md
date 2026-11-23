# Awesome 얼굴 없는 유튜브 · AI 영상 제작 도구 모음 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🌐 [English](README.md) | [简体中文](README.zh-CN.md) | [Español](README.es.md) | [日本語](README.ja.md) | **한국어**

[![Stars](https://img.shields.io/github/stars/sasharun/awesome-faceless?style=social)](https://github.com/sasharun/awesome-faceless)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Last update](https://img.shields.io/badge/last%20update-2026--11-blue.svg)](https://github.com/sasharun/awesome-faceless)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)

> **얼굴 없는 유튜브(Faceless YouTube), 유튜브 쇼츠(Shorts), 틱톡 자동화** 크리에이터를 위한 **검증된 AI 도구 & 오픈소스 파이프라인 100선**. 대본 작성, 상용/무료 로컬 AI 더빙(TTS), 차세대 영상 생성(Kling / Seedance / Veo / Wan / Hailuo / Runway), 편집·자막·클리핑, 자동화, SEO, 그리고 **2026–2027 유튜브 수익 창출(YPP) 최신 정책**까지 한눈에 정리했습니다.
>
> 주요 검색 키워드: *얼굴 없는 유튜브* · *유튜브 쇼츠 자동화* · *AI 더빙 / TTS* · *AI 영상 생성* · *오픈소스 쇼츠 자동화*

**🔗 상세 리뷰 및 워크플로 디렉터리(영문):** [faceless.directory](https://faceless.directory)  
**📩 도구 추천 / 깨진 링크 제보:** [Tool Submission Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml) 또는 [Pull Request](CONTRIBUTING.md)

얼굴 공개 없이 수익형 채널을 만드는 핵심 파이프라인: **주제 리서치 & 대본 → AI 성우/TTS → B-roll / 영상 / 애니메이션 → 편집 & 자막 → 예약 업로드 → 분석**.

---

## 이 리스트를 봐야 하는 이유

죽은 링크와 제휴 스팸이 뒤섞인 AI 모음과 달리, **실제 페이슬리스(얼굴 없는) 영상 제작 흐름에 맞춰 직접 검증한 도구만** 엄선했습니다:

- 작업 단계별 정리 (`리서치 → 대본 → 음성 → 영상 → 편집 → 배포/분석`)
- 정직한 가격 표기 + **월 0원 오픈소스 로컬 대안** 포함 (`$0` / `$30–60` / 프로 자동화 스택)
- 종료·파산 서비스 정리 완료 (**Play.ht** 2025년 12월 서비스 종료, **LOVO AI** 2026년 5월 Chapter 7 파산 신청, **OpenAI Sora** 2026년 3월 종료)
- 2026년 하반기 최신 생태계 반영: **Kling 3/4, Seedance 2.5, Wan 3.0, Veo 3.1, MiniMax H3, Kokoro-82M / Qwen3-TTS, AI 에이전트 영상 편집 파이프라인**

---

## 목차

- [🚨 유튜브 수익 창출(YPP) & AI 정책 (2026–2027)](#-유튜브-수익-창출ypp--ai-정책-20262027)
- [⚡ 바로 따라 하는 추천 스택](#-바로-따라-하는-추천-스택)
- [📝 대본 작성 & 주제 리서치](#-대본-작성--주제-리서치)
- [🎙️ AI 음성 더빙 & TTS](#️-ai-음성-더빙--tts)
  - [상용 TTS & 보이스 클로닝](#상용-tts--보이스-클로닝)
  - [오픈소스 로컬 무료 TTS (월 $0)](#오픈소스-로컬-무료-tts-월-0)
- [🎬 AI 영상 생성](#-ai-영상-생성)
- [✂️ 영상 편집, 자동 자막 & 롱폼→쇼츠 클리핑](#️-영상-편집-자동-자막--롱폼쇼츠-클리핑)
- [🖼️ 썸네일 & 이미지 생성](#️-썸네일--이미지-생성)
- [🎵 배경음악(BGM) & 효과음](#-배경음악bgm--효과음)
- [⚡ 자동화 & 예약 업로드](#-자동화--예약-업로드)
- [📊 채널 분석 & 유튜브 SEO](#-채널-분석--유튜브-seo)
- [📁 기획 및 일정 관리](#-기획-및-일정-관리)
- [🛠️ 오픈소스 파이프라인 & Agent Skills](#️-오픈소스-파이프라인--agent-skills)
- [📚 심화 가이드 & 플레이북 (영문)](#-심화-가이드--플레이북-영문)
- [🎯 인기 주제 아이디어 & CPM 참고](#-인기-주제-아이디어--cpm-참고)
- [🔗 크리에이터 커뮤니티](#-크리에이터-커뮤니티)
- [🤝 기여하기](#-기여하기)

---

## 🚨 유튜브 수익 창출(YPP) & AI 정책 (2026–2027)

자동화 툴에 결제하기 전에, 수익 창출 정지(노란딱지/재사용·비진정 콘텐츠)를 피하기 위한 공식 규정을 꼭 확인하세요:

1. **2027년 2월 1일부터 YPP(광고·Premium 수익) 신규 가입 기준 2배 상향** ([YouTube 공식 고객센터](https://support.google.com/youtube/answer/12843009)):
   - **2027년 2월 1일 이후** 신규 신청 채널은 **구독자 1,000명 + 최근 365일 유효 시청 시간 8,000시간** 또는 **최근 90일 유효 쇼츠 조회수 2,000만 회**가 필요합니다(기존 4,000시간 / 1,000만 회에서 상향).
   - 이미 YPP에 가입된 채널은 자격이 유지되지만 **2027년 1월 31일까지** YouTube Studio에서 업데이트된 약관에 동의해야 합니다. 또한 2027년 2월부터 Shorts Creator Pool 월별 수익 분배를 받으려면 최근 90일 유효 쇼츠 조회수 1,000만 회 유지가 필요합니다.
   - 팬 후원/쇼핑 조기 이용 기준(구독자 500명 + 3,000시간 또는 쇼츠 300만 회)은 기존과 동일합니다.
2. **「비진정 콘텐츠(Inauthentic Content)」 정책** (기존 반복 콘텐츠 개편, [공식 YPP 정책](https://support.google.com/youtube/answer/1311392)):
   - 얼굴 없는 채널과 AI 도구 활용 자체는 **허용**됩니다. 다만 **템플릿 대량 생산, 독창적 해설이나 서사 없는 기계적 반복 영상**은 수익 창출이 거부됩니다.
3. **사실적인 AI 합성 콘텐츠 표시 의무** ([공식 공개 가이드](https://support.google.com/youtube/answer/14328491)):
   - 실제처럼 보이는 AI 인물·사건·음성이 포함된 경우 YouTube Studio에서 '변형되거나 합성된 콘텐츠' 옵션을 체크해야 합니다. 공식 안내에 따르면 **표시하더라도 노출이나 수익 창출에 불이익이 없습니다**.

---

## ⚡ 바로 따라 하는 추천 스택

자동화를 붙이기 전에 먼저 수동으로 영상 5편을 올려 클릭률(CTR)과 시청 지속 시간을 검증하세요.

| 스택 | 월 예산 | 추천 조합 |
|---|---|---|
| **무료 시작 ($0)** | $0 | ChatGPT / Gemini 무료 → **Kokoro-82M / Qwen3-TTS** 또는 CapCut 음성 → CapCut / DaVinci Resolve + **Clips Kitty** → Canva 무료 |
| **수익형 스타터** | ~$30–60 | Claude / ChatGPT → **ElevenLabs / Fish Audio** → CapCut + **Kling / Hailuo** B-roll → Canva + **Feed Thumbnail** |
| **쇼츠·클리핑 특화** | ~$30–70 | **GetYouTubeTranscript** + Claude → ElevenLabs → **Seedance / Kling** → **Opus Clip / Submagic** 또는 **Clips Kitty** → Metricool |
| **프로 자동화** | $100+ | Claude 대본 → ElevenLabs / Cartesia → **Kling / Seedance / Veo / Runway** → Descript → **n8n / Make** → VidIQ |
| **오픈소스 자체 구축** | API / GPU만 | 로컬 LLM / API → **Qwen3-TTS / Kokoro-82M** → **Wan 3.0 / MoneyPrinterTurbo / Orkas-VideoStudio** → FFmpeg |

**투자 우선순위:** ① **대본과 초반 3초 훅** (YPP 통과 + 유지율) → ② **자연스러운 음성** → ③ **썸네일** (CTR) → ④ 고가 영상 모델은 마지막.

---

## 📝 대본 작성 & 주제 리서치

| 도구 | 설명 | 가격 | 리뷰 |
|---|---|---|---|
| [ChatGPT](https://chatgpt.com/) | 대본, 제목, 훅 및 구성 아이디어 생성 | Freemium | [Review](https://faceless.directory/directory/chatgpt) |
| [Claude](https://claude.ai/) | 긴 해설 대본에서도 자연스럽고 AI 티가 덜 나는 문체 | Freemium | [Review](https://faceless.directory/directory/claude) |
| [Gemini](https://gemini.google.com/) | 리서치, 멀티모달 영상 분석, 대본 초안 | Freemium | — |
| [Grok](https://x.ai/) | 실시간 트렌드 기반 빠른 아이디어 도출 | Freemium | — |
| [GetYouTubeTranscript](https://getyoutubetranscript.com/) | 인기 경쟁 영상의 타임스탬프 자막을 추출해 훅/구조 벤치마킹 | Freemium | — |
| [NicheCue](https://facelessyoutubeniches.com/) | 얼굴 없는 유튜브용 무료 주제 라이브러리 및 대본 개요 | 무료 | — |
| [Jasper](https://jasper.ai/) | 마케팅 중심 카피라이팅 | $49/월~ | [Review](https://faceless.directory/directory/jasper) |
| [Copy.ai](https://copy.ai/) | 훅·설명란 템플릿 워크플로 | Freemium | [Review](https://faceless.directory/directory/copyai) |
| [Writesonic](https://writesonic.com/) | 웹 검색 기반 콘텐츠 작성 도구 | Freemium | [Review](https://faceless.directory/directory/writesonic) |

---

## 🎙️ AI 음성 더빙 & TTS

### 상용 TTS & 보이스 클로닝

| 도구 | 설명 | 가격 | 리뷰 |
|---|---|---|---|
| [ElevenLabs](https://elevenlabs.io/) | 한국어·영어 모두 최상급 AI 더빙, 보이스 클로닝, 효과음, 다국어 더빙 | $5/월~ | [Review](https://faceless.directory/directory/elevenlabs) |
| [Fish Audio](https://fish.audio/) | 자연스러운 한국어·다국어 음성 복제, 합리적인 크리에이터 요금 | Freemium | — |
| [MiniMax Audio](https://www.minimax.io/audio) | 감정 표현이 뛰어난 다국어 TTS 및 고가성비 API | Freemium | — |
| [Cartesia](https://cartesia.ai/) | 초저지연 자연스러운 음성 합성 | 유료 / 무료 티어 | — |
| [Murf AI](https://murf.ai/) | 스튜디오 나레이션 + 간편 타임라인 편집 | $19/월~ | [Review](https://faceless.directory/directory/murf) |
| [WellSaid](https://www.wellsaid.io/) | 기업·설명 영상용 영어 전문 성우 | 유료 | [Review](https://faceless.directory/directory/wellsaid) |
| [Speechify](https://speechify.com/) | 자연스러운 음성, 배속 조절, 더빙 | Freemium | [Review](https://faceless.directory/directory/speechify) |
| [OpenAI TTS](https://developers.openai.com/api/docs/guides/text-to-speech) | 자동화 파이프라인용 안정적인 API 음성 | 종량제 | — |

### 오픈소스 로컬 무료 TTS (월 $0)

| 프로젝트 | 설명 | 라이선스 |
|---|---|---|
| [Kokoro-82M](https://github.com/hexgrad/kokoro) | 82M 초경량 오픈소스 TTS, CPU에서도 고속 동작, 8+ 언어 지원 | Apache-2.0 |
| [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) | 한국어 포함 10개 언어 스트리밍 TTS, 3초 제로샷 음성 복제 | Apache-2.0 |
| [CosyVoice](https://github.com/QwenAudio/CosyVoice) | 한국어 포함 다국어 감정 제어 음성 생성 (★24k+) | Apache-2.0 |
| [IndexTTS](https://github.com/index-tts/index-tts) | 정밀 제어 가능한 산업용 제로샷 TTS (★25k+) | Open source |

> **종료 서비스 제외 안내:** **Play.ht**는 2025년 12월 말 영구 종료되었고, **LOVO AI**는 2026년 5월 Chapter 7 파산을 신청하여 목록에서 삭제했습니다.

---

## 🎬 AI 영상 생성

| 도구 | 설명 | 가격 | 리뷰 |
|---|---|---|---|
| [Kling AI](https://klingai.com/) | Kling 3/4급 자연스러운 움직임과 멀티샷, 쇼츠 B-roll 주력 | Freemium | — |
| [Dreamina (Seedance)](https://dreamina.capcut.com/) | ByteDance Seedance 2.0/2.5 — 이미지→영상 및 캐릭터 일관성 최강 | Freemium | — |
| [Google Veo](https://deepmind.google/models/veo/) | 네이티브 오디오 포함 시네마틱 영상 생성 (Veo 3.1) | 유료 / Gemini | — |
| [Alibaba Wan](https://wan.video/) | Wan 3.0 클라우드 + 오픈웨이트, 1080p 가성비 우수 | Freemium / OSS | — |
| [MiniMax Hailuo](https://hailuoai.video/) | Hailuo / H3 모델, 네이티브 오디오 지원 고속·저비용 생성 | Freemium | — |
| [Runway](https://runway.com/) | Gen-4 / Gen-4.5 영상 생성 + 정교한 카메라 모션 제어 | $12/월~ | [Review](https://faceless.directory/directory/runway) |
| [Luma Dream Machine](https://lumalabs.ai/) | 빠른 시네마틱 영상 및 키프레임 전환 | Freemium | — |
| [Higgsfield AI](https://higgsfield.ai/) | 캐릭터 일관성 유지형 페이슬리스 애니메이션 스튜디오 | $15/월~ | — |
| [Vidu](https://www.vidu.com/) | 레퍼런스 기반 캐릭터 일관성 (애니/웹툰풍 쇼츠에 인기) | Freemium | — |
| [PixVerse](https://pixverse.ai/) | SNS용 빠른 클립 및 영상 이펙트 | Freemium | — |
| [Magic Hour](https://magichour.ai/) | AI 영상 생성, 비디오-투-비디오, 립싱크 올인원 | Freemium | — |
| [Pika](https://pika.art/) | 창의적인 짧은 클립 및 효과 | Freemium | [Review](https://faceless.directory/directory/pika) |
| [InVideo AI](https://invideo.io/) | 아이디어/대본 → 스톡+AI 영상 자동 완성 | Freemium / 유료 | [Review](https://faceless.directory/directory/invideo) |
| [Pictory](https://pictory.ai/) | 블로그/대본 → 나레이션 영상 변환 | 유료 / 체험 | [Review](https://faceless.directory/directory/pictory) |
| [Fliki](https://fliki.ai/) | 텍스트→영상 + 다국어 AI 음성 | Freemium | [Review](https://faceless.directory/directory/fliki) |
| [HeyGen](https://heygen.com/) | AI 아바타 + 175개 이상 언어 영상 번역·립싱크 | Freemium / 유료 | [Review](https://faceless.directory/directory/heygen) |
| [Synthesia](https://synthesia.io/) | 교육·기업 설명용 아바타 프레젠터 | 유료 / 무료 티어 | [Review](https://faceless.directory/directory/synthesia) |
| [D-ID](https://d-id.com/) | 사진 1장으로 말하는 아바타 제작 | Freemium | [Review](https://faceless.directory/directory/d-id) |
| [Lumen5](https://lumen5.com/) | 블로그 글 기반 브랜드 설명 영상 | Freemium | [Review](https://faceless.directory/directory/lumen5) |

> **참고:** OpenAI의 **Sora** 앱 및 Sora 2 API는 2026년 3월 서비스가 종료되었습니다.

---

## ✂️ 영상 편집, 자동 자막 & 롱폼→쇼츠 클리핑

| 도구 | 설명 | 가격 | 리뷰 |
|---|---|---|---|
| [CapCut](https://capcut.com/) | 자동 자막·템플릿이 강력한 크리에이터 필수 편집기 | Freemium | [Review](https://faceless.directory/directory/capcut) |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | 무료로 시작하는 전문가급 편집·색보정·모션그래픽 | 무료 / Studio 유료 | [Review](https://faceless.directory/directory/davinci) |
| [Descript](https://descript.com/) | 자막 텍스트 수정으로 컷 편집 (팟캐스트/해설에 강함) | Freemium / 유료 | [Review](https://faceless.directory/directory/descript) |
| [Adobe Premiere Pro](https://www.adobe.com/products/premiere.html) | 업계 표준 타임라인 편집 | 유료 | [Review](https://faceless.directory/directory/premiere) |
| [Final Cut Pro](https://www.apple.com/final-cut-pro/) | Mac 전용 고속 프로 편집기 | 일시불 구매 | [Review](https://faceless.directory/directory/finalcut) |
| [VEED](https://veed.io/) | 웹 기반 영상 편집 + AI 자막 | Freemium | [Review](https://faceless.directory/directory/veed) |
| [Kapwing](https://kapwing.com/) | 협업용 온라인 편집 및 자막 | Freemium | [Review](https://faceless.directory/directory/kapwing) |
| [Opus Clip](https://opus.pro/) | 긴 영상을 바이럴 점수 기반 쇼츠로 자동 편집 | Freemium / $15/월~ | [Review](https://faceless.directory/directory/opus-clip) |
| [Clips Kitty](https://github.com/ColinGPT9/clips-studio) | **오픈소스 로컬 무료 Opus Clip 대안** (Ollama + Whisper) | 무료 (AGPL-3.0) | — |
| [Submagic](https://www.submagic.co/) | 쇼츠용 다이내믹 자막 & 자동 B-roll | 유료 | — |
| [Vizard](https://vizard.ai/) | SNS용 AI 클리핑·리퍼포징 | Freemium | — |
| [Munch](https://www.munchstudio.com/) | 트렌드 연동 AI 쇼츠 추출 | 유료 | — |
| [Karaoke Captions](https://karaokecaptions.com/) | 기기 로컬 처리·워터마크 없는 단어별 강조 자막 편집 | Freemium | — |

---

## 🖼️ 썸네일 & 이미지 생성

| 도구 | 설명 | 가격 | 리뷰 |
|---|---|---|---|
| [Midjourney](https://midjourney.com/) | 고퀄리티 아트워크 썸네일 및 장면 생성 | $10/월~ | [Review](https://faceless.directory/directory/midjourney) |
| [ChatGPT (GPT Image)](https://chatgpt.com/) | 실사 이미지 및 정확한 텍스트 렌더링 (구 DALL·E 3 대체) | Freemium | [Review](https://faceless.directory/directory/dalle) |
| [FLUX (Black Forest Labs)](https://bfl.ai/) | 고품질 오픈웨이트 & API 이미지 모델 | 변동 / OSS | — |
| [Ideogram](https://ideogram.ai/) | 이미지 내 타이포그래피 가독성 우수 | Freemium | [Review](https://faceless.directory/directory/ideogram) |
| [Recraft](https://www.recraft.ai/) | 채널 통일감을 유지하는 벡터·일러스트 생성 | Freemium | — |
| [Canva](https://canva.com/) | 빠른 썸네일 문구 배치 및 템플릿 | Freemium | [Review](https://faceless.directory/directory/canva) |
| [Leonardo.ai](https://leonardo.ai/) | 스타일 제어가 정밀한 에셋 생성 | Freemium | [Review](https://faceless.directory/directory/leonardo) |
| [Adobe Firefly](https://firefly.adobe.com/) | 상업적으로 안전한 생성형 채우기 | Freemium | [Review](https://faceless.directory/directory/firefly) |
| [Photoshop](https://www.adobe.com/products/photoshop.html) | 누끼, 색감 보정 등 최종 마감 | 유료 | [Review](https://faceless.directory/directory/photoshop) |
| [Feed Thumbnail](https://feedthumbnail.com/youtube-thumbnail-size) | 실제 유튜브 피드에서 내 썸네일 가시성을 무료 미리보기 | 무료 | — |

---

## 🎵 배경음악(BGM) & 효과음

| 도구 | 설명 | 가격 |
|---|---|---|
| [Suno](https://suno.com/) | AI 음악 생성 (상업적 수익화에는 유료 플랜 필요) | Freemium |
| [Udio](https://www.udio.com/) | 고음질 AI 보컬·인스트루멘털 생성 | Freemium |
| [Epidemic Sound](https://www.epidemicsound.com/) | 유튜브 Content ID 안전 음원 및 효과음 | 구독 |
| [Artlist](https://artlist.io/) | BGM·효과음·스톡 영상 상업 라이선스 | 구독 |
| [Pixabay Music](https://pixabay.com/music/) | 무료 음원 (사용 전 개별 Content ID 안내 확인) | 무료 |

---

## ⚡ 자동화 & 예약 업로드

| 도구 | 설명 | 가격 | 리뷰 |
|---|---|---|---|
| [n8n](https://n8n.io/) | 오픈소스/자체 호스팅 워크플로 자동화 (대량 운영 시 최저 비용) | 무료 OSS / Cloud | [Review](https://faceless.directory/directory/n8n) |
| [Make](https://make.com/) | 시각적 시나리오 자동화, 다단계 파이프라인 가성비 우수 | Freemium / $9/월~ | [Review](https://faceless.directory/directory/make) |
| [Zapier](https://zapier.com/) | 가장 많은 SaaS 앱 연동 지원 | Freemium / $20/월~ | [Review](https://faceless.directory/directory/zapier) |
| [Repurpose.io](https://repurpose.io/) | 유튜브·틱톡·인스타 자동 멀티 배포 | 유료 | [Review](https://faceless.directory/directory/repurpose) |
| [Metricool](https://metricool.com/) | 멀티 플랫폼 예약 업로드 + 통합 분석 | Freemium | — |
| [Buffer](https://buffer.com/) | 1인 크리에이터용 깔끔한 예약 배포 | Freemium | [Review](https://faceless.directory/directory/buffer) |
| [Hootsuite](https://hootsuite.com/) | 팀 단위 소셜 계정 관리 | 유료 | [Review](https://faceless.directory/directory/hootsuite) |

---

## 📊 채널 분석 & 유튜브 SEO

| 도구 | 설명 | 가격 | 리뷰 |
|---|---|---|---|
| [YouTube Studio](https://studio.youtube.com/) | 공식 시청 지속 시간, CTR, 썸네일 A/B 테스트 | 무료 | — |
| [TubeBuddy](https://tubebuddy.com/) | 유튜브 SEO, 키워드 탐색, A/B 테스트 | Freemium | [Review](https://faceless.directory/directory/tubebuddy) |
| [VidIQ](https://vidiq.com/) | 떡상(Outlier) 영상 추적 및 경쟁 채널 키워드 분석 | Freemium | [Review](https://faceless.directory/directory/vidiq) |
| [Social Blade](https://socialblade.com/) | 공개 채널 성장 추이 및 통계 조회 | 무료 | [Review](https://faceless.directory/directory/socialblade) |
| [Google Trends](https://trends.google.com/trends/) | 국가별 검색·유튜브 트렌드 수요 확인 | 무료 | — |

---

## 📁 기획 및 일정 관리

| 도구 | 설명 | 가격 | 리뷰 |
|---|---|---|---|
| [Notion](https://www.notion.com/) | 업로드 캘린더, 대본 템플릿, 채널 SOP | Freemium | [Review](https://faceless.directory/directory/notion) |
| [Airtable](https://airtable.com/) | n8n / Make 자동화 연동에 최적인 제작 DB | Freemium | [Review](https://faceless.directory/directory/airtable) |
| [ClickUp](https://clickup.com/) | 다채널·외주 편집자 협업 관리 | Freemium | [Review](https://faceless.directory/directory/clickup) |
| [Trello](https://trello.com/) | 직관적인 칸반 보드 | Freemium | [Review](https://faceless.directory/directory/trello) |

---

## 🛠️ 오픈소스 파이프라인 & Agent Skills

| 프로젝트 | 기능 | 특징 |
|---|---|---|
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | 키워드 입력 → 대본·음성·영상·자막까지 HD 쇼츠 원클릭 생성 | ★145k+, 활발 |
| [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2) | 파이썬 기반 유튜브 쇼츠 자동화 파이프라인 | ★32k+ |
| [linyqh/NarratoAI](https://github.com/linyqh/NarratoAI) | 올인원 AI 영화/영상 리뷰 및 자동 편집 | ★11k+ |
| [kaomei/stickman-video-director](https://github.com/kaomei/stickman-video-director) | 대본을 스틱맨 애니메이션 영상으로 변환하는 AI Agent Skill | ★7.5k+, 활발 |
| [cporter202/automate-faceless-content](https://github.com/cporter202/automate-faceless-content) | 숏폼·롱폼 얼굴 없는 유튜브 자동화 청사진 | ★3.3k+, 활발 |
| [xuanyustudio/LocalMiniDrama](https://github.com/xuanyustudio/LocalMiniDrama) | 로컬 오픈소스 AI 숏드라마·웹툰 영상 스튜디오 (Seedance 2 지원) | ★2.5k+, 활발 |
| [gyoridavid/short-video-maker](https://github.com/gyoridavid/short-video-maker) | MCP 기반 쇼츠 생성기 (Kokoro + Whisper + Remotion) | ★1.5k+ |
| [ColinGPT9/clips-studio](https://github.com/ColinGPT9/clips-studio) | **Clips Kitty**: 로컬 무료 오픈소스 Opus Clip 대안 | ★620+, 활발 |
| [Orkas-AI/Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) | 코딩 에이전트가 타임라인 편집부터 MP4 렌더링까지 수행 | ★350+, MIT, 활발 |
| [Dark2C/Viral-Faceless-Shorts-Generator](https://github.com/Dark2C/Viral-Faceless-Shorts-Generator) | 트렌드 수집 → 대본 → TTS → FFmpeg 쇼츠 (Docker) | ★120+ |
| [aruntemme/n8n-faceless-youtube](https://github.com/aruntemme/n8n-faceless-youtube) | 페이슬리스 유튜브용 n8n 워크플로 템플릿 | n8n |

**프롬프트 & 스킬 모음:**
- [ZeroLu/awesome-seedance](https://github.com/ZeroLu/awesome-seedance) — Seedance 2.0/2.5 프롬프트 및 워크플로
- [UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) — AI 숏드라마·스토리 영상용 대본/스토리보드 스킬

---

## 📚 심화 가이드 & 플레이북 (영문)

[faceless.directory](https://faceless.directory) 연재 가이드:

- **입문:** [How to Start a Faceless YouTube Channel](https://faceless.directory/blog/how-to-start-faceless-youtube-channel) · [20 Faceless Channel Ideas](https://faceless.directory/blog/faceless-youtube-channel-ideas-2025) · [FREE AI Stack](https://faceless.directory/blog/zero-budget-faceless-youtube-guide)
- **도구 비교:** [AI Voice Comparison](https://faceless.directory/blog/elevenlabs-vs-murf-vs-play) · [AI Video Models](https://faceless.directory/blog/pika-vs-runway-vs-sora) · [CapCut Workflow](https://faceless.directory/blog/capcut-faceless-video-editing)
- **수익화·SEO:** [Automation Guide](https://faceless.directory/blog/faceless-youtube-automation-guide) · [Shorts SEO](https://faceless.directory/blog/youtube-shorts-seo-uncovered) · [7 Revenue Streams](https://faceless.directory/blog/faceless-youtube-monetization) · [YouTube AI Rules](https://faceless.directory/blog/youtube-ai-monetization-traps)

---

## 🎯 인기 주제 아이디어 & CPM 참고

*(미국/Tier-1 애드센스 기준 참고치이며, 한국/글로벌 시청자 국가와 시청 시간에 따라 실제 RPM은 크게 달라집니다.)*

| 주제(니치) | 예상 CPM (Tier-1) | 난이도 | 핵심 스택 |
|---|---|---|---|
| **재테크 / 금융 / 투자** | $15–40 | 높음 | Claude, ElevenLabs, CapCut / 인포그래픽 |
| **테크 · AI 튜토리얼** | $8–20 | 보통 | 화면 녹화 + Claude + ElevenLabs / Kokoro |
| **미스터리 · 사건 다큐** | $6–15 | 보통 | 심층 자료 조사 + 나레이션 + Kling/Runway |
| **지식 설명 / 스틱맨 애니** | $6–15 | 보통 | 오리지널 대본 + `stickman-video-director` |
| **명상 · 수면 · ASMR** | $5–15 | 낮음 | 앰비언트 음원 + 영상 (단순 반복 루프 주의) |
| **공포 썰 / 괴담 낭독** | $4–10 | 낮음 | 창작 스토리 + ElevenLabs/Fish + 다크 B-roll |
| **게임 세계관 / 스토리 해설** | $3–8 | 보통 | 플레이 영상 + 독창적 해설 |
| **레딧 썰 / 쇼츠 요약** | $2–8 | 낮음 | YPP 심사 엄격 — 본인만의 코멘터리 필수 |

---

## 🔗 커뮤니티

- [r/NewTubers](https://reddit.com/r/NewTubers) · [r/PartneredYoutube](https://reddit.com/r/PartneredYoutube) · [r/youtubers](https://reddit.com/r/youtubers) · [r/FacelessYouTube](https://www.reddit.com/r/FacelessYouTube/) · [Indie Hackers](https://indiehackers.com/)

---

## 🤝 기여하기

PR과 도구 추천을 환영합니다! [CONTRIBUTING.md](CONTRIBUTING.md)를 확인하거나 [Tool Submission Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml)로 제보해 주세요 (UTM 없는 공식 URL만 접수).

유용했다면 **Star**를 눌러 다른 크리에이터들도 찾을 수 있게 도와주세요!

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

퍼블릭 도메인 (CC0 1.0).

---

**운영: [Faceless Directory](https://faceless.directory)**

[![Star History Chart](https://api.star-history.com/svg?repos=sasharun/awesome-faceless&type=Date)](https://star-history.com/#sasharun/awesome-faceless&Date)
