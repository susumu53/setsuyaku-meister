# 節約マイスター 認定試験 ＆ 公式修了証書発行システム
（Setsuyaku Meister Certification System - 2026 Edition）

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20App-blue?logo=github)](https://susumu53.github.io/setsuyaku-meister/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-2026%20Edition-gold.svg)]()

物価高・利上げ・補助金終了に対応する、家計防衛と構造的コスト最適化の民間資格「**節約マイスター**」の公式修了認定試験および修了証書発行Webアプリケーションです。

👉 **[認定試験を受験する（Webアプリを開く）](https://susumu53.github.io/setsuyaku-meister/)**

---

## 🌟 アプリケーションの特徴

- **完全自律稼働・ノーサーバー**: HTML/CSS/JavaScriptのみで構成され、外部データベース不要で即座に動作します。
- **全30問の包括的試験**:
  - 基礎知識問題（10問）
  - 計算・判断式問題（10問）
  - ケーススタディ・実践事例問題（10問）
- **リアルタイム自動採点 ＆ カテゴリ別正答率分析**: 試験終了と同時に判定を行い、分野ごとの理解度と解説を表示。
- **公式修了証書（Certificate）の即時発行**:
  - 80%以上（24問以上正解）で合格。
  - 受講生のお名前・一意の認定番号（STM-2026-XXXX）・認定日・公印（デジタル印章）が入った本格的な証書を生成。
  - **A4横向き印刷・PDF保存に完全対応**（ブラウザの「印刷」機能でそのままPDF出力可能）。
  - 合格通知のX（旧Twitter）ワンクリックシェア機能。

---

## 📐 家計防衛「6つの判断式」（出題範囲）

1. **判断式① エンゲル係数**: 食費 ÷ 消費支出の合計 × 100
2. **判断式② 損益分岐月数**: 初期費用の総額 ÷ 毎月の削減額
3. **判断式③ 自己負担上限と手元資金**: 手元現預金 ≧ 高額療養費年間上限（約53万円）＋ 対象外費用
4. **判断式④ 回収期間**: 本体購入価格 ÷（年間節約額 ÷ 12）
5. **判断式⑤ 控除額の比較**: 医療費控除額 vs セルフメディケーション税制控除額
6. **判断式⑥ 1gあたりの単価**: 商品価格 ÷ 内容量（gまたはml）

---

## 🚀 公開とデプロイ（GitHub Pages）

本リポジトリは GitHub Pages に完全対応しています。

1. **リポジトリURL**: `https://github.com/susumu53/setsuyaku-meister`
2. **公開WebアプリURL**: `https://susumu53.github.io/setsuyaku-meister/`

### ローカルでの動作確認
特別なビルドコマンドは不要です。ブラウザで `index.html` を直接開くか、ローカルサーバーを起動してください。

```bash
# Pythonを使用する場合
python -m http.server 8080
# ブラウザで http://localhost:8080 を開く
```

---

## 📜 ライセンス

MIT License
