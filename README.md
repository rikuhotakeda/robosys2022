# plusコマンド
![test](https://github.com/rikuhotakeda/robosys2022/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字を足す。

## 使い方（python3）
初めに、plusのコードを貼り付けたplus.pyというファイルを作る。
$ vi plus.py

続いて、実行権限の有無を確認する。無い場合は、chmodを使用して実行権限を与える。
$ ls -l plus.py
$ chmod +x plus.py

次に、plusというファイル名に変更する。
$ mv plus.py plus

plusの実行が行える。
以下は実行の一例である。右のコマンド./plusに、標準出力であるseq 5を標準入力として読み込んでいる。
$ seq 5 | ./plus
15

## ダウンロード

## インストール方法
このリポジトリのコードをコピーして保存したいディレクトリに以下のようにクローンする。
* git clone git@github.com:rikuhotakeda/robosys2022.git

## 必要なソフトウェア
* Python 3.6～3.10

## テスト環境
* Ubuntu18.04

## テストの結果


## 権利関係
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです。
* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* このREADME.mdはインストール方法の記載に関してAoi Daigujiの助言を受けています。
* @ 2022 Rikuho Takeda
