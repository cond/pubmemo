# FPGA

## ZYBO/FPGA関連のリンク集

* [Vivado Design Suite](https://japan.xilinx.com/products/design-tools/vivado.html?resultsTablePreSelect=documenttype:User%20Guides#documentation) Xilnx公式ドキュメント集
* [Getting the PmodOLEDrgb to Work on Zybo: 10 Steps](https://www.instructables.com/id/Getting-the-PmodGPS-to-Work-on-Zybo/?_ga=2.25723837.1221445310.1551239693-1015329430.1550465694)
* [Vivado で AXI の IP を作ってみる : 雑多な趣味の記録帳](https://tom01h.exblog.jp/27919922/)

* [FPGAの高位合成環境まとめ | Advanced Technology Lab](http://atl.recruit-tech.co.jp/blog/3844/)
* [論理回路の高位合成について - Qiita](https://qiita.com/nekoaddict/items/cddde13a1322e94f44b8)  いろんな処理系の紹介

小野さん(marsee101)のスライド。面白い。勉強になる。
* [2 axi4 バス説明、axi4バスを使用したカスタムipの作成方法](https://www.slideshare.net/marsee101/2-axi4-axi4ip-86461484) AXI4バスの解説。くわしい。
* [Fpgaでの非同期信号の扱い方とvivadoによるサポート（公開用）](https://www.slideshare.net/marsee101/fpgavivado-87684236)
* [FPGAスタートアップ資料](https://www.slideshare.net/marsee101/fpga-92554382)

FPGA開発日記: 興味ぶかい
* [Vivado-HLSで書いた回路とプログラムで速度比較(1) - FPGA開発日記](http://msyksphinz.hatenablog.com/entry/2016/10/04/020000)
* [行列積演算のHLS設計高速化検討(1. サイクル数計測方法の構築) - FPGA開発日記](http://msyksphinz.hatenablog.com/entry/2016/09/12/020346)
* [Vivado-HLSを使って高位合成でCPUを作ってみる(1. メモリのRead/Writeのモデルを作成) - FPGA開発日記](http://msyksphinz.hatenablog.com/entry/2019/02/13/040000) このシリーズは面白そう

ぱたへね!: ここのところMLづいている。いろいろと面白い記事がある。
* [PythonとKerasによるディープラーニング - ぱたへね！](http://natsutan.hatenablog.com/entry/2019/01/05/225800)
* [PythonとKerasによるディープラーニング | マイナビブックス](https://book.mynavi.jp/ec/products/detail/id=90124) Keras作者による本
* [Vivado VIPを使ってAXIマスターを動かしてみる。その1 - ぱたへね！](http://natsutan.hatenablog.com/entry/20171225/1514216998)

* [FPGAにおける計算科学アプリケーションの部分オフローディング](http://www.xcalablemp.org/download/workshop/4th/fujita.pdf)

## Verilog

* [HDLによるFPGA設計](http://zakii.la.coocan.jp/hdl/0_contents.htm) Tipが集められている
* [Verilog-HDL Simulation環境](http://altmo.html.xdomain.jp/src_00/2015_0100/00.html)



## CPU design

* [darklife/darkriscv: opensouce RISC-V implemented from scratch in one night!](https://github.com/darklife/darkriscv)
* [Vivado-HLSを使って高位合成でCPUを作ってみる(1. メモリのRead/Writeのモデルを作成) - FPGA開発日記](http://msyksphinz.hatenablog.com/entry/2019/02/13/040000)
* [Xilinx FPGA向けCortex-M1を合成してみた | わさらぼ](http://wasa-labo.com/wp/?p=460)
* [FPGAでCortex-M1を味見する](https://www.slideshare.net/morilabo/fpgacortexm1)
* [Arm DesignStart Cortex-M1を試す(1. リファレンスデザインを試す) - FPGA開発日記](http://msyksphinz.hatenablog.com/entry/2018/10/11/040000)
* [プロセッサにおけるアウトオブオーダの考え方について(リネームレジスタの例外時の処理について) - FPGA開発日記](http://msyksphinz.hatenablog.com/entry/2016/04/24/030607)
* [シストリックアレイな行列演算器 | わさらぼ](http://wasa-labo.com/wp/?p=401)
* [ゼロから始める自作 CPU 入門](https://www.slideshare.net/hktechno/cpu-2015)
* [FPGAを用いた高性能計算の可能性とデータフロープログラミング](https://www.pccluster.org/ja/event/2017/12/pcccSymp17_sano.pdf)


## FPGA/ML

* [モデルはKerasで書いて、Google ColabでTPUを使いましょう！ ( ソフトウェア ) - @Vengineerの戯言 - Yahoo!ブログ](https://blogs.yahoo.co.jp/verification_engineer/71881982.html)
* [TensorFlowって、Model、いっぱいあるよ ( ソフトウェア ) - @Vengineerの戯言 - Yahoo!ブログ](https://blogs.yahoo.co.jp/verification_engineer/71870253.html)
* [Google ColabでTPUを使ってみる - TadaoYamaokaの日記](http://tadaoyamaoka.hatenablog.com/entry/2019/02/13/002510)
* [Google Colabを導入 - Qiita](https://qiita.com/clocker/items/ebeb5ea9ce216e1d6205)
* [【秒速で無料GPUを使う】TensorFow(Keras)/PyTorch/Chainer環境構築 on Colaboratory - Qiita](https://qiita.com/tomo_makes/items/f70fe48c428d3a61e131)
* [【秒速で無料GPUを使う】深層学習実践Tips on Colaboratory - Qiita](https://qiita.com/tomo_makes/items/b3c60b10f7b25a0a5935)
* [脳死で覚えるkeras入門 - Qiita](https://qiita.com/wataoka/items/5c6766d3e1c674d61425)
* [【無料】4大深層学習フレームワークをGoogle Colaboratoryで使い倒そう【簡単】 - Qiita](https://qiita.com/stakemura/items/1761be70a06fa8ee853f)
* [Tensorflow XLAによる高速化、メモリ効率化、サイズの最適化によるポータビリティ向上について - Qiita](https://qiita.com/GushiSnow/items/a373b8d5d904566f65fd)
* [「ゼロから作るDeep learning」の畳み込みニューラルネットワークのハードウェア化](https://www.slideshare.net/marsee101/deep-learning-80099748)

## ML tutorial

* [TensorFlowのチュートリアルを通して、人工知能の原理について学習する - Qiita](https://qiita.com/jintaka1989/items/3b70b5c5541620536fa2) Good!
* [書籍情報―TensorFlowを使った 「ニューラル・ネットワーク」の構築法](http://www.kohgakusha.co.jp/books/detail/978-4-7775-2058-9) 1つ上を本にしたもの
* [年末のご挨拶と近況、あるいは機械学習のはじめ方 - 怠惰を求めて勤勉に行き着く](http://fushiroyama.hatenablog.com/entry/2018/12/20/054321) Tutorial
* [研究者のための Python による FPGA 入門](https://www.slideshare.net/ryos36/python-fpga-74774921)
