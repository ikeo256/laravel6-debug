# 初期設定

1. `.env`ファイルを作成して DB の設定を変更する。
```
$ cd src
$ cp .env.example .env
```

2. Composer をアップデートする。
```
$ composer update
```

3. アプリケーションキーを作成する。
```
$ php artisan key:generate
```

4. コンテナを作成、起動する。
```
$ docker-compose up -d
```

