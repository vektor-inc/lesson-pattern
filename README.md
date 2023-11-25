# サクサク進む! <br>WordPressページ制作ワークショップ

## https://github.com/vektor-inc/lesson-pattern

ブロックパターンを使ってウェブページを作る事に慣れるためのレッスン素材です。

## 完成イメージ

以下の２つのページを作ってみます

* 歯科医院 トップページ  
https://pattern-lesson.instawp.xyz/
* 歯科医院 クリニック紹介  
https://pattern-lesson.instawp.xyz/clinic-introduction/

## 素材について

このリポジトリの images ディレクトリに入ってますので、必要に応じてリポジトリをダンロードしたりcloneしてください。

## 環境構築

まずは [local](https://training.vektor-inc.co.jp/courses/how-to-run-wordpress-site/lessons/development-environment/) や [wp-env](https://ja.wordpress.org/team/handbook/block-editor/getting-started/devenv/get-started-with-wp-env/) や [instaWP](https://instawp.com/) などで新しいWordPressの環境を用意してください。

### 初期設定と各種インストール

* 設定 > 一般
  - 日本語に変更
  - 日付フォーマットの変更
* 外観 > テーマ > 新しいテーマを追加 > Lightning をインストール  
    - ブロックテーマに慣れている場合は Lightning でなくても X-T9 でもかまいません。
* ダッシュボードの案内に従って プラグイン VK All in One Expansion Unit / VK Blocks / VK Block Patterns をインストール  
（ダッシュボードに新たにお知らせなどが表示されるが非表示にしたり無視してかまいません）

### 余分な要素の削除
* 外観 > カスタマイズ > Lightning トップページスライドショー設定 > スライドを非表示に設定
* 外観 > カスタマイズ > ウィジェット > フッター上部 に入ってるものを削除  
* カスタマイズ画面を一旦保存（初期コンテンツが入る）

---

## クリニック紹介ページの作成

トップページは少し複雑なので、ブロックエディタを初めてさわる人にもわかりやすいようにクリニック紹介ページからやってみましょう。

### 完成イメージ

https://pattern-lesson.instawp.xyz/clinic-introduction/

#### Lightning の場合

Lightning の場合は初期インストールすると「会社概要」という固定ページが自動的に作成されるので、そのページをクリニック紹介として編集していきます。

編集画面右側 Lightning デザイン設定 > レイアウト設定 で「１カラム」を選択

### リード部分

まずは以下の見出しと文章を入力

```
見出し : 私達は「痛くない」にこだわる歯医者さんです

私たちは歯の治療に対する一般的な「痛い」「怖い」というイメージを払拭するため、患者さんの痛みを最小限にする治療を最も心がけています。

最新の技術と患者さんへの細やかな配慮を組み合わせて、安心して治療を受けていただけるように、それぞれの患者さんの状態に合わせて治療計画を立て、治療前の詳しい説明と丁寧なフォローアップで、安心感を提供します。

私たちは、患者さんがリラックスして治療を受けられる環境づくりに注力し、健康な笑顔のために日々、質の高いケアを提供しています。

```

* 見出しを中央揃えにしてみる
* 見出しに色をつけてみる
* 余力があれば見出しの改行位置を画面サイズ毎で調整


### 施設紹介

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
* ボタンはいらないので削除します。
* 画像の高さを変更しましょう。
* コピーしたパターンは２段しかないので、１段目を複製して下に移動して、それを変更していきます。

### 施設紹介２

お手本ページは以下のパターンを使用しています。
https://patterns.vektor-inc.co.jp/vk-patterns/text-with-2-images/

テキストや画像を差し替えてみましょう。

これでクリニック紹介ページは完成です。

---

## トップページの制作

ここから難しくなりますががんばっていきましょう。

### 編集前の準備

* トップページに指定した固定ページの編集画面を開く
  - 本文欄の中身をすべて削除
  - 編集画面右側の Lightning デザイン設定 > 余白設定 > サイトコンテントの上下余白を無しにする にチェック

### 完成イメージ

https://pattern-lesson.instawp.xyz/

### ■ ヒーローエリア

まずヒーローエリアに表示するパターンを選びましょう。

[無料 & ヒーローエリア](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-industry=&pattern-category=heroarea&demo-site=&post_date_range_after=&post_date_range_before=&s=&vkfs_orderby=&vkfs_form_id=b0df8947-cedf-4943-91fb-f1a069bfdeb0) で絞り込むといろいろ出てきます。



お手本では以下のパターンを使用しています。  
https://patterns.vektor-inc.co.jp/vk-patterns/hero_textbox_slider-1/

* コピペすると、元々がスライダーなので複数枚分あります。今回は一つで良いので、余分な「スライダーアイテム」ブロックを削除してください。
* 掲載文字↓

```
健康な一日は健康な一歯から
信頼と実績あなたの街の歯科診療

健康な一日は健康な一歯から、信頼と実績のある当院で。
最新の技術と温かな対応で、あなたと家族の笑顔を守ります。
地域に根差し、皆さまの口腔健康を第一に考えたケアをお届け。
お気軽にご相談ください。
```

#### ■ お知らせ

* [無料 & 投稿リスト で検索](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-industry=&pattern-category=post-list-section&demo-site=&post_date_range_after=&post_date_range_before=&s=&vkfs_orderby=&vkfs_form_id=b0df8947-cedf-4943-91fb-f1a069bfdeb0)

お手本サイトでは以下を使用  
https://patterns.vektor-inc.co.jp/vk-patterns/post-list-content-for-top/

#### ■ 診療時間

* [無料 & 業種:医療](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-industry=medical&demo-site=&post_date_range_after=&post_date_range_before=&s=&vkfs_orderby=&vkfs_form_id=b0df8947-cedf-4943-91fb-f1a069bfdeb0) で検索

お手本サイトでは以下を使用  
https://patterns.vektor-inc.co.jp/vk-patterns/dental-clinic_reception_time/


* カラムブロックを配置して「お知らせ」と「診療時間」を左右に配置

#### ■ 診療案内

[無料 & セクション](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-type=section&pattern-industry=&demo-site=&post_date_range_after=&post_date_range_before=&s=&vkfs_orderby=date.desc&vkfs_form_id=b0df8947-cedf-4943-91fb-f1a069bfdeb0) で検索

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

※ 以下オマケ

歯周病治療  
歯周病治療では、専門的なクリーニングと日常ケアを指導します。

インプラント  
インプラントは、失った歯を人工の根で置き換える治療で、自然な見た目と機能を回復させます。

予防歯科  
虫歯にならないための予防・歯磨きなどの指導を丁寧にします。

#### ■ 採用情報

[無料 & セクション](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=free&pattern-type=section&pattern-industry=&demo-site=&post_date_range_after=&post_date_range_before=&s=&vkfs_orderby=date.desc&vkfs_form_id=b0df8947-cedf-4943-91fb-f1a069bfdeb0) で検索

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

#### ■ 地図

[地図](https://patterns.vektor-inc.co.jp/?post_type=vk-patterns&supported-themes=&license-classification=&pattern-industry=&pattern-category=map&demo-site=&post_date_range_after=&post_date_range_before=&s=&vkfs_orderby=&vkfs_form_id=b0df8947-cedf-4943-91fb-f1a069bfdeb0)で検索

お手本では以下を使用  
https://patterns.vektor-inc.co.jp/vk-patterns/iframe-fullwidth/

お好みに応じて地図を差し替え

#### ■ ご予約・お問い合わせはお気軽にどうぞ

* とりあえず見出しとサブテキストを入力  
既に作成済みの見出しとテキストや余白を複製して打ち替えればOK
* ヒーローエリア下の診療時間の部分を再利用ブロック化して複製して配置
* [電話番号と遅い合わせ](https://patterns.vektor-inc.co.jp/vk-patterns/business-tel-and-button-vertical/) のパターンを配置
* 以下の文字を打ち替え

受付 8:30-12:00 / 14:30-19:30  
（水・日・祝日・土の午後は休診）

ネット予約  
24時間受付

* 地図から下の部分をグループ化して上部に2pxの線を指定

---

■ instaWPをご利用の場合

一定時間で消えてしまうのでデータをエクスポートしてください。

プラグイン All in One WP Migration をインストール > 有効化 してエクスポート  
https://ja.wordpress.org/plugins/all-in-one-wp-migration/

↓ 参考  
https://training.vektor-inc.co.jp/courses/how-to-run-wordpress-site/lessons/all-in-one-wp-migration/

---

## おまけ

Lightning の場合

* 外観 > カスタマイズ > Lightning デザイン設定 からロゴ画像を指定します。
* 外観 > カスタマイズ > ウィジェット > フッターウィジェットエリアを全部削除

＿人人人人＿  
＞　完 成　＜  
￣Y^Y^Y^Y￣