# 最新情報

## 技術書典13に出ました

[![](/assets/img/rust-script-book.png)](/books/rust-script-book)

- 新刊: 『[ひたすら雑にRustを書く本](/books/rust-script-book)』
    - 仕様: 30p, 頒布価格500円
- 既刊更新: 『[DNSDNS Resolution -append mix-](/books/dnsdns-resolution)』
    - 仕様: 85p, 頒布価格500円
    - 以前の版の購入者向け: 上記ページより追加分の文章は読むことができます

# 最新の投稿

{% for post in site.posts limit: 5 %}
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

# 過去のイベント参加情報

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
