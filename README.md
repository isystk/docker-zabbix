🌙 docker-zabbix
====

![GitHub issues](https://img.shields.io/github/issues/isystk/docker-zabbix)
![GitHub forks](https://img.shields.io/github/forks/isystk/docker-zabbix)
![GitHub stars](https://img.shields.io/github/stars/isystk/docker-zabbix)
![GitHub license](https://img.shields.io/github/license/isystk/docker-zabbix)

## 📗 プロジェクトの概要

Zabbix サーバーのサンプルです。


## 🌐 Demo

## 💬 使い方

```
# 下準備
$ ./dc.sh init

# サーバーを起動する
$ ./dc.sh start

# データベースが立ち上がるまで少し待ちます。(初回は5分程度)

# ブラウザでアクセス
$ open http://localhost:8080/

ログインID / パスワード
admin / zabbix

# ZabbixAgentを監視設定に追加する
ホスト－ホストの作成
```
名前：sample-host
グループ：sample
エージェントのインターフェース
    DNS名：zabbix_agent
    接続方法：DNS
テンプレート：Template Module Linux CPU by Zabbix agent
```

# AgentにSSHで接続する
$ ./dc.sh agent login
> apk add stress-ng
> stress-ng -c 1 -q &

```

## 🎨 参考

| プロジェクト| 概要|
| :---------------------------------------| :-------------------------------|
| [docker-composeを使ってZabbixの環境を作成する](https://qiita.com/saeco_cco/items/5f2a38903c674fc080ee)| docker-composeを使ってZabbixの環境を作成する|
| [zabbixをdocker-composeで動かす](https://hakengineer.xyz/2018/08/16/post-1556/)| zabbixをdocker-composeで動かす|

## 🎫 Licence

[MIT](https://github.com/isystk/docker-zabbix/blob/master/LICENSE)

## 👀 Author

[isystk](https://github.com/isystk)


