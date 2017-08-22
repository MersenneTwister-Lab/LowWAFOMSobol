R package: Low WAFOM Sequences based on Sobol sequences
===================================================================

Low WAFOM Sequences based on Sobol sequences
are searched using an algorithm described in Shinsuke Mori's
master thesis.

##Information
- version 1.0 on CRAN has bugs, please use version 1.1 or later.
- LowWAFOMSobol 1.0 is now available in CRAN.

##Link
- [Japanese Version](index-ja.html)
- [vignettes](lowWAFOMSobol.html)
- [GitHub Page](https://github.com/MersenneTwister-Lab/LowWAFOMSobol/)
- [This Page](https://mersennetwister-lab.github.io/LowWAFOMSobol/)

##Install
You can install the release packeage from CRAN.

### Install Develop version

- Windows Users need [Rtools](https://cran.r-project.org/bin/windows/Rtools/).
- Mac users need Xcode.

And then,

```
install.packages('devtools')
library('devtools')
install_github("MersenneTwister-Lab/LowWAFOMSobol", ref='develop')
```

##Download

### Release Version:
- Source Package: [LowWAFOMSobol_1.0.tar.gz](LowWAFOMSobol_1.0.tar.gz)
- OS X Binary Package: [LowWAFOMSobol_1.0.tgz](LowWAFOMSobol_1.0.tgz)
- Windows Binary Package: [LowWAFOMSobol_1.0.zip](LowWAFOMSobol_1.0.zip)

### Develop Version:
- Source Package: [LowWAFOMSobol_1.1.1.tar.gz](LowWAFOMSobol_1.1.1.tar.gz)
- OS X Binary Package: [LowWAFOMSobol_1.1.1.tgz](LowWAFOMSobol_1.1.1.tgz)
- Windows Binary Package: [LowWAFOMSobol_1.1.1.zip](LowWAFOMSobol_1.1.1.zip)
- [vignettes](v1_0_1/lowWAFOMSobol.html)

##Reference
* Shinsuke Mori,
  "Suuchi Sekibun no tameno QMC Ten Shuugou no Sekkei, Tansaku,
  oyobi sono Yuukousei",
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