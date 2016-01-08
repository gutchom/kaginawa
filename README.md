# Kaginawa -忍具鉤縄-
忍者は画像を見つけて落とす。
TwitterWebに存在する画像群は、右クリックからの保存が効かず、我々は手をこまねいていた。
鉤縄はそれら画像群から必要な物を効率的に選択し、一括保存を実現する。
スマートフォンなど、保存に制限のあるデバイスからのアクセスに対して、フォルダ分け・タグ付けによって画像の選択状況の保持を提供する。

## 開発環境
### 構築手順
Node.js v4.2.3 を使用。
- `$ npm install` -> パッケージインストール
- `$ npm run dev` -> 実行

### ファイル構成
- `imagesCollection/src/*` -> フロントエンドソース
- `imagesCollection/server.js` -> モックサーバ 

### 使用言語など
- ECMAScript6
- Jade
- Sass + CSSnext

### ライブラリなど
- React.js -> クライアントサイド
- Express -> 開発用API提供
- Passport -> OAuth認証

### ビルドツールなど
- Gulp
- Webpack
