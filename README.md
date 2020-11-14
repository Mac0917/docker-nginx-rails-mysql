# docker nginx rails mysql 環境
docker nginx rails mysql の開発環境が以下の手順で入手できます。
<br>
ruby 2.5.1
rails 5.2
mysql 5.7
nginx 1.15.8

dockerを自分のpcにインストール docker for macとか
docker-compose をインストール

好きなディレクトリで実行<br>
`git clone https://github.com/Mac0917/docker-nginx-rails-mysql.git`

移動<br>
`cd docker-nginx-rails-mysql`

環境作成<br>
`docker-compose up -d`

データベース作成<br>
`docker exec -it docker-nginx-rails-mysql_app_1 bash`<br>
`rails db:create`

アクセス
http://localhost/


