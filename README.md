# docker環境 Laravel用

### ローカル環境
- docker 19.03
- docker-compose 1.27.4
- git 2.17

### 作成する環境
- PHP 7.4
- MySQL 8.0
- nginx 1.18
- composer 2.0.14

### サービスの構築
```
$ docker-compose build
```

### コンテナの作成と立ち上げ
```
$ docker-compose up
```

### アプリのコンテナに接続
```
$ docker-compose exec app bash
```

### Laravel6系インストールコマンド
```
$ composer create-project --prefer-dist "laravel/laravel=6.*" .
```