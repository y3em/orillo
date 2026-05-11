---
title: "DeltaChatをはじめませんか"
date: 2025-07-06
image: "/wp-content/uploads/2025/07/Screenshot-2025-07-06-at-13.52.43.png"
---

## DeltaChat？
[オープンソース](https://github.com/deltachat)のチャット／メール・アプリです。特定の団体が営利目的で提供するサービスではなく、だれもが公共的なリソースとして自由に使えるものです。iOSやAndroid、MacOS、Windowsなどに対応しており、公式サイトから無料で[ダウンロード](https://delta.chat/download)できます。
以下の二点において、GmailやLINE、Discord、Signalといったプラットフォームの有効な代替案となります。
  * 個々人のデータ主権：電話番号やメールアドレス、連絡帳といった個人情報を特定の団体に明けわたさずに済む仕組みがあります。また、E2EE（エンドツーエンド暗号化）によってメールサーバーの管理者によるやりとりの閲覧を防ぐことができます。
  * 他のメールアプリとの相互運用性：SMTPとIMAPという世界的にありふれたプロトコルに基づいています。そのため、DeltaChatの非利用者ともメールでのやりとりができます。


## DeltaChatを使ってみる
DeltaChatには二通りの使い方があります。DeltaChat専用のメールアドレスを新たに作る方法と既存のメールアドレスを使う方法です。前者は「個々人のデータ主権」を守るのに有効です。後者は「他のメールアプリとの相互運用性」のために必要です。状況に応じて、両者を使い分けることをおすすめします。

<img src="/wp-content/uploads/2025/04/Screenshot-2025-04-22-at-13.05.06-1024x777.png" style="max-width:100%" />

## (a) DeltaChat専用のメールアドレスを作る
アプリのインストール後、「アカウントを追加」→「Create New Profile」を押します。

<img src="https://filedn.eu/lSVQwEEIDpO5dXwQG0B2seb/delta1.png" style="max-width:300px" />

つづいて、アカウント名を入力後「Agree & Create Profile」を押せば、アカウント作成が完了します。

<img src="https://filedn.eu/lSVQwEEIDpO5dXwQG0B2seb/delta2.png" style="max-width:300px" />

他のDeltaChatユーザーとのやりとりのためには、「QRコード」ページから表示可能なフレンド登録用QRコードを読みとってもらうか、「Share Invite Link」から共有可能なフレンド登録用リンクを押してもらう必要があります。

<img src="https://filedn.eu/lSVQwEEIDpO5dXwQG0B2seb/delta3.png" style="max-width:300px" />
上述の手続きにより、[nine.testrun.org](https://nine.testrun.org) という DeltaChat の開発者が運営する[DeltaChat専用サーバー](https://chatmail.at)上にメールアドレスの作成をすることになります。サーバーの所在地はドイツにあるため、[プライバシーポリシー](https://nine.testrun.org/privacy.html)は[EU一般データ保護規則](https://ja.wikipedia.org/wiki/EU%E4%B8%80%E8%88%AC%E3%83%87%E3%83%BC%E3%82%BF%E4%BF%9D%E8%AD%B7%E8%A6%8F%E5%89%87)（GDPR）に準じています。なお、[こちらのリスト](https://chatmail.at/relays)にあるように、世界各地にDeltaChat専用サーバーが立てられています。各サーバーのウェブサイト上のQRコードや招待リンクを使うことで、新しいメールアドレスを作成することができます。
DeltaChat専用サーバーは、E2E暗号化されていないメッセージを一切受けつけません。DeltaChatアプリは、QRコードやリンクによる事前のフレンド登録によって、E2E暗号化を可能にしています。裏を返せば、このような仕組みを持たないメールアプリとのやりとりは不可能です。そのため実質的には、DeltaChatアプリの使用者以外とのやりとりはできません（[Mailvelope](https://mailvelope.com/en)のような暗号化ツールを使う場合を除く）。
## (b) 既存のメールアドレスを使う
はじめに「アカウントを追加」→「Create New Profile」→「Use Other Server」→「Classic E-Mail Login」を押します。

<img src="https://filedn.eu/lSVQwEEIDpO5dXwQG0B2seb/delta4.png" style="max-width:300px" />

既存のメールアドレスとパスワードを入力後「ログイン」を押します（場合によっては「追加設定」が必要です）。また、Gmailを使う場合は「[２段階認証プロセス](https://myaccount.google.com/signinoptions/twosv)」を有効にした上で「[アプリパスワード](https://myaccount.google.com/apppasswords)」を生成し、それをパスワード欄に入力する必要があります。
メールを送るためには、相手先を連絡帳に追加しておく必要があります。「チャット」ページの右上にあるアイコンから「新規チャット」ページにうつり「Add Contact Manually 」を押して、相手先のメールアドレスと任意の名前を追加します。

<img src="https://filedn.eu/lSVQwEEIDpO5dXwQG0B2seb/delta5.png" style="max-width:300px" />
DeltaChatを使っていない相手ともメールのやりとりができます。「新規チャット」画面から「新規グループ」を作ることで、件名（＝グループ名）付きのメールを任意の数の相手先に送ることができます。いずれにしても、この場合、メールはE2E暗号化されずに送られます。
<img src="https://filedn.eu/lSVQwEEIDpO5dXwQG0B2seb/delta6.png" style="max-width:300px" />

相手がDeltaChatを使っている場合、フレンド登録用のQRコードやリンクを使って連絡先を追加することで、E2E暗号化されたやりとりをすることができます。この場合、サーバーの管理者によってやりとりの内容を閲覧されることはありませんが、その一方でIPアドレスをはじめとするメタ情報は暗号化されずにいます。
以上のことから、次のように使い分けることをおすすめします。
  * 匿名性を重視しないかぎりは、既存のメールアドレスでDeltaChatアプリを使う。相手先がDeltaChatユーザーであれば、E2EEを有効にする。そうでなければ、通常通りのメールを送る。
  * 匿名性を最大限に確保したい場合、気楽にDeltaChatユーザー同士でのやりたい場合は、DeltaChat専用のメールアドレスを使う。


## なぜDeltaChatなのか
既存のメールやチャットの多くが営利企業によるサービスとして提供されてきました。その結果、個々人のデータ主権が脅かされるようになりました。また、DiscordやLINEをはじめとするチャットサービスに関しては、プラットフォームの垣根をこえたやりとりができないことから、いわゆるネットワーク効果とロックイン効果が生まれ、サービスの劣化を招くことになりました（LINE＝ヤフーの問題については[こちらの記事](https://orillo.org/20250410/fuck-off-line/)を参照）。
このような問題を回避する手立てのひとつとして、巨大プラットフォームの提供するサービスの利用者になるのではなく、誰にでも自由に利用可能なプロトコルを使って各々がやりとりするということが考えられます。メールというありふれたプロトコルに基づいたDeltaChatはそのための有用なツールのひとつです。
このとき、メールとチャットをわざわざ二つの異なるコミュニケーションの形として峻別する必要はありません。メールプロトコルによるチャットは可能です。これまでは、DiscordやSlackのように洗練されたインターフェイスを備えたメールアプリがありませんでしたが、DeltaChatはその点を解決するものであると言えるでしょう。
## Orillo.orgのDeltaChatチャンネル
[Orillo.org](https://orillo.org)は、DeltaChatによる雑談チャンネルを運営しています。アプリをインストール済みの方は、をクリックすることでチャンネルにご参加いただけます。
###  「<span class="title-highlight">DeltaChatをはじめませんか</span>」への2件のフィードバック 
  1. ピンバック: [脱プラットフォームを考える⎯⎯まずはLINEをやめてみる – Orillo](https://orillo.org/20250410/fuck-off-line/)
