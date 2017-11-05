# WRITE HTML

```
$ cd free-game # or free-music or music
$ bundle exec jekyll s
// You should access http://localhost:4000/ with your browser.
```

# DEPLOY

```
$ cd free-game # or free-music or music
$ bundle install && rbenv rehash
$ bundle exec jekyll build
$ open _site
// _site ディレクトリ以下にファイルが出来るのでそれを S3 へアップロード
```

# LICENSE

2009~2017 (C) Atelier Kiraly All Rights Reserved.
