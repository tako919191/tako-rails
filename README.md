# tako-rails

## 初期化

1. DBの初期化
```
$ docker-compose build
$ docker-compose down
$ docker-compose run rails rake db:create
```

2. 起動
```
$ docker-compose up
```

## 開発

1. コンテナ起動中
```
docker-compose exec ..
```
例：
```
docker-compose exec rake db:migrate
```

2. コンテナ停止中
```
docker-compose run ..
```
例：
```
docker-compose run rake db:migrate
```
