# Dark Depths of SMTP

![](/assets/img/ddbook_cover.png)

- 頒布イベント
    - 技術書典4(2018/4/22)
    - コミックアカデミー16(2018/5/19)
- 表紙イラスト: [はんぺん氏(@atamapokopoko)](https://twitter.com/atamapokopoko)
- 仕様: 48p, 頒布価格600円@物理、400円@電子
    - [電子版booth.pmページ](https://cryptic-command.booth.pm/items/1136808)
    - [物理版booth.pmページ](https://cryptic-command.booth.pm/items/892981)
        - 物理版は技術書典5にて完売いたしました。以降電子版のみの頒布となります。

[「針の音楽団」](http://harimusic.net/)の整理券システムにおけるメールサーバー運用事例をもとにした、メールサーバーセットアップガイド、迷惑メールフィルタ対策、暗号化周辺を解説した本です。

----

## 内容

### 第1章: SMTPとそれらを取り巻くプロトコルの紹介
* メール送信に関わるアクター(MTA, MDA, MUA, MRA, MSA, ...)
* サブミッションポート(port 587)について
* POP3、IMAP(SMTPとの関連を軽く触れる程度)
* SPF, DKIM, DMARC

### 第2章: Postfixを使った実際の設定

### 第3章: 迷惑メールフィルタ対策
* SPF, DKIM, DMARCのFAIL
* Googleの迷惑メール対策ガイドライン
* MSN系の迷惑メール対策ガイドライン
* IP逆引きの設定

### 第4章: Eメールの暗号化
* Eメールにおける「SSL」「TLS」
* End-to-End暗号化を実現するには

----

## アップデート情報

### 12/13/18 - Extra Chapter: 暗号屋から見たEメールの死について(EFAIL解説)

BOOTH購入者向けメッセージで予告していた記事をやっとアドベントカレンダーを期に書きました。[こちらからお読みいただけます。](https://sylph01.hatenablog.jp/entry/20181211_efail)
