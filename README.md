# リポジトリのクローン
```
git clone git@github.com:yuichi04/MySQL.git
```

# コンテナの起動
```
docker-compose up -d
```

# 環境変数の設定
ルートディレクトリに`.env`ファイルを作成し、以下の環境変数に任意の値を設定してください。
```
MYSQL_ROOT_PASSWORD=password
MYSQL_DB=mysqldb
MYSQL_USER=mysqluser
MYSQL_PASSWORD=mysqlpassword

POSTGRES_DB=pqdb
POSTGRES_USER=pquser
POSTGRES_PASSWORD=pqpassword
```

# Dockerコンテナ接続用コマンド
```
# MySQL
docker exec -it mysql bash

# PostgreSQL
docker exec -it postgres psql -U pquser -d pqdatabase
```
