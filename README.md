# ゼロから覚えたくない人のための<br>ブロックエディタ入門

## https://github.com/vektor-inc/lesson-pattern

ブロックパターンを使ってウェブページを作る事に慣れるためのレッスン素材です。

[ → [オンラインハンズオンの場合の留意事項](https://github.com/vektor-inc/lesson-pattern/blob/main/notice-online.md) ]

## 完成イメージ

以下の２つのページを作ってみます

* 歯科医院 トップページ  
https://pattern-lesson.instawp.xyz/
* 歯科医院 クリニック紹介  
https://pattern-lesson.instawp.xyz/clinic-introduction/

## 素材について

このリポジトリ（[https://github.com/vektor-inc/lesson-pattern](https://github.com/vektor-inc/lesson-pattern)）の images ディレクトリに入ってますのでダンロードしてください。ダウンロードしたzipファイルを解凍した中の images フォルダにあります。

![zipファイルダウンロード](https://raw.githubusercontent.com/vektor-inc/lesson-pattern/main/text-images/download-zip.png "zipファイルダウンロード")

## 環境構築

テーマなどインストール済みの環境を使います

### A. 自分のサーバーに用意する

1. 新規WordPress環境を準備
2. プラグイン [VK FullSite Installer](https://vk-fullsite-installer.com/) をインストール・有効化
3. X-T9 無料版 プレーン をインポート

### B. 練習用環境を使う（24時間で消失します）

一時的な練習だけであれば以下のURLから各種セットアップ済みの環境を起動する事ができます。

* [練習環境（テーマ : X-T9版）を起動する](https://app.instawp.io/launch?t=-x-t9&d=v2) 
* [練習環境（テーマ : Lightning版）を起動する](https://app.instawp.io/launch?t=pattarn-lesson-starter&d=v2) 

※ この環境は24時間で消失します。練習後のデータがほしい場合はご自身でエクスポートしてください。  

---

## クリニック紹介ページ 1

トップページは構成が少し複雑なので、ブロックエディタを初めてさわる人にもわかりやすいようにクリニック紹介ページからやってみましょう。

### 完成イメージ

https://pattern-lesson.instawp.xyz/clinic-introduction/

### 会社案内 のタイトルの変更

* ページタイトルを「会社案内」から「クリニック紹介」に変更

### リードタイトル

* リードタイトルをコピー＆ペースト
* 見出し2 に変更

* 中央揃えにしてください
* 文字の一部に色がついていた部分は、作業中のサイトには存在しない色なので、黄色い背景になります。該当部分を選択して、ツールバーの ? アイコンをクリックすれば背景色がリセットされます。
* 黄色だった部分に色をつけます。該当部分を選択して、ツールバーの下向きアイコンを展開して「ハイライト」文字色を指定します
* 改行位置を画面サイズ毎で調整

### リードテキスト

* 文章をコピペしてください。

---

## クリニック紹介ページ 2 施設紹介

ここからは手作りすると面倒なのでパターンを使います。

VK Pattern Library ( https://patterns.vektor-inc.co.jp/ ) に行くといろいろあります。とりあえず

* ライセンス区分 : 無料
* パターンタイプ : セクション

で検索して画像とテキストを表示するのに適したパターンを選びましょう。

お手本では  
https://patterns.vektor-inc.co.jp/vk-patterns/media-and-txt_gradient_free/  
を使用していますが、  
https://patterns.vektor-inc.co.jp/vk-patterns/vk-cols-fit__vk-cols-grid__vk-cols-grid-alignfull/  
などお好みのを使用してもかまいません.

「このパターンをコピーする」ボタンをクリックしてコピーして、自分のウェブサイトの作成中のページに貼り付けます。

* 画像を差し替えてみましょう。画像のところにそのまま画像をドラッグすれば可能です。
* 文字を変更して、色など調整しましょう。
* ボタンはいらないので、ボタンとその上のスペーサーを削除します。
* 画像の高さを変更してみましょう。該当のカバーブロックのスタイルタブに移動すると「カバー画像の最小の高さ」があるので、そこから変更できます。350pxくらいにしてみましょう。
* コピーしたパターンは２段しかないので、１段目を複製して下に移動して、それを変更していきます。

### 施設紹介２

お手本ページは以下のパターンを使用しています。  
https://patterns.vektor-inc.co.jp/vk-patterns/text-with-2-images/

お手本ページを参考にテキストや画像を差し替えてみましょう。

これでクリニック紹介ページは完成です。

---

## トップページの制作 1

ここから難しくなりますががんばっていきましょう。  
まずはトップページに指定してある固定ページの編集画面を開きます。

### 完成イメージ

https://pattern-lesson.instawp.xyz/

### ■ ヒーローエリア

まずヒーローエリアに表示するパターンを選びましょう。

[無料 & ヒーローエリア](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-industry=&pattern-category=heroarea&demo-site=&post_date_date_after=&post_date_date_before=&s=&vkfs_orderby=&vkfs_form_id=11755) で絞り込むといろいろ出てきます。



お手本では以下のパターンを使用しています。  
https://patterns.vektor-inc.co.jp/vk-patterns/hero_textbox_slider-1/

* コピペすると、元々がスライダーなので複数枚分あります。今回は一つで良いので、余分な「スライダーアイテム」ブロックを削除してください。
* スライダーアイテムブロックを削除できたら、残りのスライダーアイテムブロック内の文字を変更します。  
掲載文字↓

---

健康な一日は健康な一歯から  
信頼と実績あなたの街の歯科診療  

健康な一日は健康な一歯から、信頼と実績のある当院で。  
最新の技術と温かな対応で、あなたと家族の笑顔を守ります。  
地域に根差し、皆さまの口腔健康を第一に考えたケアをお届け。  
お気軽にご相談ください。

---


* スライダーの下に レスポンシブスペーサー ブロックを配置して余白サイズを L に

---

## トップページ 2 お知らせと診療時間

#### ■ お知らせ

* [無料 & 投稿リスト で検索](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-industry=&pattern-category=post-list-section&demo-site=&post_date_date_after=&post_date_date_before=&s=&vkfs_orderby=&vkfs_form_id=11755)

お手本サイトでは以下を使用  
https://patterns.vektor-inc.co.jp/vk-patterns/post-list-content-for-top/

#### ■ 診療時間

* [無料 & 業種:医療](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-industry=medical&demo-site=&post_date_date_after=&post_date_date_before=&s=&vkfs_orderby=&vkfs_form_id=11755) で検索

お手本サイトでは以下を使用  
https://patterns.vektor-inc.co.jp/vk-patterns/dental-clinic_reception_time/


* カラムブロックを配置して 50 - 50 にする
* 「お知らせ」と「診療時間」を左右に配置
* カラムブロックの スタイル > サイズ から ブロックの間隔を指定

---

## トップページ 3 診療案内

[無料 & セクション & カラムレイアウト](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-type=section&pattern-industry=&pattern-category=column&demo-site=&post_date_date_after=&post_date_date_before=&s=&vkfs_orderby=&vkfs_form_id=11755) で検索

お手本では以下を使用  
https://patterns.vektor-inc.co.jp/vk-patterns/icon-and-card-pr-section-free/

* とりあえず背景画像を変更
* 以下科目を入力

一般歯科  
軽度の虫歯はできるだけ削らない治療を心がけております。

小児歯科  
お子様の歯に関わる相談、歯の生え方のチェックを行なっております。

矯正歯科  
矯正歯科では、歯並びと咬み合わせを改善するための治療を提供します。

* アイコンを入れ替え
アイコンをクリックすると右の設定サイドバーから変更できる。
[Font Awesome アイコンリスト](https://fontawesome.com/search?o=r&m=free) のサイトで dental や tooth で検索



※ 以下オマケ

歯周病治療  
歯周病治療では、専門的なクリーニングと日常ケアを指導します。

インプラント  
インプラントは、失った歯を人工の根で置き換える治療で、自然な見た目と機能を回復させます。

予防歯科  
虫歯にならないための予防・歯磨きなどの指導を丁寧にします。

---

## トップページ 4 採用情報

[無料 & セクション & カラムレイアウト](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-type=section&pattern-industry=&pattern-category=column&demo-site=&post_date_date_after=&post_date_date_before=&s=&vkfs_orderby=&vkfs_form_id=11755) で検索

お手本では以下を使用  
https://patterns.vektor-inc.co.jp/vk-patterns/10686/

患者様の笑顔をつくるお手伝いをしませんか？

ベクトルデンタルクリニックでは、患者さんに寄り添った治療を提供することを大切にしています。
あなたが持っている経験やスキルをフルに活用し、患者さんと一緒に成長していける環境です。
また、研修制度も充実しており、スキルアップにも力を入れています。

募集職種

* 歯科医師
* 歯科衛生士
* 歯科助手
* 事務・医療事務

---

## トップページ 4 地図の配置

[地図](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-industry=&pattern-category=map&demo-site=&post_date_date_after=&post_date_date_before=&s=&vkfs_orderby=&vkfs_form_id=11755)で検索

お手本では以下を使用  
https://patterns.vektor-inc.co.jp/vk-patterns/iframe-fullwidth/

* Google Map を開いて、表示したい箇所を表示
* 埋め込み用の iframe のコードをコピーして、HTMLブロックの中身を差し替え

---

## トップページ 5 ご予約・お問い合わせはお気軽にどうぞ

* とりあえず見出しとサブテキストを入力しましょう。  
既に作成済みの見出しとテキストや余白を複製して打ち替えてもOKです。
* ヒーローエリア下の診療時間の部分を選択し、ツールバーから パターンを作成 > 同期 の手順で同期パターンを作成します。名前は「診療時間表」にしておきます。
* ページ最下部に戻って、新規挿入で、先程作成した 診療時間表 の同期パターンを配置します。
* [電話番号とお問い合わせ](https://patterns.vektor-inc.co.jp/vk-patterns/business-tel-and-button-vertical/) のパターンを配置
* 以下の文字を打ち替え

受付 8:30-12:00 / 14:30-19:30  
（水・日・祝日・土の午後は休診）

* （）の手間で shif + Enter で改行します。
* 文字のサイズを必要に応じて調整します。  
２行目を選択してツールバーの下向きアイコンから「インライン文字サイズ」が選べるので、そこから文字を更に小さくします。
* 右側の設定サイドバーのスタイルタブの「タイポフラフィ」の右の３点アイコンから「行の高さ」を選択して、行間を狭くします。
* ボタン部分も以下に書き換え

ネット予約  
24時間受付

※ 24時間受付 の部分は右側の設定サイドバーから入力してください。

* カラムブロックを 50 / 50 で配置して、診療時間表と電話番号を入れます
* カラムブロックの間隔を設定

##### グループ化と区切り線

* 地図から下の部分をグループ化
* 全幅
* グループブロックの上部に2pxの線を指定

---

■ instaWPをご利用の場合

一定時間で消えてしまうのでデータをエクスポートしてください。
※ エクスポート前にユーザー名・パスワードを確認ください。

プラグイン All in One WP Migration など、サイト引っ越し用のプラグインをインストールして、  
管理画面の All in One WP Migration > エクスポート からエクスポートしてください。
https://ja.wordpress.org/plugins/all-in-one-wp-migration/

↓ 自分の環境にインポートする場合は下記参照ください。  
https://training.vektor-inc.co.jp/courses/how-to-run-wordpress-site/lessons/all-in-one-wp-migration/


