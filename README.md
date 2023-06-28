# Tomohide-Kebukawa.github.io

このリポジトリは、[Tomohide-Kebukawa.github.io](https://Tomohide-Kebukawa.github.io)で公開しているサイトのソースです。

## pages

サイトは基本的にmdで記述しています。
mdファイル更新後に実行されるpagesにて、htmlにビルドしています。
例外は、トップページです。

トップページを例外にしたのには、理由があります。
主な理由は、pagesで生成するhtmlのデザイン的な限界です。
単に私の勉強不足かもしれませんが、pagesの生成するhtmlでは、sectionを複数入れることができなかったので、htmlを手書きしました。

## _layouts

pagesによってビルドする際に、_layoutsフォルダにあるテンプレートを利用して、デザインを決めています。
