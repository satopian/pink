# POTI-board用テンプレートPINK

[お絵かき掲示板](https://pbbs.sakura.ne.jp/)交流サイトで使っているテンプレートを一般配布用にカスタマイズしたものです。

[POTI-board改二](https://github.com/sakots/poti-kaini)用は[こちら](https://github.com/satopian/pink_for_poti-kaini)。
改と改二のテンプレートの互換性はありません。

### 設置サンプル

[POTI-board用テンプレート PINK 設置サンプル](https://pbbs.sakura.ne.jp/cgi/neosample/poti/)

### 特徴

[POTI-board用テンプレート PINK を配布します。: STP^3](http://stp.sblo.jp/article/182310034.html)

BBSNoteのようなレイアウト。

スマートフォン・タブレットに対応したレスポンシブデザイン。

新規投稿、レス送信モードからの画像アップロードができないようにしてあります。
画像アップロード掲示板ではなくお絵かき掲示板として使うためです。
管理人投稿からの画像アップロードには対応しています。

## このテンプレートを使うために必要なもの

お絵かき掲示板のスクリプト本体、[POTI-board改](https://github.com/sakots/poti-kai)をダウンロードします。
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
JavaアプレットをChromeの拡張機能[CheerpJ](https://chrome.google.com/webstore/detail/cheerpj-applet-runner/bbmolahhldcbngedljfadjlognfaaein)で起動する事を想定していますが、サーバによっては期待した動作にならないかもしれません。

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

## IE は管理画面の記事削除に非対応

管理者パスワードがurlアドレスに入る仕様はセキュリティ上好ましくないため書き換えました。

結果的に、IEでは管理画面で記事を削除する事ができなくなりました。
Windows10のEdge42.17134.1.0で試してみたところ問題なく動作しましたので、動作しないのはIEだけだと思います。

管理者が管理画面で記事を削除する時にIE以外のブラウザを使えばすむことなのでセキュリティリスクの排除を優先しました。

[formの入れ子を回避する: STP^3](http://stp.sblo.jp/article/185279768.html)

## アニメファイルアップロードペイントに対応
PaintBBS NEOのpchファイルとしぃペインターのspchを管理画面からアップロードして投稿する事ができます。

**pink_shi_painter_can_use**の、NEOとしぃペインター標準版が使えるテンプレートにのみ機能を追加しました。
NEOのみのテンプレートにはこの機能はありません。

[POTI-board改](https://poti-k.info/) v1.52.6 以降で追加された新しい機能です。
古いバージョンのPOTI-boardでは機能しませんのでご注意ください。

## 履歴
#### [2020/04/13] PINK lot.200413

- PaintBBS NEO ver1.5.5 に対応しました。
- ツールパレットの左右切り替えができるようになりました。

詳細は[こちら](https://github.com/satopian/pink/issues/1)

![Screen-2020-04-13_18-24-20](https://user-images.githubusercontent.com/44894014/79111471-8f024800-7db7-11ea-8c66-32d045c188db.png)


#### [2019/09/24] PINK lot.190924

- [POTI-board改](https://poti-k.info/) v1.53.5 lot.190921 で追加された新しい機能に対応。
- スマートフォンやタブレットで大きなキャンバスを開いた時にピンチインで縮小表示できるようになりました。
#### [2019/08/16] PINK lot.190816

- 本文のフォントサイズを15pxから16pxに変更しました。

#### [2019/08/02] PINK lot.190802

- config.phpでお絵かき機能を使用しない設定にしたときに表示が崩れていたのを修正しました。
- アニメファイルアップロードペイントに対応。（しぃペインターも使えるテンプレートのみ）

#### [2019/05/30] PINK lot.190530

- キャンバスサイズを選択するプルダウンメニューの数値にconfig.phpで設定した値が入るようになりました。

config.phpの以下の設定が反映されるようになりました。

//お絵描きデフォルトサイズ(最初に選択される数値)

PDEF_W //幅

PDEF_H // 高さ

//お絵描き最大サイズ

PMAX_W //幅

PMAX_H //高さ

#### [2019/05/28] PINK lot.190528

- ペイント画面のテーブルタグを撤去してCSSに置き換えました。

#### [2019/05/16] PINK lot.190516

- Matrix機能を使ったパレットセット時の挙動を改善するため動的パレットスクリプトを修正しました。
- 動的パレットスクリプトのOSブラウザ判定を整理。

#### [2019/05/12] PINK lot.190512

- 本文のフォントサイズを14pxから15pxに変更しました。
- ファイルサイズが小さくなるようにCSSを書き直しました。
- タグを整理しました。
- 動的パレットで使用されていたfontタグをCSSに置き換えました。

#### [2019/02/25] PINK lot.190225

- カタログモードをPCの時はよりギャラリー的に、スマートフォンの時はより作品を探しやすくなるようにしました。
- ファイルサイズが小さくなるようにCSSを書き直しました。
- 横幅の指定方法を見直しました。

#### [2018/12/27] PINK lot.181228

- しぃペインター標準版も使えるテンプレートを配布開始。
- 管理画面のセキュリティ対策。
