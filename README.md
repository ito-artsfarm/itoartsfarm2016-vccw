# itoartsfarm2016-vccw

itoartsfarmのローカル開発環境です。

## 環境構築

VirtualBox、Vagrantのインストールが必要なので事前にインストールしてください。

### 1. Install VirtualBox.
https://www.virtualbox.org/

### 2. Install Vagrant.
http://www.vagrantup.com/

以下のコマンドでイメージをダウンロードします。

```
$ vagrant box add miya0001/vccw
```

## インストール

```
$ git clone https://github.com/ito-artsfarm/itoartsfarm2016-vccw.git
$ git clone https://github.com/ito-artsfarm/itoartsfarm2016-wp
$ cd itoartsfarm2016-vccw
$ vagrant up
```

起動したら以下のURLで参照できます。

http://192.168.33.10/

管理画面にアクセスして`itoartsfarm2016-wp`のテーマを設定してください。
`admin, admin` でログインできます。

http://192.168.33.10/wp-admin

`itoartsfarm2016-wp` ファイルを編集してテーマを編集できます。
編集すると開発環境でリアルタイムに確認ができます。

## 開発環境の起動

1度インストールを行えば、次回からは以下のコマンドで環境を起動できます。

```
$ cd itoartsfarm2016-vccw
$ vagrant up
```

## 設定情報

### 管理画面

開発環境の管理画面には以下のアカパスでログインできます。

Username: admin  
Password: admin

