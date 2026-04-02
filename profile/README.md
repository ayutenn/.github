# ayutenn
![エビフライトライアングル](./ayutenn.png "ayutenn")

ayutennは、 [@tyau_nen_](https://x.com/tyau_nen_) によるPHP webフレームワークです！

## ayutennとは？
ayutennは、個人利用を目的としたwebフレームワークです。
github上で公開されていますが、**俺以外の利用は推奨しません。**

## 構成
- **[ayutenn-skeleton](https://github.com/ayutenn/ayutenn-skeleton)**: ayutennのプロジェクトテンプレートです。
- **[ayutenn-core](https://github.com/ayutenn/ayutenn-core)**: ayutenn本体。メイン機能郡です。
- **[ayutenn-css](https://github.com/ayutenn/ayutenn-css)**: ayutennのためのcss・jsライブラリです。

## 思想
### なるべくシンプル
ayutennが作られた背景は、「既存のフレームワークは、難しくてよくわからん」でした。
俺は車輪の再発明を避ける為に、なるべくシンプルで使用方法がわかりやすいフレームワークを作るべきです。

### YAGNIの法則の尊重
[You aren't gonne need it.](https://ja.wikipedia.org/wiki/YAGNI)
ayutennは、俺が使う機能だけで構成されていなくてはいけません。
あったら便利だろう、という意図でコードを書いてはいけません。

### 俺が上げ膳、俺に据え膳
このフレームワークは俺しか使用しません。つまり、俺の開発体験が何よりも優先されます。俺にとって直感的であればどのような非効率もアンチパターンも許容します。

## How to use
### インストール
```bash
composer create-project tyaunen/ayutenn-skeleton MyProject --repository="{\"type\":\"vcs\",\"url\":\"https://github.com/tyaunen/ayutenn-skeleton.git\"}"
```
