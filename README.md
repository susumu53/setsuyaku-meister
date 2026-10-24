# 節約マイスター 公式Webアプリケーション
（Setsuyaku Meister Official Web Application - 2026 Edition）

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20App-blue?logo=github)](https://susumu53.github.io/setsuyaku-meister/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-2026%20Edition-gold.svg)]()

物価高・利上げ・補助金終了に対応する、家計防衛と構造的コスト最適化の民間資格「**節約マイスター**」の公式Webアプリケーションです。

👉 **[Webアプリを開く（診断・計画・試験）](https://susumu53.github.io/setsuyaku-meister/)**

---

## 🌟 アプリケーションの3大中核機能

### 1. 🧮 家計防衛「6大判断式」リアルタイム診断シミュレーター
数字を入れるだけで、客観的判定と最適化アドバイスを瞬時に提示します。
- **判断式① エンゲル係数 判定機**: 食費と総支出から係数（%）を算出し、健全・平均・警告（30%以上）を診断。
- **判断式② 損益分岐月数 計算機**: 初期費用と毎月削減額から「何ヶ月で元が取れるか」を判定。
- **判断式③ 高額療養費・医療保険要否 診断**: 年間上限（約53万円）と手元現預金を照合し、民間医療保険の解約・減額を判定。
- **判断式④ 省エネ設備 投資回収シミュレーター**: 節水シャワーや断熱窓などの回収月数と10年間の純利益を計算。
- **判断式⑤ 医療費控除 vs セルフメディ 比較判定**: 確定申告でどちらの控除制度を選ぶべきかを自動判定。
- **判断式⑥ 1g/1mlあたり底値比較カリキュレーター**: 「PBだから安い」「大容量だから得」の思い込みを排し、真の底値を比較。

### 2. 📋 90日家計構造改革 ＆ 年間創出キャッシュフロー確定シート
- 通信費、火災保険、光熱費、食費、決済還元などの見直し額を入力すると、**年間創出キャッシュ（年間総削減額）** をリアルタイム集計。
- 浮いた資金の使い道（再配分ゴール：新NISA積立、家族旅行等）を宣言。
- ブラウザ保存（LocalStorage）に対応。

### 3. 🎓 公式修了認定試験 ＆ 修了証書即時発行システム
- **全30問の包括的試験**: 基礎知識問題（10問）、計算判断問題（10問）、実践事例問題（10問）。
- **リアルタイム合否判定**: 80%（24問以上）で合格。
- **公式修了証書（Certificate）即時発行**: お名前・認定番号（STM-2026-XXXX）・公印入りの本格証書を生成。
- **A4横向き印刷・PDF保存に完全対応**（ブラウザの「印刷」からそのままPDF保存可能）。
- 合格結果のX（旧Twitter）ワンクリック共有機能。

---

## 🚀 公開とデプロイ（GitHub Pages）

本リポジトリは GitHub Pages に完全対応しており、サーバーレス・ノービルドで世界中から即時アクセス可能です。

- **リポジトリURL**: `https://github.com/susumu53/setsuyaku-meister`
- **公開WebアプリURL**: `https://susumu53.github.io/setsuyaku-meister/`

### ローカルでの動作確認
```bash
# Pythonの簡易サーバーを起動
python -m http.server 8080
# ブラウザで http://localhost:8080 を開く
```

---

## 📜 ライセンス

MIT License
