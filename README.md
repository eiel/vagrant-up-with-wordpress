# これは何

Wordpress が入った 仮想マシンがすぐに欲しい時に使った Vagrantfile です。

# 使い方

各種準備ができていれば clone して

```
$ vagrant up
```

するだけです。

## 各種準備

* vagrant のインストール
* vagrant-berkshelf のインストール
* vagrant-omnibus のインストール

### vagrant のインストール

http://www.vagrantup.com/ からインストールしましょう

Macなら [homebrew-cask](https://github.com/caskroom/homebrew-cask) が楽です。


### vagrant-berkshelf のインストール

https://github.com/berkshelf/vagrant-berkshelf

```
vagrant plugin install vagrant-berkshelf --plugin-version ">= 2.0.1"
```

### vagrant-omnibus のインストール

https://github.com/schisamo/vagrant-omnibus

```
vagrant plugin install vagrant-omnibus
```

# TODO

* 日本語化してない
* FTPの設定をしてない
