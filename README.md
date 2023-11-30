# robosys2023
# plusコマンド
[![test](https://github.com/isseikimura613/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/isseikimura613/robosys2023/actions/workflows/test.yml)

## ソフトの内容
* 標準出力から数字を読みこみ、1から読み込んだ数字までを使い以下の計算をする。
   * 足し算
   * かけ算
   * 足し算とかけ算の合計

## 使い方
* インストール方法
```
$ git clone https://github.com/isseikimura613/robosys2023.git
```

* 実行方法

以下のコマンドでディレクトリに移動する。
```
$ cd robosys2023/
```

以下のコマンドで実行する。
例として5を入力する。
```
$ seq 5 | ./plus
```

* 実行結果
```
15 120 135
```
   * 左から足し算、かけ算、足し算とかけ算の合計の値。

## 必要なソフトウェア
   * Python
   * テスト済み: 3.7~3.10

## テスト環境
* Ubuntu 20.04

# ライセンス
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されています。
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
    * [ryuichiueda/my_slides/robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* ©2023 Issei Kimura 
