# 最新情報

## 技術書典4新刊「Dark Depths of SMTP」

![](/assets/img/ddbook_cover.png)

- 表紙イラスト: [はんぺん氏(@atamapokopoko)](https://twitter.com/atamapokopoko)
- 仕様: 48p, 頒布価格600円(予定)

[→個別紹介ページ](/books/dark-depths-of-smtp)

## イベント参加情報

- 2018/04/22(日): 「[技術書典4](https://techbookfest.org/event/tbf04)」 @ 秋葉原UDX アキバ・スクエア
    - 配置「く-44」サークル「N4+」さんへの委託となります。sylph01は該当ブースにいる予定
- 2018/05/19(土): 「[コミックアカデミー16](https://comiaca.com/)」 @ 東京大学 本郷キャンパス
    - 2日間開催のイベントですが土曜日のみの参加の予定です
    - 「Dark Depths of SMTP」に加えて、コミアカ限定のペーパーの頒布があります

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
