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

## 開発環境の起動

```
$ git clone https://github.com/ito-artsfarm/itoartsfarm2016-vccw.git
$ cd itoartsfarm2016-vccw
$ vagrant up
```

起動したら以下のURLで参照できます。

http://192.168.33.10/

WordPressのソースコードは `www/wordpress/` 配下にあります。

## 設定情報

### 管理画面

開発環境の管理画面には以下のアカパスでログインできます。

Username: admin  
Password: admin

