# digital-quiz

選択式クイズができるシンプルなシングルページWebアプリケーションです。バニラJavaScriptで構築されており、日本語のユーザーインターフェースを備えています。

## デモ
https://code4fukui.github.io/digital-quiz/

## 機能
- リモートのCSVファイルからクイズの問題と解答を取得します。
- 選択式（多肢選択式）で問題を1問ずつ出題します。
- 回答後、即座に正誤のフィードバックを表示します。
- 全問終了時に最終的な正答率を計算して表示します。
- すっきりとしたニューモーフィズム（neumorphic）デザインを採用しています。

## 使い方
インストールやビルドは不要です。モダンWebブラウザで `index.html` を開くだけでクイズを開始できます。

## データソース
クイズのデータは、[digital-quiz-data](https://github.com/code4fukui/digital-quiz-data/) リポジトリ内の `ap-2021spring.csv` ファイルから取得しています。

## 依存関係
このプロジェクトは、以下の外部モジュールとスタイルシートを使用してブラウザ上で直接動作します。

- **JavaScriptモジュール:**
  - [CSV.js](https://js.sabae.cc/CSV.js): CSVデータのパース用。
  - [waitClick.js](https://js.sabae.cc/waitClick.js): 非同期クリックイベントの処理用。
  - [input-radio.js](https://code4fukui.github.io/input-radio/input-radio.js): ラジオボタン入力用のカスタムWebコンポーネント。
- **スタイル:**
  - [neomo.css](https://code4fukui.github.io/neomo.css/neomo.css): ニューモーフィズムデザイン用の軽量CSSフレームワーク。

## ライセンス
MIT License — 詳細は [LICENSE](LICENSE) をご覧ください。
