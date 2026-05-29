# 📖 Proverbs from The Bible for Children
### こども礼拝プログラム ／ 箴言第1章 学習教材

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-blue?logo=github)](https://awaitokono.github.io/Proverbs_from_The_Bible_for_Children/)
[![HTML](https://img.shields.io/badge/Language-HTML-orange?logo=html5)](.)
[![対象](https://img.shields.io/badge/対象-子ども礼拝-green)](.)

---

## 🌟 概要

聖書の箴言第1章をこどもたちが楽しく学べるインタラクティブHTMLコンテンツです。  
キリストコミュニティガーデン アバハウスのこども礼拝プログラム向けに作成されました。

**ライブページ → [awaitokono.github.io/Proverbs_from_The_Bible_for_Children/](https://awaitokono.github.io/Proverbs_from_The_Bible_for_Children/)**

---

## 📚 コンテンツ構成

| ファイル | 内容 | 聖書箇所 |
|---|---|---|
| `index.html` | **第一部**「知恵を学ぶために」 | 箴言 1:1〜6 |
| `proverbs1-part2.html` | **第二部**「主を恐れることは知識の初め」 | 箴言 1:7〜9 |
| `proverbs1-part3.html` | **第三部**「悪いさそいに気をつけよう」 | 箴言 1:10〜19 |
| `wisdom-card-game.html` | **ボーナスゲーム**「知識 vs 知恵 カードゲーム」 | — |

---

## 🖼️ 画像ファイル一覧

### 第一部（`index.html`）用

| ファイル名 | 内容 |
|---|---|
| `img_01_title_new.png` | タイトル画像 |
| `img_02_story.png` | おはなしセクション |
| `img_03_solomon.png` | ソロモン王さまのイラスト |
| `img_04_proverbs.png` | 箴言の目的 |
| `img_05_wisdom.png` | 知識と知恵の違い |
| `img_06_howto.png` | 知恵の身につけ方 |

### 第二部（`proverbs1-part2.html`）用

| ファイル名 | 内容 |
|---|---|
| `p2_img_01_title.png` | タイトル画像 |
| `p2_img_02_intro.png` | イントロ |
| `p2_img_03_fear.png` | 主を恐れること |
| `p2_img_04_omniscient.png` | 全知の神 |
| `p2_img_05_corridor.png` | 廊下のイラスト |
| `p2_img_06_foolish.png` | 愚かさについて |
| `p2_img_07_points.png` | 今日のポイント |
| `p2_img_08_think.png` | 考えてみよう |
| `p2_img_09_prayer.png` | お祈り |

### 第三部（`proverbs1-part3.html`）用

| ファイル名 | 内容 |
|---|---|
| `p3_img_01_title.png` | タイトル画像 |
| `p3_img_02_temptation.png` | 誘惑について |
| `p3_img_03_everyone.png` | みんなやってる |
| `p3_img_04_greed.png` | 貪欲について |
| `p3_img_05_profit.png` | 利益の誘惑 |
| `p3_img_06_trap.png` | わなのたとえ |
| `p3_img_07_choose.png` | 選ぶ力 |
| `p3_img_08_god.png` | 神さまの道 |

---

## 🗂️ 推奨フォルダ構成（整理案）

現在はすべてのファイルがルートに並んでいます。  
将来的にコンテンツが増える場合は以下の構成への移行を推奨します：

```
Proverbs_from_The_Bible_for_Children/
│
├── index.html                    # エントリーポイント（第一部）
├── README.md
│
├── chapter1/                     # 箴言第1章
│   ├── part1.html                # ← 現: index.html
│   ├── part2.html                # ← 現: proverbs1-part2.html
│   └── part3.html                # ← 現: proverbs1-part3.html
│
├── games/                        # ゲームコンテンツ
│   └── wisdom-card-game.html
│
└── assets/                       # 画像・メディア
    ├── chapter1-part1/
    │   ├── img_01_title_new.png
    │   ├── img_02_story.png
    │   ├── img_03_solomon.png
    │   ├── img_04_proverbs.png
    │   ├── img_05_wisdom.png
    │   └── img_06_howto.png
    ├── chapter1-part2/
    │   ├── p2_img_01_title.png
    │   └── ... (p2_img_02〜09)
    └── chapter1-part3/
        ├── p3_img_01_title.png
        └── ... (p3_img_02〜08)
```

> ⚠️ **注意**: フォルダ移動の際は、各HTMLファイル内の画像パス（`src="img_..."` 等）を新しいパスに合わせて更新する必要があります。

---

## ✨ 特徴・技術仕様

- **ふりがな対応** — `<ruby>` タグで全漢字にふりがなを付与
- **モバイル対応** — レスポンシブデザイン、iOS Safari最適化済み
- **インタラクティブ** — カードめくりゲーム、アニメーション付き
- **アクセシビリティ** — WAI-ARIA属性、フォーカス管理に配慮
- **外部依存なし** — CDNフォント（Google Fonts）のみ、フレームワーク不使用

---

## 📝 利用・制作情報

- **制作**: キリストコミュニティガーデン アバハウス / 合同会社 #AWAI
- **対象**: こども礼拝（小学生）
- **言語**: 日本語

---

*箴言 1:7 — 「主を恐れることは知識の初め。愚かな者は知恵と訓戒を蔑む。」*
