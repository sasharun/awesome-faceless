# Awesome 顔出しなし動画制作・AI ツール大全 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🌐 [English](README.md) | [简体中文](README.zh-CN.md) | [Español](README.es.md) | **日本語** | [한국어](README.ko.md)

[![Stars](https://img.shields.io/github/stars/sasharun/awesome-faceless?style=social)](https://github.com/sasharun/awesome-faceless)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Last update](https://img.shields.io/badge/last%20update-2026--11-blue.svg)](https://github.com/sasharun/awesome-faceless)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](LICENSE)

> **顔出しなし YouTube（解説チャンネル・AI ショート動画・TikTok）** 運営のための **厳選 AI ツール & オープンソース自動化パイプライン 100選**。台本作成、商用・ローカル無料 TTS 読み上げ、次世代動画生成（Kling / Seedance / Veo / Wan / Hailuo / Runway）、編集・切り抜き・字幕、自動化、SEO、そして **2026–2027 年の YouTube 収益化（YPP）新ポリシー** まで網羅しています。
>
> 関連キーワード：*顔出しなし YouTube* · *YouTube 自動化* · *AI ショート動画* · *AI 読み上げ / TTS* · *動画生成 AI* · *切り抜き自動化*

**🔗 レビュー・構成例付き完全ディレクトリ（英語）：** [faceless.directory](https://faceless.directory)  
**📩 ツールの提案・リンク切れ報告：** [Tool Submission Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml) または [Pull Request](CONTRIBUTING.md) からお送りください。

顔出しなしで収益化チャンネルを育てる流れ：**リサーチ・台本 → AI 音声 → 映像 / B-roll / アニメーション → 編集・テロップ → 投稿自動化 → 分析**。

---

## このリストの特徴

リンク切れやアフィリエイト宣伝ばかりの AI リストと違い、**顔出しなし動画の制作ワークフローに特化して実働確認済み**のツールだけを掲載しています：

- 実作業の順番で整理（`リサーチ → 台本 → 音声 → 映像 → 編集 → 投稿・分析`）
- 料金の明記＋**無料で使えるオープンソース代替**（月 `$0` / `$30–60` / プロ自動化構成に対応）
- 終了・破綻サービスを除外済み（**Play.ht** は Meta の PlayAI 買収後に 2025 年 12 月終了、**LOVO AI** は 2026 年 5 月に Chapter 7 破産申請、**OpenAI Sora** は 2026 年 3 月提供終了）
- 2026 年末時点の最新環境を反映：**Kling 3/4、Seedance 2.5、Wan 3.0、Veo 3.1、MiniMax H3、Kokoro-82M / Qwen3-TTS、AI エージェント動画編集**

---

## 目次

- [🚨 YouTube 収益化 & AI コンテンツ規約（2026–2027）](#-youtube-収益化--ai-コンテンツ規約20262027)
- [⚡ すぐ始められるおすすめ構成（スタック）](#-すぐ始められるおすすめ構成スタック)
- [📝 台本作成・企画リサーチ](#-台本作成企画リサーチ)
- [🎙️ 音声合成・AI ナレーション（TTS）](#️-音声合成ai-ナレーションtts)
  - [商用 TTS・音声クローン](#商用-tts音声クローン)
  - [オープンソース・ローカル無料 TTS（月額 ¥0）](#オープンソースローカル無料-tts月額-0)
- [🎬 AI 動画生成](#-ai-動画生成)
- [✂️ 動画編集・自動字幕・切り抜き](#️-動画編集自動字幕切り抜き)
- [🖼️ サムネイル・画像生成](#️-サムネイル画像生成)
- [🎵 BGM・効果音](#-bgm効果音)
- [⚡ 投稿自動化・ワークフロー](#-投稿自動化ワークフロー)
- [📊 分析・YouTube SEO](#-分析youtube-seo)
- [📁 進行管理・台本管理](#-進行管理台本管理)
- [🛠️ オープンソース自動化パイプライン & Agent Skills](#️-オープンソース自動化パイプライン--agent-skills)
- [📚 ガイド・運用プレイブック（英語）](#-ガイド運用プレイブック英語)
- [🎯 ジャンル別アイデア & CPM 目安](#-ジャンル別アイデア--cpm-目安)
- [🔗 コミュニティ](#-コミュニティ)
- [🤝 コントリビュート](#-コントリビュート)

---

## 🚨 YouTube 収益化 & AI コンテンツ規約（2026–2027）

ツール課金の前に、収益化剥奪（アカウント停止・YPP 審査落ち）を避けるための公式ルールを押さえておきましょう：

1. **2027 年 2 月 1 日より YPP（広告・Premium 収益）の新規申請基準が倍増**（[YouTube 公式ヘルプ](https://support.google.com/youtube/answer/12843009)）：
   - **2027 年 2 月 1 日以降**の新規申請条件は **登録者 1,000 人＋直近 365 日の有効総再生時間 8,000 時間**、または **直近 90 日の有効ショート動画視聴 2,000 万回**（従来の 4,000 時間 / 1,000 万回から引き上げ）。
   - すでに YPP に参加済みのチャンネルは資格維持されますが、**2027 年 1 月 31 日までに** YouTube Studio で改定規約への同意が必要です。また 2027 年 2 月以降、Shorts Creator Pool の月次分配を受けるには直近 90 日で 1,000 万回の有効ショート視聴維持が必要です。
   - ファン向け機能（メンバーシップ・ショッピング等）の早期解放条件（登録者 500 人＋3,000 時間またはショート 300 万回）は変更ありません。
2. **「非本物コンテンツ（Inauthentic Content）」ポリシー**（旧「繰り返しの多いコンテンツ」、[公式 YPP ポリシー](https://support.google.com/youtube/answer/1311392)）：
   - 顔出しなしチャンネルや AI ツールの使用自体は**明確に許可**されています。NG なのは、**テンプレート量産・独自解説や構成のない使い回し動画**です。
   - 審査員が直近 10 本を見たときに「すべて同じテンプレの単語差し替え」に見えないよう、独自の台本・構成・編集意図を入れることが必須です。
3. **リアルな改変・合成コンテンツの開示義務**（[公式開示ガイド](https://support.google.com/youtube/answer/14328491)）：
   - 実在するように見える AI 生成人物・出来事・音声を含む場合は YouTube Studio で開示ラベルをオンにします。公式によると、**開示してもおすすめ表示や収益化に悪影響はありません**。

---

## ⚡ すぐ始められるおすすめ構成（スタック）

自動化する前に、まず手動で 5 本公開してクリック率（CTR）と視聴維持率を検証しましょう。

| 構成 | 月額目安 | ツール連携 |
|---|---|---|
| **ゼロ予算（無料）** | $0 | ChatGPT / Gemini 無料枠 → **Kokoro-82M / Qwen3-TTS** または CapCut 音声 → CapCut / DaVinci Resolve + **Clips Kitty** → Canva 無料版 |
| **収益化スターター** | ~$30–60 | Claude / ChatGPT → **ElevenLabs / Fish Audio** → CapCut + **Kling / Hailuo** B-roll → Canva + **Feed Thumbnail** |
| **ショート＆切り抜き量産** | ~$30–70 | **GetYouTubeTranscript** + Claude → ElevenLabs → **Seedance / Kling** → **Opus Clip / Submagic** または **Clips Kitty** → Metricool |
| **プロ自動化** | $100+ | Claude 台本 → ElevenLabs / Cartesia → **Kling / Seedance / Veo / Runway** → Descript → **n8n / Make** → VidIQ |
| **セルフホスト（OSS）** | API / GPU のみ | ローカル LLM / API → **Qwen3-TTS / Kokoro-82M** → **Wan 3.0 / MoneyPrinterTurbo / Orkas-VideoStudio** → FFmpeg |

**投資の優先順位：** ① **台本と冒頭 3 秒のフック**（YPP 通過＋維持率）→ ② **音声の自然さ** → ③ **サムネイル**（CTR）→ ④ 最後に高価な動画生成モデル。

---

## 📝 台本作成・企画リサーチ

| ツール | 概要 | 料金 | レビュー |
|---|---|---|---|
| [ChatGPT](https://chatgpt.com/) | 台本・タイトル・構成案の高速生成 | Freemium | [Review](https://faceless.directory/directory/chatgpt) |
| [Claude](https://claude.ai/) | 長尺解説台本でも自然な語り口を維持しやすい | Freemium | [Review](https://faceless.directory/directory/claude) |
| [Gemini](https://gemini.google.com/) | リサーチ・動画マルチモーダル分析・台本下書き | Freemium | — |
| [Grok](https://x.ai/) | 最新トレンドを反映した企画出し | Freemium | — |
| [GetYouTubeTranscript](https://getyoutubetranscript.com/) | 伸びている競合動画のタイムスタンプ付き字幕を取得して構成研究 | Freemium | — |
| [NicheCue](https://facelessyoutubeniches.com/) | 顔出しなしチャンネル向けの無料ネタ帳・構成アウトライン集 | 無料 | — |
| [Jasper](https://jasper.ai/) | マーケティング寄りのコピーライティング | $49/月〜 | [Review](https://faceless.directory/directory/jasper) |
| [Copy.ai](https://copy.ai/) | タイトル・概要欄向けテンプレート | Freemium | [Review](https://faceless.directory/directory/copyai) |
| [Writesonic](https://writesonic.com/) | 検索連携型の記事・台本生成 | Freemium | [Review](https://faceless.directory/directory/writesonic) |

---

## 🎙️ 音声合成・AI ナレーション（TTS）

### 商用 TTS・音声クローン

| ツール | 概要 | 料金 | レビュー |
|---|---|---|---|
| [ElevenLabs](https://elevenlabs.io/) | 日本語・英語ともに高品質な読み上げ、音声クローン、効果音、吹き替え | $5/月〜 | [Review](https://faceless.directory/directory/elevenlabs) |
| [Fish Audio](https://fish.audio/) | 日本語含む多言語対応・自然な音声クローン、個人向け価格が強み | Freemium | — |
| [MiniMax Audio](https://www.minimax.io/audio) | 表現力豊かな多言語音声合成と高コスパ API | Freemium | — |
| [Cartesia](https://cartesia.ai/) | 超低遅延で自然な音声合成 | 有料 / 無料枠 | — |
| [Murf AI](https://murf.ai/) | ナレーション生成＋タイムライン調整 | $19/月〜 | [Review](https://faceless.directory/directory/murf) |
| [WellSaid](https://www.wellsaid.io/) | 企業・解説向け英語ナレーション | 有料 | [Review](https://faceless.directory/directory/wellsaid) |
| [Speechify](https://speechify.com/) | 自然な読み上げ、速度調整、吹き替え | Freemium | [Review](https://faceless.directory/directory/speechify) |
| [OpenAI TTS](https://developers.openai.com/api/docs/guides/text-to-speech) | 自動化パイプライン向けの安定した API 音声 | 従量課金 | — |

### オープンソース・ローカル無料 TTS（月額 ¥0）

| プロジェクト | 概要 | ライセンス |
|---|---|---|
| [VOICEVOX](https://voicevox.hiroshiba.jp/) | 日本の顔出しなし解説動画（ずんだもん等）の定番無料ローカル音声合成 | 無料 / OSS（各キャラ規約あり） |
| [Kokoro-82M](https://github.com/hexgrad/kokoro) | 82M パラメータの超軽量 TTS。CPU でも高速、日本語を含む 8 言語以上に対応 | Apache-2.0 |
| [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) | 日本語を含む 10 言語対応のストリーミング TTS、3 秒音声クローン可 | Apache-2.0 |
| [CosyVoice](https://github.com/QwenAudio/CosyVoice) | 感情制御・多言語（日本語含む）対応の音声生成モデル（★24k+） | Apache-2.0 |
| [IndexTTS](https://github.com/index-tts/index-tts) | 制御性の高い産業向けゼロショット TTS（★25k+） | Open source |

> **終了サービス削除メモ：** **Play.ht** は 2025 年 12 月末に完全終了、**LOVO AI** は 2026 年 5 月に Chapter 7 破産申請済みのためリストから除外しました。

---

## 🎬 AI 動画生成

| ツール | 概要 | 料金 | レビュー |
|---|---|---|---|
| [Kling AI](https://klingai.com/) | Kling 3/4 世代の滑らかな動きとマルチショット生成。ショート用 B-roll の定番 | Freemium | — |
| [Dreamina (Seedance)](https://dreamina.capcut.com/) | ByteDance の Seedance 2.0/2.5。画像→動画とキャラクター一貫性に極めて強い | Freemium | — |
| [Google Veo](https://deepmind.google/models/veo/) | ネイティブ音声付きシネマティック動画生成（Veo 3.1） | 有料 / Gemini プラン | — |
| [Alibaba Wan](https://wan.video/) | Wan 3.0 クラウド＋オープンウェイト。1080p の高コスパ動画生成 | Freemium / OSS | — |
| [MiniMax Hailuo](https://hailuoai.video/) | Hailuo / H3 系列。ネイティブ音声付きで高速・低コスト | Freemium | — |
| [Runway](https://runway.com/) | Gen-4 / Gen-4.5 の高品質生成と細かなカメラ制御 | $12/月〜 | [Review](https://faceless.directory/directory/runway) |
| [Luma Dream Machine](https://lumalabs.ai/) | シネマティック映像とキーフレーム補間 | Freemium | — |
| [Higgsfield AI](https://higgsfield.ai/) | キャラ一貫性を保った顔出しなしアニメ・解説動画スタジオ | $15/月〜 | — |
| [Vidu](https://www.vidu.com/) | リファレンス画像からのキャラ維持に強い（アニメ・漫画動画向け） | Freemium | — |
| [PixVerse](https://pixverse.ai/) | SNS 向けショート映像とエフェクト生成 | Freemium | — |
| [Magic Hour](https://magichour.ai/) | 動画生成、動画変換、リップシンク等をまとめて提供 | Freemium | — |
| [Pika](https://pika.art/) | クリエイティブな短尺クリップ・エフェクト | Freemium | [Review](https://faceless.directory/directory/pika) |
| [InVideo AI](https://invideo.io/) | 台本・アイデアからストック素材＋AI 映像で一括動画化 | Freemium / 有料 | [Review](https://faceless.directory/directory/invideo) |
| [Pictory](https://pictory.ai/) | ブログ記事や台本を自動で動画化 | 有料 / 試用 | [Review](https://faceless.directory/directory/pictory) |
| [Fliki](https://fliki.ai/) | テキストから多言語音声付き動画を生成 | Freemium | [Review](https://faceless.directory/directory/fliki) |
| [HeyGen](https://heygen.com/) | AI アバター＋175 言語以上の高精度動画翻訳・リップシンク | Freemium / 有料 | [Review](https://faceless.directory/directory/heygen) |
| [Synthesia](https://synthesia.io/) | 解説・研修向けプレゼンターアバター | 有料 / 無料枠 | [Review](https://faceless.directory/directory/synthesia) |
| [D-ID](https://d-id.com/) | 静止画から喋るアバターを生成 | Freemium | [Review](https://faceless.directory/directory/d-id) |
| [Lumen5](https://lumen5.com/) | 記事ベースの説明動画作成 | Freemium | [Review](https://faceless.directory/directory/lumen5) |

> **注記：** OpenAI の **Sora**（アプリおよび Sora 2 API）は 2026 年 3 月に終了しています。

---

## ✂️ 動画編集・自動字幕・切り抜き

| ツール | 概要 | 料金 | レビュー |
|---|---|---|---|
| [CapCut](https://capcut.com/) | 自動字幕・テンプレートが豊富な定番編集ソフト | Freemium | [Review](https://faceless.directory/directory/capcut) |
| [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) | 無料から使えるプロ仕様の動画編集・合成ソフト | 無料 / Studio 有料 | [Review](https://faceless.directory/directory/davinci) |
| [Descript](https://descript.com/) | 文字起こしテキストを編集して動画をカット | Freemium / 有料 | [Review](https://faceless.directory/directory/descript) |
| [Adobe Premiere Pro](https://www.adobe.com/products/premiere.html) | 業界標準のタイムライン編集ソフト | 有料 | [Review](https://faceless.directory/directory/premiere) |
| [Final Cut Pro](https://www.apple.com/final-cut-pro/) | Mac 向け高速プロ編集ソフト | 買い切り | [Review](https://faceless.directory/directory/finalcut) |
| [VEED](https://veed.io/) | ブラウザ完結の動画編集・AI 字幕 | Freemium | [Review](https://faceless.directory/directory/veed) |
| [Kapwing](https://kapwing.com/) | 共同編集対応オンライン動画エディタ | Freemium | [Review](https://faceless.directory/directory/kapwing) |
| [Opus Clip](https://opus.pro/) | 長尺動画からバズりやすいショートを自動抽出 | Freemium / $15/月〜 | [Review](https://faceless.directory/directory/opus-clip) |
| [Clips Kitty](https://github.com/ColinGPT9/clips-studio) | **ローカル無料のオープンソース Opus Clip 代替**（Ollama + Whisper） | 無料 (AGPL-3.0) | — |
| [Submagic](https://www.submagic.co/) | ショート動画向け強調字幕・B-roll 自動挿入 | 有料 | — |
| [Vizard](https://vizard.ai/) | 長尺→SNS 短尺の AI 自動切り抜き | Freemium | — |
| [Munch](https://www.munchstudio.com/) | トレンド分析連携の AI 切り抜き | 有料 | — |
| [Karaoke Captions](https://karaokecaptions.com/) | 端末ローカル処理・透かしなしの単語単位ハイライト字幕 | Freemium | — |

---

## 🖼️ サムネイル・画像生成

| ツール | 概要 | 料金 | レビュー |
|---|---|---|---|
| [Midjourney](https://midjourney.com/) | 世界観の強いサムネイル・イラスト生成 | $10/月〜 | [Review](https://faceless.directory/directory/midjourney) |
| [ChatGPT (GPT Image)](https://chatgpt.com/) | 写実画像と正確な文字入れ（旧 DALL·E 3 後継） | Freemium | [Review](https://faceless.directory/directory/dalle) |
| [FLUX (Black Forest Labs)](https://bfl.ai/) | 高精細なオープンウェイト＆API 画像モデル | 変動 / OSS | — |
| [Ideogram](https://ideogram.ai/) | 画像内テキストの描画精度が高い | Freemium | [Review](https://faceless.directory/directory/ideogram) |
| [Recraft](https://www.recraft.ai/) | チャンネル統一スタイルを保てるベクター・イラスト生成 | Freemium | — |
| [Canva](https://canva.com/) | サムネイル文字入れ・テンプレート管理 | Freemium | [Review](https://faceless.directory/directory/canva) |
| [Leonardo.ai](https://leonardo.ai/) | スタイル制御しやすい素材生成 | Freemium | [Review](https://faceless.directory/directory/leonardo) |
| [Adobe Firefly](https://firefly.adobe.com/) | 商用利用に配慮した生成塗りつぶし | Freemium | [Review](https://faceless.directory/directory/firefly) |
| [Photoshop](https://www.adobe.com/products/photoshop.html) | 切り抜き・色調整の最終仕上げ | 有料 | [Review](https://faceless.directory/directory/photoshop) |
| [Feed Thumbnail](https://feedthumbnail.com/youtube-thumbnail-size) | 実際の YouTube フィード上でのサムネ見え方を無料プレビュー | 無料 | — |

---

## 🎵 BGM・効果音

| ツール | 概要 | 料金 |
|---|---|---|
| [Suno](https://suno.com/) | AI 音楽生成（商用収益化には有料プランが必要） | Freemium |
| [Udio](https://www.udio.com/) | 高品質な AI 楽曲・BGM 生成 | Freemium |
| [Epidemic Sound](https://www.epidemicsound.com/) | YouTube Content ID クリア済み BGM・効果音 | サブスク |
| [Artlist](https://artlist.io/) | 音楽・SFX・動画素材の商用ライセンス | サブスク |
| [Pixabay Music](https://pixabay.com/music/) | 無料 BGM（使用前に Content ID 記載を要確認） | 無料 |

---

## ⚡ 投稿自動化・ワークフロー

| ツール | 概要 | 料金 | レビュー |
|---|---|---|---|
| [n8n](https://n8n.io/) | セルフホスト可能な OSS 自動化（大量運用で最安） | 無料 OSS / Cloud | [Review](https://faceless.directory/directory/n8n) |
| [Make](https://make.com/) | ビジュアル自動化、多ステップ処理のコスパ良好 | Freemium / $9/月〜 | [Review](https://faceless.directory/directory/make) |
| [Zapier](https://zapier.com/) | 対応アプリ数最多のノーコード連携 | Freemium / $20/月〜 | [Review](https://faceless.directory/directory/zapier) |
| [Repurpose.io](https://repurpose.io/) | YouTube / TikTok / IG 間の自動クロスポスト | 有料 | [Review](https://faceless.directory/directory/repurpose) |
| [Metricool](https://metricool.com/) | マルチプラットフォーム予約投稿＋分析 | Freemium | — |
| [Buffer](https://buffer.com/) | 個人クリエイター向けのシンプルな予約投稿 | Freemium | [Review](https://faceless.directory/directory/buffer) |
| [Hootsuite](https://hootsuite.com/) | チーム向け SNS 運用管理 | 有料 | [Review](https://faceless.directory/directory/hootsuite) |

---

## 📊 分析・YouTube SEO

| ツール | 概要 | 料金 | レビュー |
|---|---|---|---|
| [YouTube Studio](https://studio.youtube.com/) | 公式アナリティクス、維持率、サムネ A/B テスト | 無料 | — |
| [TubeBuddy](https://tubebuddy.com/) | YouTube SEO・キーワード・A/B テスト | Freemium | [Review](https://faceless.directory/directory/tubebuddy) |
| [VidIQ](https://vidiq.com/) | 急上昇（Outlier）動画の検知と競合リサーチ | Freemium | [Review](https://faceless.directory/directory/vidiq) |
| [Social Blade](https://socialblade.com/) | 公開チャンネルの登録者・再生推移チェック | 無料 | [Review](https://faceless.directory/directory/socialblade) |
| [Google Trends](https://trends.google.com/trends/) | 地域別検索・YouTube トレンド需要確認 | 無料 | — |

---

## 📁 進行管理・台本管理

| ツール | 概要 | 料金 | レビュー |
|---|---|---|---|
| [Notion](https://www.notion.com/) | 投稿カレンダー、台本テンプレート、運用マニュアル | Freemium | [Review](https://faceless.directory/directory/notion) |
| [Airtable](https://airtable.com/) | n8n / Make と相性抜群の制作データベース | Freemium | [Review](https://faceless.directory/directory/airtable) |
| [ClickUp](https://clickup.com/) | 複数チャンネル・外注編集者管理 | Freemium | [Review](https://faceless.directory/directory/clickup) |
| [Trello](https://trello.com/) | シンプルなカンバン管理 | Freemium | [Review](https://faceless.directory/directory/trello) |

---

## 🛠️ オープンソース自動化パイプライン & Agent Skills

| プロジェクト | 概要 | 特徴 |
|---|---|---|
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | テーマ入力から台本・音声・映像・字幕付き HD ショートを一括生成 | ★145k+、活発 |
| [FujiwaraChoki/MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2) | Python 製の自動ショート動画生成パイプライン | ★32k+ |
| [linyqh/NarratoAI](https://github.com/linyqh/NarratoAI) | AI 映画・動画解説の自動台本＆自動編集ツール | ★11k+ |
| [kaomei/stickman-video-director](https://github.com/kaomei/stickman-video-director) | 台本から棒人間アニメ動画を生成する AI Agent Skill（Claude Code / Codex） | ★7.5k+、活発 |
| [cporter202/automate-faceless-content](https://github.com/cporter202/automate-faceless-content) | 長尺＆ショート顔出しなし動画の自動化設計集 | ★3.3k+、活発 |
| [xuanyustudio/LocalMiniDrama](https://github.com/xuanyustudio/LocalMiniDrama) | ローカル完結の AI ショートドラマ・漫画動画スタジオ（Seedance 2 対応） | ★2.5k+、活発 |
| [gyoridavid/short-video-maker](https://github.com/gyoridavid/short-video-maker) | MCP 駆動ショート動画生成（Kokoro + Whisper + Remotion） | ★1.5k+ |
| [ColinGPT9/clips-studio](https://github.com/ColinGPT9/clips-studio) | **Clips Kitty**：無料オープンソースのローカル Opus Clip 代替 | ★620+、活発 |
| [Orkas-AI/Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) | コーディングエージェントがタイムライン編集から MP4 出力まで実行 | ★350+、MIT、活発 |
| [Dark2C/Viral-Faceless-Shorts-Generator](https://github.com/Dark2C/Viral-Faceless-Shorts-Generator) | トレンド取得 → 台本 → TTS → FFmpeg 出力（Docker 対応） | ★120+ |
| [aruntemme/n8n-faceless-youtube](https://github.com/aruntemme/n8n-faceless-youtube) | 顔出しなし YouTube 向け n8n テンプレート集 | n8n |

**プロンプト＆スキル集：**
- [ZeroLu/awesome-seedance](https://github.com/ZeroLu/awesome-seedance) — Seedance 2.0/2.5 プロンプト・ワークフロー集
- [UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) — AI ショートドラマ・ストーリー動画向け台本＆絵コンテスキル集

---

## 📚 ガイド・運用プレイブック（英語）

[faceless.directory](https://faceless.directory) 掲載の詳細ガイド：

- **入門：** [How to Start a Faceless YouTube Channel](https://faceless.directory/blog/how-to-start-faceless-youtube-channel) · [20 Faceless Channel Ideas](https://faceless.directory/blog/faceless-youtube-channel-ideas-2025) · [FREE AI Stack](https://faceless.directory/blog/zero-budget-faceless-youtube-guide)
- **ツール比較：** [AI Voice Comparison](https://faceless.directory/blog/elevenlabs-vs-murf-vs-play) · [AI Video Models](https://faceless.directory/blog/pika-vs-runway-vs-sora) · [CapCut Workflow](https://faceless.directory/blog/capcut-faceless-video-editing)
- **収益化・SEO：** [Automation Guide](https://faceless.directory/blog/faceless-youtube-automation-guide) · [Shorts SEO](https://faceless.directory/blog/youtube-shorts-seo-uncovered) · [7 Revenue Streams](https://faceless.directory/blog/faceless-youtube-monetization) · [YouTube AI Rules](https://faceless.directory/blog/youtube-ai-monetization-traps)

---

## 🎯 ジャンル別アイデア & CPM 目安

*(英語圏 Tier-1 AdSense の目安。日本市場・視聴者層により実際の RPM は変動します。)*

| ジャンル | 目安 CPM (Tier-1) | 難易度 | 主力ツール |
|---|---|---|---|
| **金融・投資・経済解説** | $15–40 | 高 | Claude, ElevenLabs, CapCut / 図解 |
| **テック・AI 解説** | $8–20 | 中 | 画面録画 + Claude + ElevenLabs / Kokoro |
| **未解決事件・ドキュメンタリー** | $6–15 | 中 | 綿密なリサーチ + ナレーション + Kling/Runway |
| **教育・雑学・棒人間解説** | $6–15 | 中 | オリジナル台本 + `stickman-video-director` |
| **睡眠・瞑想・環境音** | $5–15 | 低 | 環境音 + 映像（単調ループのみは YPP 注意） |
| **ホラー・怪談・ミステリー朗読** | $4–10 | 低 | オリジナル脚本 + ElevenLabs/Fish + 暗め B-roll |
| **ゲーム考察・ストーリー解説** | $3–8 | 中 | プレイ映像 + 独自考察ナレーション |
| **海外反応・ショート朗読系** | $2–8 | 低 | YPP 審査が厳しいため独自コメント・編集が必須 |

---

## 🔗 コミュニティ

- [r/NewTubers](https://reddit.com/r/NewTubers) · [r/PartneredYoutube](https://reddit.com/r/PartneredYoutube) · [r/youtubers](https://reddit.com/r/youtubers) · [r/FacelessYouTube](https://www.reddit.com/r/FacelessYouTube/) · [Indie Hackers](https://indiehackers.com/)

---

## 🤝 コントリビュート

PR やツール提案を歓迎します。詳細は [CONTRIBUTING.md](CONTRIBUTING.md) をご覧ください。Git 不要で提案できる [Tool Submission Issue](https://github.com/sasharun/awesome-faceless/issues/new?template=submit-tool.yml) も用意しています（UTM なし公式 URL のみ受付）。

役に立ったらぜひ **Star** をお願いします！

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

パブリックドメイン (CC0 1.0)。

---

**運営：[Faceless Directory](https://faceless.directory)**

[![Star History Chart](https://api.star-history.com/svg?repos=sasharun/awesome-faceless&type=Date)](https://star-history.com/#sasharun/awesome-faceless&Date)
