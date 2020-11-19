# docker環境 Laravel用

### ローカル環境
- docker 19.03
- docker-compose 1.27.4
- git 2.17

### 作成する環境
- PHP 7.4
- MySQL 8.0
- nginx 1.18
- composer 1.10

### サービスの構築
```
$ docker-compose build
```

### コンテナの作成と立ち上げ
```
$ docker-compose build
```

### Laravel6系インストールコマンド
```
$ docker-compose exec app composer create-project --prefer-dist laravel/laravel "6.*"
```

### アプリのコンテナに接続
```
$ docker-compose exec app ash
```