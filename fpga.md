# FPGA

## Zynq(Xilinx)

* [Vivado Design Suite](https://japan.xilinx.com/products/design-tools/vivado.html?resultsTablePreSelect=documenttype:User%20Guides#documentation) Xilnx公式ドキュメント集
* [Zynq-7000 SoC - 性能およびアクセラレーション](https://japan.xilinx.com/support/documentation-navigation/design-hubs/dh0054-zynq-7000-performance-and-benchmarks-hub.html)
* [Zynq およびコプロセッサを使用したシステム パフォーマンスの向上 (日本語吹替)](https://japan.xilinx.com/video/soc/accelerating-system-performance-zynq.html) Zynq内蔵のCortex-A9にACP経由でコプロセッサを付ける
* [Zynq-7000 SoC - データ ムーバー](https://japan.xilinx.com/support/documentation-navigation/design-hubs/dh0051-zynq-7000-data-movement-hub.html) データの高速な移動について
* [Vivado HLS で設計する浮動小数点行列乗算の Zynq アクセラレータ](https://japan.xilinx.com/support/documentation/application_notes/j_xapp1170-zynq-hls.pdf) HLSのチュートリアル。やってみる。

## Zynq

* [Zynq + Vivado HLS入門](https://www.slideshare.net/narusugimoto/zynq-vivado-hls)
* [ソフト屋がXilinx zynq-7000をさわってみた ～体験記～](http://openit.kek.jp/workshop/2016/nifs/presentation/sendai-zynq.pdf)
* [Vivado HLS で設計する浮動小数点行列乗算の Zynq アクセラレータ](https://japan.xilinx.com/support/documentation/application_notes/j_xapp1170-zynq-hls.pdf) チュートリアル
* [FPGAでの割り算は怖くない: なひたふJTAG日記](http://nahitafu.cocolog-nifty.com/nahitafu/2013/01/fpga-64ef.html) Core Generatorで除算回路を生成する話
* [Training to use Zynq on ZYBO](http://www.ritsumei.ac.jp/se/re/izumilab/dist/axi2axis/) 立命館大学の演習ページ
* [XILINX 7 シリーズにおけるMMCM周波数の動的変更: なひたふJTAG日記](http://nahitafu.cocolog-nifty.com/nahitafu/2014/03/xilinx-7-mmcm-1.html)
* [ZYNQのFSBLが動かない場合の対処法: なひたふJTAG日記](http://nahitafu.cocolog-nifty.com/nahitafu/2014/08/zynqfsbl-5f71.html)
* [ZYNQではバイパスコンデンサが不要なのか？: なひたふJTAG日記](http://nahitafu.cocolog-nifty.com/nahitafu/2014/04/zynq-8852.html)

### ZynqでPLのみの回路をSD化する

* [■PL部のみでLチカしたプロジェクトをSDブート化する - gogo fpga](http://gogofpga.blog.fc2.com/blog-entry-86.html)
* [Solved: How to make bootable SD card for Zynq 7000 series ... - Community Forums](https://forums.xilinx.com/t5/7-Series-FPGAs/How-to-make-bootable-SD-card-for-Zynq-7000-series-PL-only/td-p/876083)
* [Solved: PL 'only' Zynq - Community Forums](https://forums.xilinx.com/t5/Embedded-Boot-and-Configuration/PL-only-Zynq/td-p/381199)

## ZYBO/FPGA関連のリンク集

* [Getting the PmodOLEDrgb to Work on Zybo: 10 Steps](https://www.instructables.com/id/Getting-the-PmodGPS-to-Work-on-Zybo/?_ga=2.25723837.1221445310.1551239693-1015329430.1550465694)
* [Vivado で AXI の IP を作ってみる : 雑多な趣味の記録帳](https://tom01h.exblog.jp/27919922/)
* [FPGAリテラシーおよびチュートリアル](http://marsee101.web.fc2.com/fpga_literacy_tutorial.html)
* [FPGA(Zynq) 評価基板を使う(Zybo Z7編) - Qiita](https://qiita.com/ryos36/items/16816e19f2b8b1dbca31)
* [High-Speed Real-Time Video Streaming Transmission - Hackster.io](https://www.hackster.io/DigilentContestTeam/high-speed-real-time-video-streaming-transmission-844481)  GigE Vision camera bridge prototype using the Zybo Z7-10 board with a Digilent Pcam 5C camera connected to it.

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
* [乗算・除算器 : 雑多な趣味の記録帳](https://tom01h.exblog.jp/27418544/) v-scaleというV-RISC実装をいじるシリーズ。参考になる
* [kozos on V-scale chip on ARTY : 雑多な趣味の記録帳](https://tom01h.exblog.jp/27321632/)
* [Inspiron11 購入 ＆ FPGA 環境セットアップ : 雑多な趣味の記録帳](https://tom01h.exblog.jp/27371838/) VivadoをBash on Windows環境にインストールする話。

ぱたへね!: ここのところMLづいている。いろいろと面白い記事がある。
* [PythonとKerasによるディープラーニング - ぱたへね！](http://natsutan.hatenablog.com/entry/2019/01/05/225800)
* [PythonとKerasによるディープラーニング | マイナビブックス](https://book.mynavi.jp/ec/products/detail/id=90124) Keras作者による本
* [Vivado VIPを使ってAXIマスターを動かしてみる。その1 - ぱたへね！](http://natsutan.hatenablog.com/entry/20171225/1514216998)

* [FPGAにおける計算科学アプリケーションの部分オフローディング](http://www.xcalablemp.org/download/workshop/4th/fujita.pdf)
* [AvnetのUltra96を買ってみた - ハードウェアの気になるあれこれ](https://www.tech-diningyo.info/entry/2018/12/24/154145)

## Verilog

* [HDLによるFPGA設計](http://zakii.la.coocan.jp/hdl/0_contents.htm) Tipが集められている
* [Verilog-HDL Simulation環境](http://altmo.html.xdomain.jp/src_00/2015_0100/00.html)
* [100 Power Tips for FPGA Designers - ぱたへね！](http://natsutan.hatenablog.com/entry/20120808/1344381574)


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
* [Arty+VivadoでMicroBlazeとRISC-Vを動かしてみた – 楽しくやろう。](https://blog.boochow.com/article/arty-risc-v.html)

* [RISC-V ISAの基本構造](https://notes.muo.jp/1707_riscv-arch.html)
* [RISC-V Foundationを中心とするアーキテクチャ管理体制](https://notes.muo.jp/1707_riscv-foundation.html)

FPGA開発日記のブログは、とても勉強になる。いろいろなCPU関連の技術・実装について調べている。
* [APSで連載しているRISC-V入門全8回がすべて公開されました - FPGA開発日記](http://msyksphinz.hatenablog.com/entry/2018/10/17/040000) 
* [2018年のRISC-V関係の(私の)講演資料をすべて公開しました - FPGA開発日記](http://msyksphinz.hatenablog.com/entry/2018/11/15/040000)
* [ますます注目されるオープンCPUアーキテクチャRISC-Vの最新動向 - Speaker Deck](https://speakerdeck.com/msyksphinz/masumasuzhu-mu-sareruopuncpuakitekutiyarisc-vfalsezui-xin-dong-xiang) さまざまなRISC-Vの実装を紹介。必読

* [f32c/f32c: A 32-bit RISC-V / MIPS ISA retargetable CPU core & SoC, 1.63 DMIPS/MHz](https://github.com/f32c/f32c)  A 32-bit RISC-V / MIPS ISA retargetable CPU core & SoC, 1.63 DMIPS/MHz

* [VerilogでCPU設計入門](http://japanese.sugawara-systems.com/opencores/VPI/cpu.htm) CPUを自作する話。力作

## Mathematic

* [FPGA用にシンプルな浮動小数点数演算器を作る - Qiita](https://qiita.com/tvrcw/items/e20b26eafba365056916)



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
* [画像処理100本ノックを作ったった - Qiita](https://qiita.com/yoyoyo_/items/2ef53f47f87dcf5d1e14)
* [yoyoyo-yo/Gasyori100knock: 画像処理100本ノックして画像処理を画像処理して画像処理するためのもの For Japanese, English and Chinese](https://github.com/yoyoyo-yo/Gasyori100knock)
* [ディープラーニング∞本ノック作ったった - Qiita](https://qiita.com/yoyoyo_/items/cd5b859341106c3b52f9)
* [yoyoyo-yo/DeepLearningMugenKnock: でぃーぷらーにんぐを無限にやってディープラーニングでディープラニングするためのもの](https://github.com/yoyoyo-yo/DeepLearningMugenKnock)
* [Zynq MPSoc Book – With PNYQ and Machine Learning Applications](https://www.zynq-mpsoc-book.com/)

## 画像処理

* [Zybo＋PetalinuxでUVCカメラを使う - how to code something](http://d.hatena.ne.jp/seinzumtode/20171120/1511167136)
* [OpenCVで外接矩形と回転角の算出 - how to code something](http://d.hatena.ne.jp/seinzumtode/20171121/1511241157)
* [zybo上での画像処理関連 - how to code something](http://d.hatena.ne.jp/seinzumtode/20171121/1511247282)
* [High-Speed Real-Time Video Streaming Transmission - Hackster.io](https://www.hackster.io/DigilentContestTeam/high-speed-real-time-video-streaming-transmission-844481)

## PetaLinux

* [ZYBO-Z7を用いたLチカ(Petalinux編) - aster_ismの工作室](http://aster-ism.hatenablog.com/entry/2017/10/21/150717)

## 書籍・雑誌

「FPGAキットで始める ハード&ソフト丸ごと設計」

* [FPGAキットで始めるハード&ソフト丸ごと設計 - kuriken12の日記](http://d.hatena.ne.jp/kuriken12/20130430/1367315308) 著者による紹介記事
* [FPGAキットで始めるハード&ソフト丸ごと設計 - ぱたへね！](http://natsutan.hatenablog.com/entry/20130506/1367829777)
* [PDFのサンプル CQ出版](http://www.cqpub.co.jp/hanbai/books/46/46101/46101.pdf)


「実用HDLサンプル記述集」

* [実用HDLサンプル記述集【PDF版＋サンプル・ファイル】 ](https://cc.cqpub.co.jp/lib/system/doclib_item/1088/)
