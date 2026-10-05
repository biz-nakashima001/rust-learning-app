# Rustの小さな教室

Rustの文法をゼロから試せる日本語のブラウザ学習アプリです。追加のパッケージは不要です。

## 起動

ターミナルでプロジェクトフォルダに移動して、ローカルサーバーを起動します。

```sh
cd /Users/shinya_nakashima/codex-practice/rust-learning-app
python3 -m http.server 8000
```

ブラウザで <http://localhost:8000> を開いてください。終了するときはターミナルで `Ctrl+C` を押します。

## コードの実行

「実行して確認」を押すと、入力したRustコードをRust公式Playground（<https://play.rust-lang.org>）に送信してコンパイル・実行します。実行にはインターネット接続が必要です。レッスンの進捗と入力中のコードは、このブラウザのローカルストレージに保存されます。
