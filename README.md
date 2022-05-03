# bundle-knifezero

KnifeZero 環境をインストールする

##  インストール手順

- リポジトリをクローンする

```bash
git clone --recursive git@gitlab.com:takahiro-itou/bundle-knifezero.git
cd  bundle-jekyll
```

- インストールスクリプトを実行する

```bash
./Install.sh
```

- なお Install.sh の内容は下記の通り
- 手動でこの二行を実行しても良い。

```bash
bundle config set --local path 'vendor/bundle'
time bundle install
```
