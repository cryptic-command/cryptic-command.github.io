# 最新情報

ここに何か書く。

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