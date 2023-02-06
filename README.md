## 環境構築手順 / Instruction

コンテナ起動
```
docker-compose up
```

コンテナ内でLaravelをインストール
```
docker-compose exec app bash

composer create-project --prefer-dist laravel/laravel プロジェクト名 "バージョン"
# 例 composer create-project --prefer-dist laravel/laravel LaravelApp "8.*"
# バージョン指定せずにインストールすると最新版がインストールされる。
```

## 動作確認
http://localhost:8000  
Laravelのウェルカムページが表示されればOK!