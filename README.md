LP-5

シンプルな静的サイトです。

概要

HTML / CSS / JavaScript のみで構成された静的サイトです。Bootstrap をベースにレイアウトを組み、jQuery と Lightbox で画像表示などのインタラクションを実装しています。

技術スタック
HTML / CSS / JavaScript
Bootstrap
jQuery
Lightbox.js
ディレクトリ構成
.
├── index.html          # メインページ
├── bootstrap.min.css   # Bootstrap スタイルシート
├── bootstrap.min.js    # Bootstrap スクリプト
├── jquery-3.3.1.slim.min.js
├── popper.min.js
├── lightbox.css / lightbox.js  # 画像のライトボックス表示
└── 画像ファイル各種
開発

特別なビルド環境は不要です。index.html をブラウザで開けば表示を確認できます。

Grunt を使ったタスクランナー設定 (Gruntfile.js) も含まれています。

bash
npm install
grunt
デプロイ

デプロイ手順は DEPLOY.md を参照してください。GitHub Pages でホスティングしています。

ライセンス

MIT License
