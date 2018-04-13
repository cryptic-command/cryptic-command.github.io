# 全記事一覧

<ul>
{% for post in site.posts %}
  <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a> / {{ post.date | date_to_string }}</li>
{% endfor %}
</ul>