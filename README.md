# plusコマンド
![test](https://github.com/rikuhotakeda/robosys2022/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字を足す。

## インストール方法
コピーしたいディレクトリで、以下の操作をする。
* git clone https://github.com/rikuhotakeda/robosys2022

## 必要なソフトウェア
* Python 3.6～3.10
* Ubuntu18.04

## 使い方
robosys2022のディレクトリに移動する。  
```
$ cd robosys2022
```

以下のようにpulsを実行する。右のコマンド./plusに、標準出力であるseq 5を標準入力として読み込んでいる。  
```
$ seq 5 | ./plus  
15
```

## テスト環境
* Ubuntu18.04

## 権利表記
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです。
* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* このREADME.mdはインストール方法の記載に関してaoi-daigujiに助言を受け、許可を得た上で参考にしています。
* @ 2022 Rikuho Takeda
