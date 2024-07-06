# リポジトリのクローン
```
git clone git@github.com:yuichi04/MySQL.git
```

# コンテナの起動
```
docker-compose up -d
```

# 環境変数の設定
ルートディレクトリに`.env`ファイルを作成し、以下の環境変数を設定してください。
- MYSQL_ROOT_PASSWORD
- MYSQL_DATABASE
- MYSQL_USER
- MYSQL_PASSWORD

# Dockerコンテナ接続用コマンド
```
# MySQL
docker exec -it mysql bash

# PostgreSQL
docker exec -it postgres-container psql -U pquser -d pqdatabase
```
