# POTI-board用テンプレートPINK

[お絵かき掲示板](https://pbbs.sakura.ne.jp/)交流サイトで使っているテンプレートを一般配布用にカスタマイズしたものです。

### 設置サンプル

[POTI-board用テンプレート PINK 設置サンプル](https://pbbs.sakura.ne.jp/cgi/neosample/poti/)

### 特徴

[POTI-board用テンプレート PINK を配布します。: STP^3](http://stp.sblo.jp/article/182310034.html)

## このテンプレートを使うために必要なもの

お絵かき掲示板のスクリプト本体、[POTI-board改](https://sakots.red/poti/)をダウンロードします。
[PaintBBS NEO](https://github.com/funige/neo)をダウンロードします。
必要なファイルは、neo/dist/の**neo.css**と、**neo.js**の2つです。

## 緑色の「Clone or download」ボタンを押下してpink-master.zipを入手します。

### pink_neo_only

HTML5版しぃPaintBBS NEO のためのテンプレートです。
NEO以外使えません。

### pink_shi_painter_can_use

しぃペインターも使いたい人のためのテンプレートです。

NEOを使うのチェックを外すと、しぃペインター標準版が起動します。
JavaアプレットをChromeの拡張機能[CheerpJ](https://chrome.google.com/webstore/detail/cheerpj-applet-runner/bbmolahhldcbngedljfadjlognfaaein)で起動する事を想定していますが、サーバによっては期待通りの動作をしない事があるようです。

Javaで起動したほうが安定していますが、対応ブラウザは2018年現在IE11だけです。

## サーバへの転送

**pink_neo_only**

**pink_shi_painter_can_use**

の**フォルダの中身**を、potiboard.phpと同じディレクトリに転送します。
**フォルダごと転送しても動きません**のでご注意ください。

readme_pink.txtにも、その他の必要事項を記載しました。
基本的に、これだけの情報で自力で設置、カスタマイズができる方のためのテンプレートです。

問題なく動作する事を期待して作成していますが、なんらかの不具合があったとしても無保証です。

## IE Edgeは管理画面の記事削除に非対応

管理者パスワードがurlアドレスに入る仕様はセキュリティ上好ましくないため、書き換えました。

結果的に、IEとEdgeでは管理画面からの記事の削除ができなくなりました。
管理者がChrome、Firefoxを使えば解決するため、セキュリティリスクの排除を優先しました。

## 履歴
#### PINK lot.181228

しぃペインター標準版も使えるテンプレートを配布開始。
管理画面のセキュリティ対策。