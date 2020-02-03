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

## Digilentのチュートリアル

* [Zybo Z7 Reference Manual [Reference.Digilentinc]](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/reference-manual) Zybo Z7リファレンスマニュアル

* [Getting Started with Vivado IP Integrator [Reference.Digilentinc]](https://reference.digilentinc.com/vivado/getting-started-with-ipi/start?_ga=2.107851842.133077564.1579780347-1146242163.1575210715)


## Xilinx documents

ZilinxのSDK関連のドキュメントサイト

* [Software Development Kit (SDK)](https://japan.xilinx.com/support/documentation-navigation/self-paced-tutorials/software-development-kit-sdk.html)

### チュートリアル

* [Vivado Design Suite チュートリアル: エンベデッド プロセッサ ハードウェア デザイン(UG940)](https://japan.xilinx.com/support/documentation/sw_manuals_j/xilinx2019_2/ug940-vivado-tutorial-embedded-design.pdf)
* [Zynq-7000 All Programmable SoC:エンベデッドデザインチュートリアル -- 効率的なエンベデッドシステムを構築するためのハンディガイド UG1165 (v2017.4)](https://www.xilinx.com/support/documentation/sw_manuals_j/xilinx2017_4/ug1165-zynq-embedded-design-tutorial.pdf) これは良い

### リファレンス

* [Vivado Design Suite Tclコマンドリファレンス](https://japan.xilinx.com/support/documentation/sw_manuals_j/xilinx2019_1/ug835-vivado-tcl-commands.pdf)

Synthesisのマニュアル。4章で、種々の回路の構成要素(シフトレジスタ、乗算器など)のVerilog/VHDLでの記述法を説明している。

* [Vivado Design Suiteユーザーガイド 合成 UG901 (v2018.2)](https://www.xilinx.com/support/documentation/sw_manuals_j/xilinx2018_2/ug901-vivado-synthesis.pdf)

IPを利用してデザインをする方法。

* [Vivado Design Suiteユーザーガイド IPを使用した設計 UG896 (v2017.1)](https://www.xilinx.com/support/documentation/sw_manuals_j/xilinx2017_1/ug896-vivado-ip.pdf)

* [Vivado IP Integratorでよく使う便利なIPコア16選 - Qiita](https://qiita.com/s_nkg/items/f2928fb727238d14f23f)
* [FPGAの部屋 IP Integrator のブロックデザインで使うと便利なIP](https://marsee101.blog.fc2.com/blog-entry-3209.html)


## 参考になるページ

* [Zybo 開発環境構築記: Ryuzのブログ](http://ryuz.txt-nifty.com/blog/2018/04/zybo-2f5e.html)

実際にシンプルなハードウェアをZyboで定義して、それをPetaLinuxに読ませてLinuxイメージを生成する手順が細かく説明されている。

* [ZYBO (Zynq) 初心者ガイド (8) Linux起動する - Qiita](https://qiita.com/iwatake2222/items/6e6915f7318689818368) 

全部入りLinuxのブートイメージ。Zybo Z7-20用もある。

* [FPGA+SoC+Linux+Device Tree Overlay+FPGA Region(ブートイメージの提供) - Qiita](https://qiita.com/ikwzm/items/7e90f0ca2165dbb9a577)
