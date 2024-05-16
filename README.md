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

## テーマのインストール
参考元： https://kinsta.com/jp/blog/how-to-install-a-wordpress-theme/#install-free
ダッシュボードから外観→テーマを開き、「新しいテーマを追加」
今回は→のテーマをダウンロード：https://businesspress.jp/theme/
Zip形式のままインストール可能。

外観＞テーマ でBusinesspressを有効化

## 検証したいこと
- shifterのようなSaaSを利用せずにHTML/CSS/JSに吐き出すことができるプラグイン等がないか
    - staticpress2019 : やりたいことではなかった。サイトを高速化するために検索等を捨てる選択肢。（多分）
- 簡易的なHPを楽に作れるか・無料テーマでそれなりのものがあるか調査
