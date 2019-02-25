# POTI-board用テンプレートPINK

[お絵かき掲示板](https://pbbs.sakura.ne.jp/)交流サイトで使っているテンプレートを一般配布用にカスタマイズしたものです。

### 設置サンプル

[POTI-board用テンプレート PINK 設置サンプル](https://pbbs.sakura.ne.jp/cgi/neosample/poti/)

### 特徴

[POTI-board用テンプレート PINK を配布します。: STP^3](http://stp.sblo.jp/article/182310034.html)

BBSNoteのようなレイアウト。

スマートフォン・タブレットに対応したレスポンシブデザイン。

画像アップロード掲示板ではなくお絵かき掲示板として使うため、新規投稿、レス送信モードから画像アップロードできないようにしてあります。
管理人投稿からの画像アップロードには対応しています。

## このテンプレートを使うために必要なもの

お絵かき掲示板のスクリプト本体、[POTI-board改](https://sakots.red/poti/)をダウンロードします。
[PaintBBS NEO](https://github.com/funige/neo)をダウンロードします。
必要なファイルは、neo/dist/の**neo.css**と、**neo.js**の2つです。

## このテンプレートのダウンロード 

**緑色の「Clone or download」ボタンを押下してpink-master.zipを入手します。**

zipファイルに2つのフォルダが入っています。

### pink_neo_only

HTML5版しぃPaintBBS NEO のためのテンプレートです。
NEO以外使えません。

### pink_shi_painter_can_use

しぃペインターも使いたい人のためのテンプレートです。

NEOを使うのチェックを外すと、しぃペインター標準版が起動します。
JavaアプレットをChromeの拡張機能[CheerpJ](https://chrome.google.com/webstore/detail/cheerpj-applet-runner/bbmolahhldcbngedljfadjlognfaaein)で起動する事を想定していますが、サーバによっては期待している動作にならないかもしれません。

Javaで起動したほうが安定していますが、Javaに対応しているブラウザは2018年現在IE11とWaterfoxだけです。

## サーバへの転送

**pink_neo_only**

**pink_shi_painter_can_use**

の**フォルダの中身**を、potiboard.phpと同じディレクトリに転送します。
**フォルダごと転送しても動きません**のでご注意ください。

色の設定は外部cssで行っています。
Chromeのデベロッパーツールでpink.cssを編集すれば配色を変更する事ができます。

[readme_pink.txt](https://github.com/satopian/pink/blob/master/pink_neo_only/readme_pink.txt)にも、その他の必要事項を記載しました。

基本的に、これだけの情報で自力で設置、カスタマイズができる方のためのテンプレートです。
問題なく動作する事を期待して作成していますが、なんらかの不具合があっても無保証です。

## IE Edgeは管理画面の記事削除に非対応

管理者パスワードがurlアドレスに入る仕様はセキュリティ上好ましくないため書き換えました。

結果的に、IEとEdgeでは管理画面で記事を削除する事ができなくなりました。

管理者が管理画面で記事を削除する時に、Chrome・Firefoxを使えばすむことなので、セキュリティリスクの排除を優先しました。

[formの入れ子を回避する: STP^3](http://stp.sblo.jp/article/185279768.html)

## 履歴
#### [2019/02/25] PINK lot.190225

- PC、iPad Proのカタログ表示を大きくし、ギャラリーとして機能するようにしました。枠線を撤去。
- スマートフォンの時はカタログが1カラムから2カラムに。閲覧時の縦方向のスクロールの量を減らしました。
- ファイルサイズが小さくなるようにCSSを書き直しました。
- 横幅の指定方法を見直しました。

#### [2018/12/27] PINK lot.181228

- しぃペインター標準版も使えるテンプレートを配布開始。
- 管理画面のセキュリティ対策。
