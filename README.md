# Tomohide-Kebukawa.github.io

このリポジトリは、[Tomohide-Kebukawa.github.io](https://Tomohide-Kebukawa.github.io)で公開しているサイトのソースです。

以下はGithubを勉強中の自分のために書く備忘録的なものです。

## pages

サイトは基本的にmdで記述しています。
mdファイル更新後に実行されるpagesにて、htmlにビルドしています。
例外は、トップページです。

トップページを例外にしたのには、理由があります。
主な理由は、pagesで生成するhtmlのデザイン的な限界です。
単に私の勉強不足かもしれませんが、pagesの生成するhtmlでは、sectionを複数入れることができなかったので、htmlを手書きしました。

## _layouts

pagesによってビルドする際に、_layoutsフォルダにあるテンプレートを利用して、デザインを決めています。

mdで書かれたページの冒頭には、どのレイアウトを使うかが記述されています。
例えば、次のように書かれている場合は、pagesによってhtmlにビルドする際に、default.htmlのデザインでビルドされます。

```
---
layout: default
---
```
