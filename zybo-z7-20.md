# Zybo Z7-20の情報ページ

DigilentのZynqを搭載したFPGAボード Zybo Z7-20に関する情報をまとめました。

## PetaLinux

Digilent社はZybo Z7用のPetaLinuxを公開しています。

* [Digilent/Petalinux-Zybo-Z7-20](https://github.com/Digilent/Petalinux-Zybo-Z7-20)

Zybo Z7-20用PetaLinuxで使用しているハードウェアの定義です。
Vivadoでプロジェクトを作って、そこからBSPを生成できます。
自分で拡張したハードウェアで、PetaLinuxでPetaLinuxを動かせます。

* [Digilent/Zybo-Z7-20-base-linux](https://github.com/Digilent/Zybo-Z7-20-base-linux) 

Digilent社の各種ボードのPetaLinuxのサポート状況情報

* [Petalinux Support for Digilent Boards [Reference.Digilentinc]](https://reference.digilentinc.com/reference/software/petalinux/start) 

DigilentのVivado向けのIPライブラリ

* [Digilent/vivado-library](https://github.com/Digilent/vivado-library)

## 参考になるページ

* [Zybo 開発環境構築記: Ryuzのブログ](http://ryuz.txt-nifty.com/blog/2018/04/zybo-2f5e.html)

実際にシンプルなハードウェアをZyboで定義して、それをPetaLinuxに読ませてLinuxイメージを生成する手順が細かく説明されている。

* [ZYBO (Zynq) 初心者ガイド (8) Linux起動する - Qiita](https://qiita.com/iwatake2222/items/6e6915f7318689818368) 

全部入りLinuxのブートイメージ。Zybo Z7-20用もある。

* [FPGA+SoC+Linux+Device Tree Overlay+FPGA Region(ブートイメージの提供) - Qiita](https://qiita.com/ikwzm/items/7e90f0ca2165dbb9a577)
