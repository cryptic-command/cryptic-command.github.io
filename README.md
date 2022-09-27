# cryptic-command.github.io

To build site, install Ruby and Bundler, then do the following:

```
$ bundle install
$ bundle exec jekyll serve
```

With the server running, you can see the site at `http://localhost:4000`.

----

## update 2022/09/27: 「最新情報」の運用について

- 内容
  - とりあえず最新1件のみトップページに書く
  - ここが更新されるときに過去の内容を `_posts` に動かす
- このような運用を取る理由
  - postsにすると時系列が整理できて便利
  - しかしJekyllの仕様としてpostsの内容を `strip_html` しないと中途半端にHTMLタグが読み込まれレイアウトが崩れる。 `strip_html` すると画像が出てこない
  - なので画像が出てきてほしい最新情報だけトップページに置くようにする
