# battletanks_server

battletanksサーバーサイドアプリケーション(Ruby on Rails)

## 導入

実行までの作業覚え書き

### 準備

bundler実行までの準備

* rubyインストール（必要であればrbenv等）
* `gem update`実行
* httpd設定（Phusion Passenger等）

### bundle install

```bash
$ bundle install --path=vendor/bundle
```

`--path`オプションを忘れないこと。

### マイグレーション

```bash
$ bundle exec rake db:migrate RAILS_ENV=<environment(e.g. production, development, test ...)>
```

### Github Flavored Markdown

#### リファレンス

<https://help.github.com/articles/github-flavored-markdown/>

#### エディタ（シミュレータ）

<http://jbt.github.io/markdown-editor/>

#### 他

qiita形式

<http://qiita.com/Qiita/items/c686397e4a0f4f11683d>

