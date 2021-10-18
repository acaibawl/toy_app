# README
Ruby on Rails チュートリアル

[第2章 Toyアプリケーション](https://railstutorial.jp/chapters/toy_app?version=5.1#code-validates_content_presence)  

``` bash
heroku create
git push heroku master
# 作業環境の5000番ポートエラーでheroku runが正常に動作しない為detachedで実行
heroku run:detached rails db:migrate
```