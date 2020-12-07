# pj-002-vue
pj-001-html(https://github.com/yuri-nakano/pj-001-html) で作成した画面をVueを使って作成しました。
rawフォルダーには手動作成したフォルダ、pj-002-cliにはVueCLIで作成したフォルダーが入っています。
 
# DEMO

## pj-002-cli作成画面キャプキャ
![image](https://user-images.githubusercontent.com/64944011/99899511-4287cf00-2ced-11eb-91b7-6971c517090b.png)
continueボタンの押下時
![image](https://user-images.githubusercontent.com/64944011/99899513-4582bf80-2ced-11eb-8ca2-1d6f3cbaa329.png)
iphone Xサイズ

![image](https://user-images.githubusercontent.com/64944011/101308932-63742680-388e-11eb-9567-096c6dccb674.png)

## rawフォルダー作成画面キャプキャ
![image](https://user-images.githubusercontent.com/64944011/101308782-00828f80-388e-11eb-8f02-4a9a32619b88.png)
continueボタンの押下時
![image](https://user-images.githubusercontent.com/64944011/101308785-037d8000-388e-11eb-8cb4-e55354f858ed.png)

# Features

pj-002-cliはpug/scssでコードを書いております。
ロゴ、ハンバーガーメニュー、コンティニューボタンをVuetifyを利用して実装しました。

## 機能
continueボタンの押下時確認のモーダルが開きます。
両方の画面レスポンシブ対応しております。

 
# Requirement
 
* Node.js v12.18.0 
* vue/cli 4.4.1 
* Ruby Sass 3.7.4

 
# Installation
 
## Node.js
https://qiita.com/sansaisoba/items/242a8ba95bf70ba179d3 
リンク先の手順で進めていく

## VueCLI
1. `vue create pj-002-cli` とし、`Manually select features`でマニュアル設定を以下のように行う。Babel、Router、CSS Pre-processors、Linter / Formatterを選択

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d202b51e-b02b-48a1-bf8c-bf11872f2a8f/vue_create.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d202b51e-b02b-48a1-bf8c-bf11872f2a8f/vue_create.png)

    ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4bd410a7-6519-4082-bd94-4c387ce722e1/cli2.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4bd410a7-6519-4082-bd94-4c387ce722e1/cli2.png)

    設定詳細はこの画像のように設定してください。最後の`save this as a preset for future projects?`はNoで大丈夫です。

## Vuetify

```bash
cd pj-002-cli
vue add vuetify
```

## Sass

```bash
npm install sass-loader node-sass
```

# Usage
 
DEMOの実行方法など、"hoge"の基本的な使い方を説明する
 
```bash
git clone https://github.com/yuri-nakano/pj-002-vue.git
cd pj-002-cli
npm i
npm run serve
```
 
# Note
 
注意点などがあれば書く
 
# Author
 
* 作成者 中野由梨
* E-mail　nakanoyuri.03@gmail.com
 
