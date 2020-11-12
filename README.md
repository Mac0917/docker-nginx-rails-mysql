# docker nginx rails mysql 環境
docker nginx rails mysql の開発環境が以下の手順で入手できます。

dockerを自分のpcにインストール docker for macとか

好きなディレクトリで実行<br>
`git clone https://github.com/Mac0917/docker-nginx-rails-mysql.git`

移動<br>
`cd docker-nginx-rails-mysql`

環境作成<br>
`docker-compose up -d`

データベース作成<br>
`docker exec -it docker-nginx-rails-mysql_app_1 bash`
`rails db:create`

アクセス
http://localhost/


