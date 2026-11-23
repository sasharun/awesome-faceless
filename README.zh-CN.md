# 不露脸自媒体 & AI 视频创作资源大全 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🌐 [English](README.md) | **简体中文** | [Español](README.es.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

[![Stars](https://img.shields.io/github/stars/sasharun/awesome-faceless?style=social)](https://github.com/sasharun/awesome-faceless)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Last update](https://img.shields.io/badge/last%20update-2026--11-blue.svg)](https://github.com/sasharun/awesome-faceless)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)

> **100+ 精选 AI 工具与开源自动化流水线**，专为**不露脸自媒体（Faceless YouTube / TikTok / Shorts）**以及**国内抖音 / 视频号 / B 站 / AI 漫剧与解说创作者**整理。覆盖选题脚本、商业与开源本地配音（TTS）、2026 新一代文生/图生视频（可灵 / 即梦 Seedance / Veo / 通义万相 / 海螺 / Runway）、智能剪辑字幕、封面设计、自动化工作流，以及 **YouTube 2026–2027 最新变现红线**。
>
> 常见检索词：*不露脸 YouTube* · *无人出镜自媒体* · *YouTube 自动化* · *AI 短视频* · *AI 漫剧* · *开源 TTS 配音* · *MoneyPrinterTurbo*

**🔗 完整工具库与评测（英文站）：** [faceless.directory](https://faceless.directory)（收录 100+ 工具）  
**📩 推荐工具 / 反馈死链：** 提交 [Tool Submission Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml) 或直接提 [Pull Request](CONTRIBUTING.md)。

不用出镜也能跑通盈利频道：**选题与脚本 → AI 配音 → 画面 / B-roll / 动漫分镜 → 剪辑与动态字幕 → 定时分发 → 数据复盘**。

---

## 为什么看这份清单

市面上的 AI 工具合集大多混着停服死链和返佣软文。这份清单**定期实测校验，只保留不露脸视频链路真正能打的工具**：

- 按完整生产流程排序（`选题脚本 → 配音 → 视频生成 → 剪辑切片 → 封面 → 自动化`）
- 兼顾**出海美金频道**与**国内直连工具栈**（含免费开源本地替代，可搭 ¥0 / 低成本 / 自动化三档方案）
- 剔除已停服/破产项目（**Play.ht** 已于 2025 年 12 月停服、**LOVO AI** 已于 2026 年 5 月申请破产清算、**OpenAI Sora** 已于 2026 年 3 月停运）
- 对齐 2026 年底最新生态：**可灵 3/4、即梦 Seedance 2.0/2.5、通义万相 Wan 3.0、Veo 3.1、海螺 H3、Kokoro-82M / Qwen3-TTS / IndexTTS，以及 AI Agent 视频剪辑工作流**

---

## 目录

- [🚨 平台变现与 AI 合规红线（2026–2027）](#-平台变现与-ai-合规红线20262027)
- [⚡ 快速起步工具栈（国内直连版 & 出海美金版）](#-快速起步工具栈国内直连版--出海美金版)
- [📝 选题调研与脚本写作](#-选题调研与脚本写作)
- [🎙️ AI 配音与开源本地 TTS](#️-ai-配音与开源本地-tts)
  - [商业配音与声音克隆](#商业配音与声音克隆)
  - [开源本地免费 TTS（¥0/月）](#开源本地免费-tts0月)
- [🎬 AI 视频生成（出海旗舰 & 国内直连）](#-ai-视频生成出海旗舰--国内直连)
- [✂️ 视频剪辑、动态字幕与长转短切片](#️-视频剪辑动态字幕与长转短切片)
- [🖼️ 封面缩略图与视觉素材](#️-封面缩略图与视觉素材)
- [🎵 背景音乐与音效](#-背景音乐与音效)
- [⚡ 自动化工作流与多平台发布](#-自动化工作流与多平台发布)
- [📊 数据分析与频道 SEO](#-数据分析与频道-seo)
- [📁 项目协作与排期管理](#-项目协作与排期管理)
- [🛠️ 开源视频流水线、AI 漫剧与 Agent Skills](#️-开源视频流水线ai-漫剧与-agent-skills)
- [📚 深度指南与玩法手册（英文）](#-深度指南与玩法手册英文)
- [🎯 热门不露脸赛道与 CPM 参考](#-热门不露脸赛道与-cpm-参考)
- [🔗 创作者社区](#-创作者社区)
- [🤝 参与贡献](#-参与贡献)

---

## 🚨 平台变现与 AI 合规红线（2026–2027）

花钱买工具前，先看清平台官方规则，避免做到一半被取消收益（Demonetized）：

1. **YouTube YPP 门槛将于 2027 年 2 月 1 日正式翻倍**（[YouTube 官方公告](https://support.google.com/youtube/answer/12843009)）：
   - **2027 年 2 月 1 日起**，新频道申请完整广告/Premium 分成（Full YPP）门槛提高至：**1,000 订阅 + 近 365 天 8,000 小时有效观看时长**，或 **近 90 天 2,000 万次有效 Shorts 播放**（原为 4,000 小时 / 1,000 万次）。
   - 已加入 YPP 的老频道不受入驻门槛影响，但**必须在 2027 年 1 月 31 日前**于 YouTube Studio 接受新条款；2027 年 2 月起，Shorts Creator Pool 月度分成需维持近 90 天 1,000 万次有效 Shorts 播放。
   - 早期变现档（粉丝赞助 / Shopping）维持 500 订阅 + 3,000 小时或 300 万 Shorts 播放不变。
2. **YouTube「非真实内容（Inauthentic Content）」政策**（[官方创收政策](https://support.google.com/youtube/answer/1311392)）：
   - YouTube **不禁止**不露脸频道，也**不禁止**用 AI 工具，但严打**套模板、批量生产、缺乏原创观点或叙事、换汤不换药**的流水线内容。
   - **过审底线**：审核员随机点开你 10 条视频，必须能看出原创脚本、节奏编排或独特观点，而不是同一个模板换关键词跑出来的“AI 垃圾”。
3. **AI 合成内容主动披露**（[官方披露指南](https://support.google.com/youtube/answer/14328491)）：
   - 涉及逼真的虚拟人物、未发生的现实事件或仿声时，在 YouTube Studio 勾选「经修改或合成的内容」。官方明确说明：**如实披露不会限流，也不影响 YPP 变现**。
   - **国内平台提示**：在抖音、视频号、B 站、小红书发布 AI 生成画面/漫剧时，同样需按各平台规定勾选「AI 生成内容」标识，避免限流或下架。

---

## ⚡ 快速起步工具栈（国内直连版 & 出海美金版）

先手动做完前 5 条视频验证完播率与点击率，再谈自动化。

| 方案路线 | 预算/月 | 推荐组合 |
|---|---|---|
| **国内直连 · 零成本起步** | ¥0 | DeepSeek / 豆包写脚本 → **IndexTTS / 剪映配音** → **即梦 AI / 可灵**每日免费积分出镜头 → **剪映专业版**成片 |
| **国内直连 · AI 漫剧 / 解说进阶** | ¥100–300 | DeepSeek / Kimi 改编分镜 → **即梦（Seedance 2.0/2.5）+ Vidu / 可灵**控角色一致性 → **Fish Audio / IndexTTS** → 剪映 / `LocalMiniDrama` |
| **出海美金 · 零成本起步** | $0 | ChatGPT / Gemini 免费版 → **Kokoro-82M** 或 CapCut 配音 → CapCut / DaVinci Resolve + **Clips Kitty** → Canva 免费版 |
| **出海美金 · 稳健主力栈** | ~$30–60 | Claude 写英文长脚本 → **ElevenLabs / Fish Audio** → **Kling / Seedance / Hailuo** B-roll → CapCut + Canva + **Feed Thumbnail** |
| **出海美金 · 自动化批量栈** | $100+ | **GetYouTubeTranscript** + Claude → ElevenLabs / Cartesia → Kling / Veo / Runway → Descript + **n8n / Make** → VidIQ |
| **开源自托管（极客降本）** | 仅算力/API | 开源大模型 / API → **Qwen3-TTS / Kokoro-82M** → **MoneyPrinterTurbo / NarratoAI / Orkas-VideoStudio** → FFmpeg |

**投入优先级**：先把预算花在**脚本与前 3 秒 Hook**（决定完播与能否过 YPP），其次**配音自然度**（留存），再次**封面点击率（CTR）**，最后才追求昂贵的视频大模型。

---

## 📝 选题调研与脚本写作

挖低竞争高变现选题、拆解竞品爆款结构、写口语化播音脚本。

| 工具 | 核心用途 | 定价 | 评测 |
|---|---|---|---|
| [DeepSeek](https://www.deepseek.com/) | **国内直连**，逻辑与长篇网文/解说改编强，性价比极高 | 免费 / 按量 API | — |
| [豆包](https://www.doubao.com/) | **国内直连**，创意发散与中文口语短视频脚本顺手 | 免费 | — |
| [Kimi](https://www.kimi.com/) | **国内直连**，长文档资料消化与自然中文语感出色 | Freemium | — |
| [ChatGPT](https://chatgpt.com/) | 英文脚本、标题、Hook 与大纲迭代主力 | Freemium | [Review](https://faceless.directory/directory/chatgpt) |
| [Claude](https://claude.ai/) | 长视频解说脚本质感稳，去“AI 味”能力强 | Freemium | [Review](https://faceless.directory/directory/claude) |
| [Gemini](https://gemini.google.com/) | 结合搜索与多模态能力做竞品视频拆解和脚本初稿 | Freemium | — |
| [Grok](https://x.ai/) | 热点趋势追踪与快速起稿 | Freemium | — |
| [GetYouTubeTranscript](https://getyoutubetranscript.com/) | 一键抓取同赛道爆款 YouTube 带时间戳字幕，方便拆结构与 Hook | Freemium | — |
| [NicheCue](https://facelessyoutubeniches.com/) | 免费不露脸 YouTube 选题库 + 脚本大纲，适合 B-roll/解说频道 | 免费 | — |
| [Jasper](https://jasper.ai/) | 偏品牌营销口吻的英文文案工具 | $49/月起 | [Review](https://faceless.directory/directory/jasper) |
| [Copy.ai](https://copy.ai/) | 标题、简介与社媒短文案模板 | Freemium | [Review](https://faceless.directory/directory/copyai) |
| [Writesonic](https://writesonic.com/) | 带联网核查的内容写作工具 | Freemium | [Review](https://faceless.directory/directory/writesonic) |

---

## 🎙️ AI 配音与开源本地 TTS

声音质感是不露脸频道留存率的第一杠杆。

### 商业配音与声音克隆

| 工具 | 核心用途 | 定价 | 评测 |
|---|---|---|---|
| [ElevenLabs](https://elevenlabs.io/) | 英文/多语种配音标杆，支持声音克隆、音效与多语配音翻译 | $5/月起 | [Review](https://faceless.directory/directory/elevenlabs) |
| [Fish Audio](https://fish.audio/) | **中英文表现均很强**，声音克隆自然，价格对个人创作者友好 | Freemium | — |
| [MiniMax Audio](https://www.minimax.io/audio) | 高拟真多语种语音与克隆，情绪表现自然、API 性价比高 | Freemium | — |
| [Cartesia](https://cartesia.ai/) | 超低延迟自然语音，适合自动化管线 | 付费 / 免费额度 | — |
| [Murf AI](https://murf.ai/) | 棚级旁白配音 + 轻量时间轴对齐 | $19/月起 | [Review](https://faceless.directory/directory/murf) |
| [WellSaid](https://www.wellsaid.io/) | 企业解说/科普风格英文专业人声 | 付费 | [Review](https://faceless.directory/directory/wellsaid) |
| [Speechify](https://speechify.com/) | 自然人声、语速控制与配音 | Freemium | [Review](https://faceless.directory/directory/speechify) |
| [OpenAI TTS](https://developers.openai.com/api/docs/guides/text-to-speech) | 稳定的 API 语音接口，适合脚本化批量管线 | 按量付费 | — |

### 开源本地免费 TTS（¥0/月）

| 项目 | 特点 | 协议 |
|---|---|---|
| [Kokoro-82M](https://github.com/hexgrad/kokoro) | 82M 轻量开源标杆，**纯 CPU 也能流畅跑**，覆盖 8+ 语种 54 音色 | Apache-2.0 |
| [IndexTTS](https://github.com/index-tts/index-tts) | B 站开源工业级零样本 TTS（★25k+），**中文解说/漫剧情绪与断句控制极强** | 开源 |
| [CosyVoice](https://github.com/QwenAudio/CosyVoice) | 阿里开源多语种情感配音与克隆（★24k+），中文与方言表现突出 | Apache-2.0 |
| [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) | 10 语种流式开源 TTS，3 秒零样本克隆，支持本地量化推理 | Apache-2.0 |

> **已停服清理提示**：**Play.ht** 于 2025 年 12 月 31 日永久停服（团队被 Meta 收购）；**LOVO AI** 于 2026 年 5 月申请 Chapter 7 破产清算。老项目请尽快迁移至 ElevenLabs、Fish Audio、MiniMax Audio 或上方开源方案。

---

## 🎬 AI 视频生成（出海旗舰 & 国内直连）

文生/图生视频、角色一致性漫剧、数字人及一键脚本成片工具。

| 工具 | 核心用途 | 网络 / 定价 | 评测 |
|---|---|---|---|
| [可灵 AI (Kling AI)](https://klingai.com/) | **国内直连 & 海外均强**，Kling 3/4 级动作与多镜头运镜，短视频 B-roll / 写实主力 | 直连 · Freemium | — |
| [即梦 AI（国内）](https://jimeng.jianying.com/) / [Dreamina（海外）](https://dreamina.capcut.com/) | 字节 **Seedance 2.0/2.5** 底座，图生视频与多参考角色一致性王者，**AI 漫剧首选** | 直连 · Freemium | — |
| [海螺 AI (MiniMax Hailuo)](https://hailuoai.video/)（[国内入口](https://hailuoai.com/video)） | MiniMax H3 系列，高性价比文生/图生视频，支持原生音画同步 | 直连 · Freemium | — |
| [Vidu](https://www.vidu.com/) | 参考生视频人物/场景一致性强，动漫/国漫解说常用 | 直连 · Freemium | — |
| [通义万相 (Alibaba Wan)](https://wan.video/) | Wan 3.0 云端 + 开源权重，1080p 高性价比，可自部署 | 直连 · Freemium / 开源 | — |
| [Google Veo](https://deepmind.google/models/veo/) | Veo 3.1 旗舰电影级视频 + 原生音效/对话生成 | 需海外 · 付费/Gemini | — |
| [Runway](https://runway.com/) | Gen-4 / Gen-4.5 专业镜头控制与后期生态 | 需海外 · $12/月起 | [Review](https://faceless.directory/directory/runway) |
| [Luma Dream Machine](https://lumalabs.ai/) | 快速电影感画面与首尾帧过渡 | 需海外 · Freemium | — |
| [Higgsfield AI](https://higgsfield.ai/) | 主打角色一致性的不露脸动画频道 & 电影运镜工作台 | 需海外 · $15/月起 | — |
| [PixVerse](https://pixverse.ai/) | 社媒短视频特效与快速图生视频 | Freemium | — |
| [Magic Hour](https://magichour.ai/) | 一站式 AI 视频生成、视频转绘、换脸与口型同步 | Freemium | — |
| [Pika](https://pika.art/) | 创意特效与轻量化短视频镜头 | Freemium | [Review](https://faceless.directory/directory/pika) |
| [InVideo AI](https://invideo.io/) | 英文主题/脚本一键生成带素材与配音的完整视频 | 需海外 · Freemium/付费 | [Review](https://faceless.directory/directory/invideo) |
| [Pictory](https://pictory.ai/) | 博客/脚本快速转库存素材配音视频 | 需海外 · 付费/试用 | [Review](https://faceless.directory/directory/pictory) |
| [Fliki](https://fliki.ai/) | 文本转视频 + 多语种 AI 配音 | 需海外 · Freemium | [Review](https://faceless.directory/directory/fliki) |
| [HeyGen](https://heygen.com/) | AI 数字人口播 + 175+ 语种视频翻译对口型 | Freemium / 付费 | [Review](https://faceless.directory/directory/heygen) |
| [Synthesia](https://synthesia.io/) | 商业讲解/培训型数字人视频 | 付费 / 免费试用 | [Review](https://faceless.directory/directory/synthesia) |
| [D-ID](https://d-id.com/) | 单张照片生成开口说话人物 | Freemium | [Review](https://faceless.directory/directory/d-id) |
| [Lumen5](https://lumen5.com/) | 文章/脚本转品牌科普视频 | Freemium | [Review](https://faceless.directory/directory/lumen5) |

> **实测提示**：OpenAI 已于 2026 年 3 月停运 Sora App 与 Sora 2 API。当前做系列化不露脸内容，建议以**即梦（先出定妆图再图生视频）+ 可灵 / 海螺 / Veo 补镜头**组合出片，可控度远高于纯文生盲抽。

---

## ✂️ 视频剪辑、动态字幕与长转短切片

| 工具 | 核心用途 | 定价 | 评测 |
|---|---|---|---|
| [剪映专业版（国内）](https://www.capcut.cn/) / [CapCut（出海）](https://capcut.com/) | 不露脸短视频剪辑国民首选：自动字幕、内置配音、模板齐全 | Freemium | [Review](https://faceless.directory/directory/capcut) |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | 专业免费非线性剪辑、调色与动态图形 | 免费 / Studio 买断 | [Review](https://faceless.directory/directory/davinci) |
| [Descript](https://descript.com/) | 像改 Word 文档一样剪英文视频，适合播客与知识口播 | Freemium / 付费 | [Review](https://faceless.directory/directory/descript) |
| [Adobe Premiere Pro](https://www.adobe.com/products/premiere.html) | 行业标准专业剪辑 | 付费 | [Review](https://faceless.directory/directory/premiere) |
| [Final Cut Pro](https://www.apple.com/final-cut-pro/) | Mac 端高效剪辑 | $299 买断 | [Review](https://faceless.directory/directory/finalcut) |
| [VEED](https://veed.io/) | 浏览器在线剪辑 + AI 字幕降噪 | Freemium | [Review](https://faceless.directory/directory/veed) |
| [Kapwing](https://kapwing.com/) | 协作型在线剪辑与字幕 | Freemium | [Review](https://faceless.directory/directory/kapwing) |
| [Opus Clip](https://opus.pro/) | 长视频一键切高传播短视频，带爆款评分 | Freemium / $15/月起 | [Review](https://faceless.directory/directory/opus-clip) |
| [Clips Kitty](https://github.com/ColinGPT9/clips-studio) | **开源本地版 Opus Clip 替代**（Ollama + Whisper，零月费） | 免费（AGPL-3.0） | — |
| [Submagic](https://www.submagic.co/) | 英文 Shorts 动态卡点字幕与 B-roll | 付费 | — |
| [Vizard](https://vizard.ai/) | 长转短 AI 切片工具 | Freemium | — |
| [Munch](https://www.munchstudio.com/) | 结合热点趋势的 AI 二创切片 | 付费 | — |
| [Karaoke Captions](https://karaokecaptions.com/) | 本地逐词高亮字幕与 SRT/VTT 编辑，导出无水印 | Freemium | — |

---

## 🖼️ 封面缩略图与视觉素材

封面决定点击率（CTR）：画面主体单一明确 + 2–4 个高对比大字，远胜堆满元素。

| 工具 | 核心用途 | 定价 | 评测 |
|---|---|---|---|
| [Midjourney](https://midjourney.com/) | 艺术感封面、故事插画与角色概念图 | $10/月起 | [Review](https://faceless.directory/directory/midjourney) |
| [ChatGPT (GPT Image)](https://chatgpt.com/) | 写实画面与精准带字出图（已迭代取代旧版 DALL·E 3） | Freemium | [Review](https://faceless.directory/directory/dalle) |
| [即梦 AI](https://jimeng.jianying.com/) | **国内直连**，中文文字渲染与角色定妆图极强 | Freemium | — |
| [FLUX (Black Forest Labs)](https://bfl.ai/) | 高画质开源权重 & API 图像模型 | 开源 / API | — |
| [Ideogram](https://ideogram.ai/) | 英文海报/封面内嵌文字准确率高 | Freemium | [Review](https://faceless.directory/directory/ideogram) |
| [Recraft](https://www.recraft.ai/) | 风格统一的矢量插画与系列频道视觉资产 | Freemium | — |
| [Canva](https://canva.com/) | 封面排版加字、复用频道模板最快 | Freemium | [Review](https://faceless.directory/directory/canva) |
| [Leonardo.ai](https://leonardo.ai/) | 风格可控的连续插画素材 | Freemium | [Review](https://faceless.directory/directory/leonardo) |
| [Adobe Firefly](https://firefly.adobe.com/) | 商业版权安全扩图与局部重绘 | Freemium | [Review](https://faceless.directory/directory/firefly) |
| [Photoshop](https://www.adobe.com/products/photoshop.html) | 专业抠图、调色与最终精修 | 付费 | [Review](https://faceless.directory/directory/photoshop) |
| [Feed Thumbnail](https://feedthumbnail.com/youtube-thumbnail-size) | 免费浏览器预览封面在真实 YouTube 推荐流里的视觉对比效果 | 免费 | — |

---

## 🎵 背景音乐与音效

做变现频道务必确认版权与 YouTube Content ID 规则，别因一首 BGM 被分走全部广告费。

| 工具 | 核心用途 | 定价 |
|---|---|---|
| [Suno](https://suno.com/) | AI 生成背景乐与歌曲（商用需付费订阅档） | Freemium |
| [Udio](https://www.udio.com/) | 高质量 AI 音乐与纯音乐配乐 | Freemium |
| [Epidemic Sound](https://www.epidemicsound.com/) | YouTube 频道版权白名单音乐与音效库 | 订阅 |
| [Artlist](https://artlist.io/) | 音乐、音效与视频素材打包商用授权 | 订阅 |
| [Pixabay Music](https://pixabay.com/music/) | 免费配乐（使用前仍需留意单曲 Content ID 提示） | 免费 |

---

## ⚡ 自动化工作流与多平台发布

| 工具 | 核心用途 | 定价 | 评测 |
|---|---|---|---|
| [n8n](https://n8n.io/) | 开源可自托管工作流引擎，高频自动化成本最低 | 开源免费 / 云版 | [Review](https://faceless.directory/directory/n8n) |
| [Make](https://make.com/) | 可视化流程编排，多步骤自动化比 Zapier 划算 | Freemium / $9/月起 | [Review](https://faceless.directory/directory/make) |
| [Zapier](https://zapier.com/) | 生态连接最广的无代码自动化工具 | Freemium / $20/月起 | [Review](https://faceless.directory/directory/zapier) |
| [Repurpose.io](https://repurpose.io/) | YouTube / TikTok / IG / FB 自动跨平台分发 | 付费 | [Review](https://faceless.directory/directory/repurpose) |
| [Metricool](https://metricool.com/) | 多平台定时发布 + 统一数据看板 | Freemium | — |
| [Buffer](https://buffer.com/) | 轻量级个人社媒排期 | Freemium | [Review](https://faceless.directory/directory/buffer) |
| [Hootsuite](https://hootsuite.com/) | 团队级多账号管理与审批 | 付费 | [Review](https://faceless.directory/directory/hootsuite) |

---

## 📊 数据分析与频道 SEO

| 工具 | 核心用途 | 定价 | 评测 |
|---|---|---|---|
| [YouTube Studio](https://studio.youtube.com/) | 官方留存曲线、点击率、封面 A/B 测试与收益数据（第一步必看） | 免费 | — |
| [TubeBuddy](https://tubebuddy.com/) | YouTube 关键词、标签与 A/B 测试 | Freemium | [Review](https://faceless.directory/directory/tubebuddy) |
| [VidIQ](https://vidiq.com/) | 爆款异常值（Outlier）监控与竞品关键词研究 | Freemium | [Review](https://faceless.directory/directory/vidiq) |
| [Social Blade](https://socialblade.com/) | 公开频道增长与预估播放量查询 | 免费 | [Review](https://faceless.directory/directory/socialblade) |
| [Google Trends](https://trends.google.com/trends/) | 全球/分地区搜索热度与 YouTube 趋势验证 | 免费 | — |

---

## 📁 项目协作与排期管理

| 工具 | 核心用途 | 定价 | 评测 |
|---|---|---|---|
| [Notion](https://www.notion.com/) | 内容日历、脚本模板库与频道 SOP | Freemium | [Review](https://faceless.directory/directory/notion) |
| [Airtable](https://airtable.com/) | 表格型数据库，极适合对接 n8n / Make 驱动自动发片 | Freemium | [Review](https://faceless.directory/directory/airtable) |
| [ClickUp](https://clickup.com/) | 多频道矩阵团队（编剧+剪辑）任务流 | Freemium | [Review](https://faceless.directory/directory/clickup) |
| [Trello](https://trello.com/) | 极简看板（`选题 → 脚本 → 配音 → 剪辑 → 已发`） | Freemium | [Review](https://faceless.directory/directory/trello) |

---

## 🛠️ 开源视频流水线、AI 漫剧与 Agent Skills

适合想省掉 SaaS 订阅费、或用开源代码搭建私有生产线的创作者：

| 开源项目 | 解决什么问题 | 亮点 |
|---|---|---|
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | 输入主题/关键词，全自动生成脚本、配音、素材、字幕与高清短视频 | ★145k+，中英双语，持续活跃 |
| [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2) | Python 自动化 YouTube Shorts 与社媒视频工作流 | ★32k+ |
| [linyqh/NarratoAI](https://github.com/linyqh/NarratoAI) | 一站式 AI 影视解说 + 自动化剪辑工具 | ★11k+ |
| [kaomei/stickman-video-director](https://github.com/kaomei/stickman-video-director) | AI Agent Skill（支持 Claude Code / Codex），脚本直出火柴人动画视频 | ★7.5k+，持续活跃 |
| [cporter202/automate-faceless-content](https://github.com/cporter202/automate-faceless-content) | 长短不露脸 YouTube 频道自动化实战蓝图 | ★3.3k+ |
| [xuanyustudio/LocalMiniDrama](https://github.com/xuanyustudio/LocalMiniDrama) | 本地开源 AI 短剧 & 漫剧一站式平台，支持接入 Seedance 2，数据不出本机 | ★2.5k+，持续活跃 |
| [gyoridavid/short-video-maker](https://github.com/gyoridavid/short-video-maker) | 基于 MCP 协议的短视频生成器（Kokoro TTS + Whisper + Remotion） | ★1.5k+ |
| [ColinGPT9/clips-studio](https://github.com/ColinGPT9/clips-studio) | **Clips Kitty**：本地开源免费 Opus Clip 替代（Ollama + Whisper） | ★620+，持续活跃 |
| [Orkas-AI/Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) | 让编程 Agent（Claude Code / Codex / Cursor）直接剪辑时间线并渲染 MP4 | ★350+，MIT，持续活跃 |
| [Dark2C/Viral-Faceless-Shorts-Generator](https://github.com/Dark2C/Viral-Faceless-Shorts-Generator) | 容器化热点 → 脚本 → TTS → FFmpeg 短视频生成 | ★120+ |
| [aruntemme/n8n-faceless-youtube](https://github.com/aruntemme/n8n-faceless-youtube) | 开箱即用的 n8n 不露脸 YouTube 工作流模板 | n8n |

**AI 漫剧 & 提示词开源技能库：**
- [ZeroLu/awesome-seedance](https://github.com/ZeroLu/awesome-seedance) — Seedance 2.0/2.5 高质量提示词与工作流合集
- [UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) — AI 短剧/漫剧专用剧本、分镜与视频提示词 Agent Skill 合集

---

## 📚 深度指南与玩法手册（英文）

托管在 [faceless.directory](https://faceless.directory) 的配套深度文章：

- **入门起号**：[如何启动不露脸 YouTube 频道](https://faceless.directory/blog/how-to-start-faceless-youtube-channel) · [20 个能赚钱的不露脸频道点子](https://faceless.directory/blog/faceless-youtube-channel-ideas-2025) · [零预算免费工具栈](https://faceless.directory/blog/zero-budget-faceless-youtube-guide)
- **工具横评**：[AI 语音横评（ElevenLabs vs Murf）](https://faceless.directory/blog/elevenlabs-vs-murf-vs-play) · [AI 视频模型横评](https://faceless.directory/blog/pika-vs-runway-vs-sora) · [CapCut 不露脸剪辑工作流](https://faceless.directory/blog/capcut-faceless-video-editing)
- **自动化与变现**：[不露脸频道自动化指南](https://faceless.directory/blog/faceless-youtube-automation-guide) · [YouTube Shorts SEO](https://faceless.directory/blog/youtube-shorts-seo-uncovered) · [AdSense 之外的 7 种变现方式](https://faceless.directory/blog/faceless-youtube-monetization) · [联盟分销变现策略](https://faceless.directory/blog/affiliate-marketing-faceless-channels) · [YouTube AI 规则与防封收益避坑](https://faceless.directory/blog/youtube-ai-monetization-traps)
- **垂类剧本**：[Reddit 故事频道](https://faceless.directory/blog/reddit-stories-youtube-channel-guide) · [恐怖悬疑解说](https://faceless.directory/blog/horror-narration-channel-guide) · [AI 资讯频道](https://faceless.directory/blog/ai-news-channel-guide) · [冥想助眠高 CPM 频道](https://faceless.directory/blog/meditation-sleep-channel-guide)

---

## 🎯 热门不露脸赛道与 CPM 参考

*(参考欧美 Tier-1 YouTube AdSense 区间；国内视频号/抖音/中视频收益模型与受众地区差异较大，另按平台结算。)*

| 赛道 | 欧美典型 CPM | 难度 | 核心配置 |
|---|---|---|---|
| **财经 / 投资理财** | $15–40 | 高 | Claude 深度脚本 + ElevenLabs + 动态图表/剪映 |
| **科技 / AI 教程解说** | $8–20 | 中 | 录屏演示 + 真实测评 + ElevenLabs / Kokoro |
| **罪案纪录 / 历史深挖** | $6–15 | 中 | 深度资料检索 + 悬疑旁白 + 可灵/Runway B-roll |
| **科普动画 / 火柴人解说** | $6–15 | 中 | 原创文案 + `stickman-video-director` / 动效 |
| **冥想助眠 / 氛围白噪音** | $5–15 | 低 | 氛围音频 + 慢镜画面（切忌整条素材循环复用） |
| **恐怖故事 / 灵异怪谈 / AI 漫剧** | $4–10 | 低–中 | 原创改编 + IndexTTS/Fish + 即梦 Seedance / Vidu |
| **游戏剧情考据与杂谈** | $3–8 | 中 | 实机素材 + 强观点解说 |
| **Reddit 故事 / 热点短视频** | $2–8 | 低 | YPP 审核极严，必须加入原创评论与画面编排 |

---

## 🔗 创作者社区

- [r/NewTubers](https://reddit.com/r/NewTubers) — 新手 YouTuber 起号与反馈交流
- [r/PartneredYoutube](https://reddit.com/r/PartneredYoutube) — 已开通变现创作者社区，YPP 新政一手讨论
- [r/youtubers](https://reddit.com/r/youtubers) — 综合 YouTube 运营社区
- [r/FacelessYouTube](https://www.reddit.com/r/FacelessYouTube/) — 不露脸频道垂直讨论版
- [Indie Hackers](https://indiehackers.com/) — 创作者商业化与独立变现讨论

---

## 🤝 参与贡献

欢迎提 PR 或 Issue 补充优质工具、修正死链、完善中文/多语种本地化内容，详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

- **快速提交工具**：直接填写 [Tool Submission Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml)。
- **收录原则**：只收真实可用、无 UTM 追踪或返佣垃圾链接、免费/开源或有诚意免费额度的工具。

如果这份清单帮你省下了挑工具和踩坑的时间，欢迎点一个 **Star** 支持持续更新。

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Public domain (CC0 1.0).

---

**由 [Faceless Directory](https://faceless.directory) 维护** — 不露脸自媒体创作者的工具栈与实战指南。

[![Star History Chart](https://api.star-history.com/svg?repos=sasharun/awesome-faceless&type=Date)](https://star-history.com/#sasharun/awesome-faceless&Date)
