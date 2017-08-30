R package: Sobol sequence に基づくLow WAFOM Sequence
==================================================

森信輔による修士論文「数値積分のためのQMC点集合の設計,探索およびその有効性」において
述べられた方法で探索された「Sobol sequence に基づくLow WAFOM Sequence」を
Rに移植したもの。

##お知らせ
- バグ修正版バージョン1.1.1がCRANに登録されました。
- このパッケージはCRANに登録されました。

##リンク

- [英語版](index.html)
- [ビニエット](lowWAFOMSobol-ja.html)
- [GitHub Page](https://github.com/MersenneTwister-Lab/LowWAFOMSobol/)
- [このページ](https://mersennetwister-lab.github.io/LowWAFOMSobol/)

##インストール
リリース版はCRANからインストールできます。

### 開発版のインストール
まず、

- Windows利用者は[Rtools](https://cran.r-project.org/bin/windows/Rtools/)を
インストールしておく必要がある。
- Mac 利用者はXcodeをインストールしておく必要があるかもしれない。

その後、以下のようにしてこのパッケージをRにインストールすることができる。

```
install.packages('devtools')
library('devtools')
install_github('MersenneTwister-Lab/LowWAFOMSobol', ref='develop')
```


##ダウンロード
###リリース版

- Source Package: [LowWAFOMSobol_1.1.1.tar.gz](LowWAFOMSobol_1.1.1.tar.gz)
- OS X Binary Package: [LowWAFOMSobol_1.1.1.tgz](LowWAFOMSobol_1.1.1.tgz)
- Windows Binary Package: [LowWAFOMSobol_1.1.1.zip](LowWAFOMSobol_1.1.1.zip)

###開発版

現在、開発版とリリース版は一致しています。

- Source Package: [LowWAFOMSobol_1.1.1.tar.gz](LowWAFOMSobol_1.1.1.tar.gz)
- OS X Binary Package: [LowWAFOMSobol_1.1.1.tgz](LowWAFOMSobol_1.1.1.tgz)
- Windows Binary Package: [LowWAFOMSobol_1.1.1.zip](LowWAFOMSobol_1.1.1.zip)
- [vignettes](v1_0_1/lowWAFOMSobol-ja.html)

##参照
* 森 信輔,
  "数値積分のための QMC 点集合の設計, 探索およびその有効性",
  Master's Thesis, 2017.
* Ryuichi Ohori,
  "Efficient Quasi Monte Carlo Integration by Adjusting the
  Derivation-sensitivity Parameter of Walsh Figure of Merit",
  Master's Thesis, 2015.
* S. Harase and R. Ohori,
  "A search for extensible low-WAFOM point sets",
  arXiv preprint, arXiv:1309.7828, (2013),
  https://arxiv.org/abs/1309.7828.
* Harase, S. (2016).
  "A search for extensible low-WAFOM point sets",
  Monte Carlo Methods and Applications, 22(4), pp. 349-357, 2017.
  [doi:10.1515/mcma-2016-0119](doi:10.1515/mcma-2016-0119)
* M. Matsumoto and R. Ohori,
  "Walsh Figure of Merit for Digital Nets: An Easy Measure
  for Higher Order Convergent QMC",
  Springer International Publishing, Cham, 2016, pp. 143-160.
* M. Matsumoto, M. Saito, and K. Matoba,
  "A computable figure of merit for quasi-Monte Carlo point sets",
  Mathematics of Computation, 83 (2014), pp. 1233-1250.
* S. Joe and F. Y. Kuo,
  "Constructing Sobol sequences with better two-dimensional projections",
  SIAM J. Sci. Comput. 30, 2635-2654 (2008).
