# DNSDNS Resolution

![](/assets/img/ddrbook_cover.png)

- 頒布イベント
    - 技術書典6(2019/4/14)
- 仕様
    - 物理本: 64p, 頒布価格600円
        - 物理版は技術書典6当日中に完売いたしました。以降電子版のみの頒布となります。
    - 電子版: 当日頒布ペーパーの内容を追加した68p, 頒布価格400円
        - [電子版booth.pmページ](https://cryptic-command.booth.pm/items/1317266)

----

**"Show me your moves, Government!"**

『Dark Depths of SMTP』に続く、「個人で立ててはいけないサーバー」シリーズ第2弾！
DNSのセキュリティ・プライバシーについてフォーカスしたDNS解説書です。OP53B・Encrypted SNIブロッキングなどDNSへの「攻撃」が話題の昨今、自由なインターネットを取り戻すためのプロトコル動向を解説します。

インターネットの自由という問題は全ネットユーザーに関わる問題で必然的にインターネットに関わる技術者すべてに知ってほしい話ではあるのですが、具体的に想定対象読者を絞り込むならば以下のような感じです。

* DNSの仕組みを入門書からもう少し掘り下げて知りたい
* DNSのセキュリティ面が不安、DNSへの攻撃について知りたい
* カ○ンゴが暴走してるのはなんとなくTwitterの識者の発言見てるとわかるのだけど具体的にブロッキングで何がマズいのか知りたい
* 表現の自由、インターネットの自由を守るためのインターネット側の防御・対策について知りたい

----

# 目次

## はじめに: Show me your moves

## 第1章: DNSの基礎 - Lesson by DJ
- DNSの登場人物
- 名前解決のプロセス
- インターネットの必須要素としてのDNS

## 第2章: DNSに対する攻撃 - On the Break

### DNSの利用
- ホモグラフ攻撃
- ドロップキャッチ

### DNSの運用
- Lame Delegation
- 幽霊ドメイン名脆弱性

### DDoS攻撃
- DNSアンプ攻撃
- DNS水責め攻撃

### キャッシュポイズニング攻撃
- 原理
- Müller-Kaminsky攻撃
- 第一フラグメント便乗攻撃

## 第3章: ブロッキング、検閲、その他プライバシーの懸念 - Somehow You Found Me
- 通信の秘密と正当業務行為
- IIJによるDNSフィルタリング
- OP53BによるDNSブロッキング
- SNIブロッキングとEncrypted SNI
-- Server Name Indication
-- Encrypted SNI
-- 対策
- パブリックDNSは救いか否か？

## 第4章: DNSSEC - POSSESSION
- DNSSECの紹介
- インターネットを救う7人の勇者？
- DNSSECの問題
-- RSAの使用に起因する問題
-- 運用ミスの影響範囲
-- そもそもの信頼のあり方について

## 第5章: セキュアなプロトコル - Dancer in the flare

### DNS over (D)TLS
- 互換性とプロファイル
- 証明書の検証方法
- 対応状況
- 検閲に対する弱点

### DNS over HTTPS
- 概要
- 名前解決のURLに関する取り回し
- DNS over TLSに対する利点
- 対応状況

### 検閲とのいたちごっこ

## Extra Chapter: ラブライブ！ドメイン名乗っ取り（当日頒布ペーパーの内容と同一です）

## おわりに - Over the "Period"

----

# アップデート情報

## 2022/09/07 - Extra Chapterその4: Oblivious DNS over HTTPS

技術書典13に出るにあたってExtra Chapterその4「[Oblivious DNS over HTTPS](/2022/09/10/odoh.html)」を書き下ろしました。

また、Extra Chapterその2として収録している[Application Behavior Considering DNS](https://d.s01.ninja/entry/20191219-dns-updates-abcd)もこのページからリンクします。

## 2019/12/22 - Extra Chapterその3: anti-DNSSEC - PARANOiA Revolution

DNSSEC章の最後に触れているanti-DNSSECの主張についてより掘り下げた内容、また締めた文章の「修正」についてを記述したExtra Chapterを書きました。[こちらからお読みいただけます。](https://sylph01.hatenablog.jp/entry/20191222/1577010669)
