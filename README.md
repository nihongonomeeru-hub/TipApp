# Tip Time — チップ計算アプリ

**Jetpack Compose** を用いて開発された、リアルタイムでチップ金額を計算するモダンな Android アプリケーションです。

公式カリキュラム「Android Basics with Compose」の一環として作成し、宣言型UIにおける状態管理（State Management）および設計パターンの実践を目的としています。

---

## 主な機能

* **リアルタイム計算:** 金額の入力に合わせて即座にチップ額を算出・表示します。
* **状態ホイスティング（State Hoisting）:** UIコンポーネントとロジック（状態）を適切に分離し、再利用性とテスト容易性を高めた設計を採用しています。
* **リソース管理:** 表示文字列やフォーマット引数はすべて `strings.xml` で安全に管理し、ローカライズに対応しています。
* **モダンなレイアウト対応:** エッジ・トゥ・エッジ（Edge-to-Edge）表示に対応し、`safeDrawingPadding` やスクロール制御による快適なUIを実現しています。

---

## 使用技術・アーキテクチャ

* **開発言語:** Kotlin
* **UIフレームワーク:** Jetpack Compose (Material 3)
* **設計パターン:** 単一方向データフロー（UDF） / 状態ホイスティング（State Hoisting）
* **主要コンポーネント・API:**
  * `mutableStateOf` / `remember`
  * `TextField`
  * `stringResource`（フォーマット文字列処理）

---

## セットアップ手順

1. リポジトリをクローンします:
   ```bash
   git clone [https://github.com/](https://github.com/)nihongonomeeru-hub/TipApp.git
