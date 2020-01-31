# 最新情報

## 技術書典8に出ます

[![](/assets/img/cc_tbf08.png)](https://techbookfest.org/event/tbf08/circle/5650897719787520)

正確な需要予測（とサークル関係者の承認欲求の刺激ｗ）のためWebサイト上でのサークルチェックをお願いします！

- 配置: 「初日(2020/2/29)く05」
- 頒布物予定
    - 新刊: "OAuth of the Gatewatch" (仕様未定)
    - 既刊: "DNSDNS Resolution append mix" (詳細仕様未定)
        - "DNSDNS Resolution"に技術書典6の当日頒布ペーパーとブログ記事2点を追加した拡張版です
    - "Dark Depths of SMTP", "バージョン管理 with Pijul"は物理見本のみとなります

## 技術書典6新刊「DNSDNS Resolution」

[![](/assets/img/ddrbook_cover.png)](/books/dnsdns-resolution)

- 頒布イベント
    - 技術書典6(2019/4/14)
- 仕様
    - 物理本: 64p, 頒布価格600円
        - 物理版は技術書典6当日中に完売いたしました。以降電子版のみの頒布となります。
    - 電子版: 当日頒布ペーパーの内容を追加した68p, 頒布価格400円
        - [電子版booth.pmページ](https://cryptic-command.booth.pm/items/1317266)

## コミックアカデミー17新刊「Computer Science Head-Start Guide 2018 Edition」

[![](/assets/img/cshsg_cover.png)](/books/cs-headstart-guide)

- 仕様: 72p, 頒布価格500円(予定)

五月祭で予告した初心者向けコンピュータ入門書、ついに着弾！コンピュータ科学とは何か、コンピュータ科学以前のコンピュータの話、プログラミングの始め方など、Cryptic Commandはコンピュータ科学を始めたいみなさんを全力で応援します！

### 過去のイベント参加情報

- 2018/04/22(日): 「[技術書典4](https://techbookfest.org/event/tbf04)」 @ 秋葉原UDX アキバ・スクエア
    - 配置「く-44」サークル「N4+」さんへの委託となります。sylph01は該当ブースにいる予定
- 2018/05/19(土): 「[コミックアカデミー16](https://comiaca.com/)」 @ 東京大学 本郷キャンパス
    - 2日間開催のイベントですが土曜日のみの参加の予定です
    - 「Dark Depths of SMTP」に加えて、コミアカ限定のペーパーの頒布があります
- 2018/10/08(月祝): 「[技術書典5](https://techbookfest.org/event/tbf05)」 @ 池袋サンシャインシティ2F 展示ホールD（文化会館ビル2F）
    - 配置「お-13」、[サークルページはこちら](https://techbookfest.org/event/tbf05/circle/32360001)
- 2018/11/25(日): 「[コミックアカデミー17](https://comiaca.com/)」 @ 東京大学 **駒場キャンパス**
    - 3日間開催のイベントですが日曜日のみの参加の予定です
    - 駒場祭の併設イベントのため、コミアカ16とは違い駒場キャンパスでの開催です
- 2019/04/14(日): 「[技術書典6](https://techbookfest.org/event/tbf06)」 @ 池袋サンシャインシティ2F 展示ホールD（文化会館ビル2F）

# 最近の投稿

{% for post in site.posts limit: 1 %}
<div class="posts">
  <h2>
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
  </h2>
  <p>
    {{ post.content | strip_html | truncate: 350 }}
  </p>
  <p>
    <a href="{{ site.url }}{{ post.url }}">続きを読む</a>
    <span class="post-date" style="margin-top:3px"><i class="fa fa-calendar" aria-hidden="true"></i> {{ post.date | date_to_string }}</span>
  </p>
</div>
{% endfor %}
