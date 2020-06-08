# 広島市 新型コロナウイルス感染症対策サイト
# [![Mie Prefecture COVID-19 Task Force website](https://github.com/inspired-fox/covid19-hirosima_city/blob/develop/static/logo-hiroshima-city.png)](https://github.com/inspired-fox/covid19-hirosima_city)

### 日本語 | [English](./README_EN.md) | [Spanish](./README_ES.md) | [Korean](./README_KO.md) | [Chinese (Taiwan)](./README_ZH_TW.md) | [Chinese (Simplified)](./README_ZH_CN.md)

これは、三重県の高専生有志チームが開発した、東京都の新型コロナウイルス感染症対策サイトの広島市版です。東京都新型コロナウイルス対策サイトのリポジトリからフォークしています。

## ライセンス
本ソフトウェアは、[MITライセンス](./LICENSE.txt)の元提供されています。

## 開発者向け情報

### 環境構築の手順

- 必要となるNode.jsのバージョン: 10.19.0以上

**yarn を使う場合**
``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev
```

**docker compose を使う場合**
```bash
# serve with hot reload at localhost:3000
$ docker-compose up --build
```

### ステージング・本番環境への反映

`master` ブランチがアップデートされると、自動的に `production` ブランチにHTML類がbuildされます。そして、本番サイト https://mie.stopcovid19.jp が更新されます。  
`develop`ブランチがアップデートされると、自動的に`dev_pages`ブランチにHTML類がbuildされます。そして、開発用サイト https://covid19-mie-dev.netlify.com/ が更新されます。
