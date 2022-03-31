# compornent（共通部品）

## イメージ画像
<img width="405" alt="image" src="https://user-images.githubusercontent.com/99580997/161017641-0279cd82-f960-494b-b189-ac433d6e9d3d.png">
<img width="778" alt="image" src="https://user-images.githubusercontent.com/99580997/161017715-7699c7b5-b2ee-4d19-902a-82ef4c3c668e.png">
<img width="1019" alt="image" src="https://user-images.githubusercontent.com/99580997/161017796-f26f6667-9367-4054-9046-6f2bb10afa99.png">


## 概要

- カード（画像（擬似要素）、タイトル、説明）
- https://www.notion.so/000_web-component-index-c4b399010bf342e9b4e2ed516cf9c730
-
- 画像とコンテンツをセパレートしたパターン（これにするとコンテンツの文字が画像の邪魔をしない。）
- `<div class="card">`
- `<div class="card__inner">`
- `<div class="card__photo"></div>`
- `<div class="card__contents"></div>`
- `</div>`
- `</div>`

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- xxx

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> card をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="758" alt="image" src="https://user-images.githubusercontent.com/99580997/161018204-9ac04076-c720-4134-a708-7204ce98a615.png">


## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
- <img width="888" alt="image" src="https://user-images.githubusercontent.com/99580997/161018273-20289713-4b73-4ba6-b285-d5d9202bf040.png">


## portfolio url:

- https://c-0042.wtb.cfbx.jp/

## 参考にしたサイト

- xxx

## 更新履歴

- 2022/3/31 初版 作成完了(カード（画像（擬似要素）、タイトル、説明）)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
