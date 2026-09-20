# 札幌すごいAIハッカソン 2026夏 — ランディングページ

AI駆動開発ハッカソン（札幌すごいAIハッカソン 2026夏）の公式ランディングページです。

## 概要

「2時間で、世界を作れ。」をキャッチコピーに、思考 → 実装 → 発表を圧縮する実験場を提供するハッカソンイベントのLPです。

## ファイル構成

```
/
├── index.html        # メインLP（全セクション）
├── guideline.html    # ルール・ガイドライン詳細
├── conditions.html   # 参加規約
├── style.css         # スタイルシート
├── script.js         # JavaScript（アニメーション、インタラクション）
├── requirements.md   # プロジェクト要件定義
└── README.md         # このファイル
```

## ページ構成（index.html）

1. **HERO** — キャッチコピー・開催概要・CTA
2. **INTRODUCTION** — イベントの思想・設計思想
3. **WHAT YOU WILL DO** — 体験の流れ（4ステップ）
4. **RULES** — ルール（自由度の高さ）
5. **THEME** — お題（当日発表）
6. **TIMELINE** — 時間設計（14:00〜18:00）
7. **OUTPUT & PRESENTATION** — 成果物と発表形式
8. **JUDGING** — 審査基準（ベース評価＋技術加点）
9. **AWARDS** — 表彰（最優秀賞・審査員特別賞）
10. **JUDGES** — 審査員紹介
11. **ENTRY** — エントリーCTA
12. **ORGANIZER** — 主催者紹介
13. **FOOTER**

## ローカルで表示

```bash
open index.html
```

またはローカルサーバーを起動：

```bash
python3 -m http.server 8000
```

その後、ブラウザで `http://localhost:8000` を開く。

## ＜仮＞ 要確認項目

以下の情報が未確定のため、`＜仮：...＞` とマークして実装済みです。確定後に差し替えてください。

| 項目 | 場所 |
|------|------|
| 開催日 | index.html hero-date, hero-info-badge, footer |
| 会場名・住所 | index.html hero-info-badge, footer |
| 参加費 | index.html（現状記載なし、必要であれば追加） |
| エントリーフォームURL | index.html `#entry` セクション CTAボタンhref |
| チーム人数制限 | guideline.html 参加ルール |
| 審査員の名前・肩書き・写真・コメント | index.html `#judges` セクション（3枠プレースホルダー） |
| 最優秀賞の賞品 | index.html `#awards` セクション |
| 審査員特別賞の賞品 | index.html `#awards` セクション |

## カラーパレット

```css
--film-purple: #9D4EDD;
--film-cyan:   #00D4FF;
--film-gold:   #FFD700;
--dark-bg:     #08080f;
```

## デプロイ先

`hack-2026-summer.sugoiai.org`（CNAME設定済み）

---

**© 2026 札幌すごいAI会 All rights reserved.**
