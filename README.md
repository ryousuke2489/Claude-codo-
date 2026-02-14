# GenAI Video Model Market Analysis — Consulting Slide Deck

McKinsey/BCG スタイルのコンサルティング資料として、GenAI動画生成モデル市場の包括的分析を行ったプロジェクトです。

## プロジェクト構成

```
├── prompts/
│   ├── analysis-prompt.md        # 分析プロンプト（原文記録）
│   └── system-prompt.md          # スライド生成用システムプロンプト（再利用可能）
├── data/
│   ├── market-data.md            # 市場規模・成長データ
│   ├── model-specs.md            # モデル技術仕様
│   ├── benchmarks.md             # ベンチマークスコア・Eloレーティング
│   └── pricing.md                # 価格比較データ
└── slides/
    └── genai-video-market-deck.html  # 12枚のスライドデッキ（HTML+CSS）
```

## スライドデッキの使い方

1. `slides/genai-video-market-deck.html` をChromeまたはEdgeで開く
2. スクロールで全12スライドを閲覧可能
3. PDF出力: `Ctrl+P` → 「PDFとして保存」→ レイアウト: 横向き

## スライド内容（全12枚）

| # | 内容 | データ可視化 |
|---|------|------------|
| 1 | カバー | — |
| 2 | エグゼクティブサマリー | 4つの主要発見 |
| 3 | 市場規模 | 棒グラフ + KPIカード |
| 4 | コスト構造 | ウォーターフォールチャート |
| 5 | 競争環境 | 8モデル比較表 |
| 6 | アーキテクチャ比較 | ハーベイボール機能マトリクス |
| 7 | 品質ベンチマーク（スコア） | グループ化棒グラフ |
| 8 | 品質ベンチマーク（Elo） | SVG横棒グラフ |
| 9 | 価格・バリュー分析 | 価格比較 + 品質/価格比 |
| 10 | 戦略ポジショニング | 2x2マトリクス |
| 11 | 主要示唆 | 3列インサイト |
| 12 | 付録 | 詳細データテーブル |

## 対象モデル

Seedance 2.0, Kling 3.0, Sora 2, Veo 3.1, Runway Gen-4.5, Luma Ray3, Pika 2.5, Wan2.2

## システムプロンプトの再利用

`prompts/system-prompt.md` には、コンサルティングスタイルのスライドを生成するための再利用可能なシステムプロンプトが含まれています。任意のLLMにこのプロンプトを使用して、異なるトピックのスライドデッキを生成できます。

## データソース

- Grand View Research, Verified Market Research, MarketsandMarkets（市場データ）
- Lanta AI Quantitative Benchmarks（構造化ベンチマーク）
- VBench Community Rankings（Eloレーティング）
- 各社公式ドキュメント（技術仕様）
- 2026年2月時点のデータ
