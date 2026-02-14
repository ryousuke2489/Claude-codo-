# スライド生成プロンプト — テンプレートと記録

このファイルは2つの役割を持っています：
1. **テンプレート**: 新しいスライド資料を生成する際にコピーして使えるプロンプトの雛形
2. **記録**: 過去に生成したスライド資料のプロンプト履歴

---

## テンプレート（コピーして使ってください）

以下のフォーマットに沿って入力すれば、`system-prompt.md` と組み合わせてコンサルティング品質のスライドが生成されます。

```
テーマ: [分析したいテーマを記入]

データ:
- [数値データ、比較データ、市場情報などを箇条書きで記入]
- [記事やレポートのURLを貼り付けてもOK]
- [テキストをそのまま貼り付けてもOK]

要件:
- スライド枚数: [希望枚数、未指定なら10〜12枚]
- 言語: [日本語 / English / 等]
- テンプレート: [A: 市場分析 / B: 技術トレンド / C: 事業提案 / D: 簡易レポート / 未指定なら自動選択]
- その他: [特別な要件があれば記入]
```

---

## 記録: 過去の生成履歴

### #1 — GenAI動画生成モデル市場の包括的分析（2026-02-14）

**テーマ:**
Conduct a comprehensive analysis of the GenAI video model market, focusing on leading players (e.g., Seedance 2.0, Kling, Veo, Luma). Compare their core architectures, temporal consistency, and prompt adherence to identify current industry benchmarks. Use the latest information

**デザイン要件:**
A professional, high-density consulting presentation slide, designed in the style of a top-tier strategy firm (McKinsey/BCG) blended with high-end editorial aesthetics.

Core Content & Layout:
1. Rich Data Visualization: The slide is populated with complex, precise charts (stacked bar charts, waterfall charts, or line graphs) and detailed data tables with rows and columns.
2. Structured Frameworks: Includes strategic diagrams or 2x2 matrices constructed with thin, clean lines.
3. High Information Density: The layout is sophisticated and multi-column, mimicking an actual business analysis deck, not just an empty cover page.

Visual Style:
1. Aesthetic: Tech-minimalist but information-heavy. Clean, sharp, and authoritative.
2. Typography: Serif fonts (like Times New Roman) for the main headlines to give a premium financial report feel; clean Sans-serif for chart labels and data numbers.
3. Color Palette: Clean white background. Text is sharp black. Charts and graphical accents use Deep Royal Blue and distinct shades of grey for data hierarchy.
4. Graphics: Use fine hairline borders for tables and precise vector lines for graphs.

**使用テンプレート:** A（市場・競争分析）
**生成枚数:** 12枚
**出力ファイル:** `slides/genai-video-market-deck.html`

---

*最終更新: 2026-02-14*
