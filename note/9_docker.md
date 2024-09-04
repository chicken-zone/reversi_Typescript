## Docker で MySQL をセットアップ

![alt text](image-60.png)

- Mysql にアクセスするためのユーザー名やパスワードを設定したり通信ポートの設定をしている
  ![alt text](image-61.png)

```
docker-compose up -d

## windowsはコマンドが違う可能性あり
```

- 上記コマンドで実行

- MySQL のコンテナが立ち上がる為、下記コマンドを実施すると MySQL のコンテナの起動状態を確認できる

![alt text](image-62.png)

- 起動した MySQL に接続する
  ![alt text](image-63.png)

- このように MySQL のプロンプトが返ってくれば OK
  ![alt text](image-64.png)

## シェルスクリプト

- 長いコマンドを短縮できるようになる
  ![alt text](image-65.png)

## MySQL のコンテナを削除する方法

- 下記のコマンドで削除できる

```
docker-compose down
```
