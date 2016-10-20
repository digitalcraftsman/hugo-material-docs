---
date: 2016-10-20T21:20:00+09:00
title: Material for Hugo
type: index
weight: 0
---

## 美しいドキュメント

"Material"は速くて柔軟な静的サイトジェネレータ[Hugo](https://gohugo.io)のテーマです。
Googleの[マテリアルデザイン](https://www.google.com/design/spec/material-design/introduction.html)のガイドラインに沿って、レスポンシブデザインに完全対応。
様々なスクリーンサイズはもちろん、タッチ操作やマウス操作にも最適化されています。

![Materialのスクリーンショット](/images/screen.png)

Material はとても軽量です – JavascriptとCSSはゼロから書かれていて、30kB以下しかありません
（リソースを圧縮（minified、gzip圧縮）し、GoogleフォントとAnalyticsを除いたサイズ）。
それでも、とても高いカスタマイズ性を持ち、古いブラウザにもレベルを合わせることができます。


## Quick start

`git`を使ってインストールします:

```sh
git clone git@github.com:digitalcraftsman/hugo-material-docs.git themes/hugo-material-docs
```

## 特徴

- Googleのマテリアルデザインのガイドラインをベースにした、美しく、読みやすく、そしてユーザーフレンドリーなデザイン：
  レスポンシブデザインに完全対応し、[明確で、カスタマイズしやすいカラーパレット]({{< relref "getting-started/index.md#changing-the-color-palette" >}})、素晴らしいタイポグラフィ、さらには、美しい検索インターフェースとフッタを備えています。

- 十分テストされ、最適化されたJavascriptとCSS：
  クロスブラウザ対応した固定ヘッダ／スティッキーヘッダや、[checkbox hack](http://tutorialzine.com/2015/08/quick-tip-css-only-dropdowns-with-the-checkbox-hack/)とフォールバックを使ってJavascriptなしでも動作するドロワー、画面サイズが小さすぎるときにスクロールするレスポンシブなテーブル、そして洗練された印刷スタイルが用意されています。

- 追加された設定オプション：
  [プロジェクトのロゴ]({{< relref "getting-started/index.md#adding-a-logo" >}})や、著者や[GitHubやTwitterアカウント]({{< relref "getting-started/index.md#adding-a-github-and-twitter-account" >}})へのリンクだったり、GitHubプロジェクトのスターの数を表示することができたりします。

- iOS上でのウェブアプリケーション対応：
  ページがホーム画面に保存されたとき、nativeアプリケーションのように振る舞います。

詳しくは [getting started guide]({{< relref "getting-started/index.md" >}}) を御覧ください


## 謝辞

最後になりましたが、[Martin Donath](https://github.com/squidfunk)にとても感謝しています。
彼が、Hugoの姉妹版である[MkDocs](http://www.mkdocs.org/)用のオリジナルの[Materialテーマ](https://github.com/squidfunk/mkdocs-material)を作成してくれていなければ、このテーマはできなかったことでしょう。

さらに、Hugoを作成した[Steve Francia](https://gihub.com/spf13)とその[素晴らしいコミュニティ](https://github.com/spf13/hugo/graphs/contributors)にも感謝します。
