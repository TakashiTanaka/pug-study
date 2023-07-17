# Pugのテスト

## [case1 基本](./case1/index.html)

``` pug
doctype html 
html(lang="ja")
  include head.pug
  body 
    h1 Pugのテストです
    p これでhtmlに出力されるはず
    p.test testというクラスを付加したparagraph
    p#test testというIDを付加したparagraph
    p(class="test2") testというクラスを付加したparagraph
    p(id="test2") testというIDを付加したparagraph
    img(src="./hoge.jpg")
```

## [case2 layoutを使った例](./case2/index.html)

## [case3 gulpと組み合わせてhtmlをjsonから生成する例](./case3/index.html)

## [case4 case3のgulpfile.jsの書き方を推奨されているモジュールを使った方法に書き換えてみる](./case4/index.html)

## [case5 extendsのテスト](./case5/index.html)

## [case6 appendのテスト](./case6/index.html)

## [case7 webpackでpugをコンパイルするテスト](./case7/index.html)

参考:[webpackでPugのコンパイル環境を作成してみる \| 大阪市天王寺区ホームページ制作 \| 合同会社デザインサプライ\-DesignSupply\. LLC\-](https://designsupply-web.com/media/programming/6721/)
