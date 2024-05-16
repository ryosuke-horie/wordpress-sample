# WordPress Dockerサンプル

## 環境構築
＊docker compose v2がインストール済み
```
docker compose up -d
```

localhost:8000を開き、設定開始
- 日本語
- サイトのタイトル：wp-sample
- ユーザー名:wp-sample
- パスワード:q5^1FbYwM(u3MiwgMB
- メール: test@example.com
- 検索エンジンでの表示>  検索エンジンがサイトをインデックスしないようにする

## シャットダウンとクリーンアップ
```
# 停止
docker-compose down

# データごと削除
docker-compose down --volumes
```
