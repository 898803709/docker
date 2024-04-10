# dockerを練習用のリポジトリ

# 環境変数を設定する

```
export VARIABLE_NAME=<your password>
```

# 設定した環境変数を確認する

```
echo $VARIABLE_NAME
```

# rails newを実行する
```
docker-compose run --entrypoint "rails new ."
```

# サービスを起動する
```
docker-compose up
```


## コンテナの中に入る
```
docker-compose exec web bash
```