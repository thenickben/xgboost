# Installation in Anaconda

1. run anaconda prompt as admin
2. look for the right mirror according to the local version of python, with

anaconda search -t conda xgboost
   
In my case it gave the following results:

Using Anaconda API: https://api.anaconda.org
Packages:
     Name                      |  Version | Package Types   | Platforms       | Builds
     ------------------------- |   ------ | --------------- | --------------- | ----------
     Friend/xgboost            |    0.6a2 | conda           | linux-64        | py27_0
     GlaxoSmithKline/r-xgboost |    0.6_0 | conda           | linux-64        | r341h18cf945_0
                                          : Extreme Gradient Boosting, which is an efficient implementation of the gradient boosting framework from Chen & Guestrin (2016) <doi:10.1145/2939672.2939785>. This package is its R interface. The package includes efficient linear  model solver and tree learning algorithms. The package can automatically  do parallel computation on a single machine which could be more than 10  times faster than existing gradient boosting packages. It supports various objective functions, including regression, classification and ranking. The package is made to be extensible, so that users are also allowed to define their own objectives easily.
     JaimeIvanCervantes/xgboost |     0.47 | conda           | linux-64        | py27_0
                                          : Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for Python, R, Java, Scala, C++ and more. Runs on single machine, Hadoop, Spark, Flink and DataFlow
     ODSP-TEST/xgboost         |          | conda           | zos-z           | py36_0
     akode/xgboost             |      0.3 | conda           | osx-64          | py27_0
     anaconda/_py-xgboost-mutex |      2.0 | conda           | linux-64, osx-64, win-64 | cpu_0, gpu_0
     anaconda/_r-xgboost-mutex |      2.0 | conda           | linux-64, osx-64, win-64 | cpu_0, gpu_0
     anaconda/libxgboost       |     0.72 | conda           | linux-64, win-32, win-64, linux-32, osx-64 | hf484d3e_0, hdfa14d8_0, h0a44026_0, h6538335_0, 0, h83be7fe_0, h013b905_0, h1133f5d_0, h8fd8b8a_0, h87a4715_0
     anaconda/py-xgboost       |     0.72 | conda           | linux-64, win-32, win-64, linux-32, osx-64 | py35h6538335_0, py27np112hf8e804c_0, py36np112h982e225_0, py36np112hcd65443_0, py35np112h32b46d2_0, py35np112h14384ea_0, py35h87a4715_0, py35np112h1606666_0, py36h0a44026_0, py35np112h24854b6_0, py36np112h54d5342_0, py36np112hcfb0327_0, py27h0a44026_0, py27h6538335_0, py27np112h0aae3cd_0, py27hc56fc5f_0, py36h87a4715_0, py35h0a44026_0, py35hf484d3e_0, py27hf484d3e_0, py27np112ha102af9_0, py27np112haef2c84_0, py36hf484d3e_0, py36h83be7fe_0, py27h83be7fe_0, py36h6538335_0, py27h87a4715_0, py35h83be7fe_0
     anaconda/py-xgboost-cpu   |     0.72 | conda           | linux-64, win-64, osx-64 | py36_0, py35_0, py27_0
     anaconda/py-xgboost-gpu   |     0.72 | conda           | linux-64        | py35h895cc61_0, py36h895cc61_0, py36hbd78df6_0, py27h895cc61_0, py27hbd78df6_0, py35hbd78df6_0
     anaconda/r-xgboost        |     0.72 | conda           | linux-64, win-64, osx-64 | mro343h9e8cafe_0, mro343h125f7dc_0, r343h8b19950_0, mro343h5bcfacd_0, r343hcdcee97_0, mro343h2d050f9_0, r343hc004794_0, r343h7e9b26e_0, r343h7150583_0
     anaconda/r-xgboost-cpu    |     0.72 | conda           | linux-64, win-64, osx-64 | mro343h9e8cafe_0, r343hc004794_0
     anaconda/r-xgboost-gpu    |     0.72 | conda           | linux-64        | r343h7ba8e84_0, r343h23e6c04_0, mro343h8e6da59_0, mro343h872fb70_0
     aterrel/xgboost           | 0.4.0.c4fa2f | conda           | linux-64, osx-64 | np19py27_0, py27_0
                                          : An optimized general purpose gradient boosting library.
     avengers/xgboost          |   0.4a30 | conda           | linux-64        | py27h39ecc38_0
                                          : XGBoost Python Package
     bioconda/xgboost          |    0.6a2 | conda           | linux-64        | py34_0
     brittainhard/r-xgboost    |    0.6_0 | conda           | linux-64        | r341h18cf945_0, py35r34h9a77854_0
                                          : Extreme Gradient Boosting, which is an efficient implementation of the gradient boosting framework from Chen & Guestrin (2016) <doi:10.1145/2939672.2939785>. This package is its R interface. The package includes efficient linear  model solver and tree learning algorithms. The package can automatically  do parallel computation on a single machine which could be more than 10  times faster than existing gradient boosting packages. It supports various objective functions, including regression, classification and ranking. The package is made to be extensible, so that users are also allowed to define their own objectives easily.
     brown-data-science/r-xgboost |    0.6_4 | conda           | linux-64        | r3.3.2_0
     brown-data-science/xgboost |     0.60 | conda           | linux-64        | np111py27_0, py27h6bb024c_0, np113py27_0
     conda-forge/dask-xgboost  |    0.1.5 | conda           | linux-64, win-32, win-64, noarch, osx-64 | py_0, py36_0, py35_0, py27_0
                                          : Launch, train, and test with XGBoost from Dask
     conda-forge/xgboost       |   0.72.1 | conda           | linux-64, osx-64 | py27_2, py27_1, py27_0, py36_1, py36_0, py36_2, py36hfc679d8_1, py35hfc679d8_1, py27hfc679d8_1, py35_2, py35_0, py35_1
                                          : Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for
Python, R, Java, Scala, C++ and more. Runs on single machine, Hadoop, Spark, Flink
and DataFlow

     creditx/xgboost           |     0.64 | conda           | linux-64        | py35_1, py27_1, py35_0, py27_0
     derickl/xgboost           |     0.71 | conda           | osx-64          | py27h90ec04b_0, py27_0
                                          : Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for
Python, R, Java, Scala, C++ and more. Runs on single machine, Hadoop, Spark, Flink
and DataFlow

     diegslva/xgboost          |      0.6 | conda           | linux-64        | py27_6
     dmanglam/r-xgboost        |    0.6_4 | conda           | osx-64          | r34hbf94c42_0
                                          : Extreme Gradient Boosting, which is an efficient implementation of the gradient boosting framework from Chen & Guestrin (2016) <doi:10.1145/2939672.2939785>. This package is its R interface. The package includes efficient linear  model solver and tree learning algorithms. The package can automatically  do parallel computation on a single machine which could be more than 10  times faster than existing gradient boosting packages. It supports various objective functions, including regression, classification and ranking. The package is made to be extensible, so that users are also allowed to define their own objectives easily.
     enneamer/xgboost          |     0.60 | conda           | linux-64        | py35_0, py27_0
     floriangeigl/xgboost      |   0.4a30 | conda           | linux-64        | py27_1, py27_0
                                          : XGBoost Python Package
======================

|PyPI version| |PyPI downloads|

Installation
------------

We are on `PyPI <https://pypi.python.org/pypi/xgboost>`__ now. For
stable version, please install using pip:

-  ``pip install xgboost``
-  Note for windows users: this pip installation may not work on some
   windows environment, and it may cause unexpected errors. pip
   installation on windows is currently disabled for further
   invesigation, please install from github.

For up-to-date version, please install from github.

-  To make the python module, type ``./build.sh`` in the root directory
   of project
-  Make sure you have
   `setuptools <https://pypi.python.org/pypi/setuptools>`__
-  Install with ``python setup.py install`` from this directory.
-  For windows users, please use the Visual Studio project file under
   `windows folder <../windows/>`__. See also the `installation
   tutorial <https://www.kaggle.com/c/otto-group-product-classification-challenge/forums/t/13043/run-xgboost-from-windows-and-python>`__
   from Kaggle Otto Forum.

Examples
--------

-  Refer also to the walk through example in `demo
   folder <../demo/guide-python>`__
-  See also the `example scripts <../demo/kaggle-higgs>`__ for Kaggle
   Higgs Challenge, including `speedtest
   script <../demo/kaggle-higgs/speedtest.py>`__ on this dataset.

Note
----

-  If you want to build xgboost on Mac OS X with multiprocessing support
   where clang in XCode by default doesn't support, please install gcc
   4.9 or higher using `homebrew <http://brew.sh/>`__
   ``brew tap homebrew/versions; brew install gcc49``
-  If you want to run XGBoost process in parallel using the fork backend
   for joblib/multiprocessing, you must build XGBoost without support
   for OpenMP by ``make no_omp=1``. Otherwise, use the forkserver (in
   Python 3.4) or spawn backend. See the
   `sklearn\_parallel.py <../demo/guide-python/sklearn_parallel.py>`__
   demo.

.. |PyPI version| image:: https://badge.fury.io/py/xgboost.svg
   :target: http://badge.fury.io/py/xgboost
.. |PyPI downloads| image:: https://img.shields.io/pypi/dm/xgboost.svg
   :target: https://pypi.python.org/pypi/xgboost/

     hcarvalhoalves/xgboost    |     0.47 | conda           | osx-64          | py27_0
                                          : Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for Python, R, Java, Scala, C++ and more. Runs on single machine, Hadoop, Spark, Flink and DataFlow
     hivmmer/xgboost           |      0.7 | conda           | linux-64        | py36h6bb024c_0
                                          : eXtreme Gradient Boosting
     intel/xgboost             |      0.7 | conda           | linux-64        | py36_0, py27_0
                                          : Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for
Python, R, Java, Scala, C++ and more. Runs on single machine, Hadoop, Spark, Flink
and DataFlow

     jjhelmus/_py-xgboost-mutex |      2.0 | conda           | linux-64, win-64 | cpu_0, gpu_0
     jjhelmus/_r-xgboost-mutex |      2.0 | conda           | linux-64, win-64 | cpu_0, gpu_0
     jjhelmus/libxgboost       |     0.72 | conda           | linux-64, win-64 | hf484d3e_0, ha7adb77_0, h87a4715_0, h83be7fe_0
     jjhelmus/py-xgboost       |     0.72 | conda           | linux-64, win-64 | py36hf484d3e_0, py35h87a4715_0, py36h87a4715_0, py36h83be7fe_0, py27h83be7fe_0, py35hf484d3e_0, py27hf484d3e_0, py36ha7adb77_0, py27h87a4715_0, py35ha7adb77_0, py35h83be7fe_0
     jjhelmus/py-xgboost-cpu   |     0.72 | conda           | linux-64        | py36_0, py35_0, py27_0
     jjhelmus/py-xgboost-gpu   |     0.72 | conda           | linux-64, win-64 | py35h895cc61_0, py36h895cc61_0, py36hbd78df6_0, py27h895cc61_0, py27hbd78df6_0, py35hbd78df6_0
     jjhelmus/r-xgboost        |     0.72 | conda           | linux-64, win-64 | mro343h5bcfacd_0, mro343h125f7dc_0, mro343h2d050f9_0, r343h8b19950_0, r343hcdcee97_0, mro343h6f6328c_0, r343h7e9b26e_0, r343h379c258_0
     jjhelmus/r-xgboost-cpu    |     0.72 | conda           | linux-64        | mro343h9e8cafe_0, r343hc004794_0
     jjhelmus/r-xgboost-gpu    |     0.72 | conda           | linux-64, win-64 | r343h7ba8e84_0, r343h23e6c04_0, mro343h8e6da59_0, mro343h872fb70_0
     kite-eating-tree/r-xgboost |     0.60 | conda           | linux-64        | r332h3717fef_0
                                          : eXtreme Gradient Boosting
     matthewparentoracle/r-xgboost |    0.4_2 | conda           | linux-64        | r3.2.2_0
                                          : Extreme Gradient Boosting, which is an  efficient implementation of gradient boosting framework.  This package is its R interface. The package includes efficient  linear model solver and tree learning algorithms. The package can automatically  do parallel computation on a single machine which could be more than 10 times faster than existing gradient boosting packages. It supports various objective functions, including regression, classification and ranking. The package is made to be extensible, so that users are also allowed to define their own objectives easily.
     mikesilva/xgboost         |    0.6a2 | conda           | linux-64, win-64 | py36_0
                                          : XGBoost Python Package
     mndrake/xgboost           |      0.6 | conda           | win-64          | py27_0
     moutai/xgboost            |     0.60 | conda           | linux-64        | py27_0
     msarahan/libxgboost       |     0.60 | conda           | osx-64          | h76f0375_0, hd2b34af_0, h15e06e5_0, hde90d9e_0, h3c80cd1_0
     msarahan/py-xgboost       |     0.60 | conda           | osx-64          | py27h5d9ed17_0, py35hb86cbc6_0, py36h8a48ca5_0, py34hce7f44b_0, py35h19e95da_0, py27hc351098_0, py36h87d2a76_0, py34hac259ef_0
     msarahan/r-xgboost        |     0.60 | conda           | osx-64          | r332he0ba5fb_0, r332h813f73e_0, r332h75bb6d3_0, r332h3c525f2_0, r332hbf643ed_0
     mwojcikowski/xgboost      |    v0.60 | conda           | linux-64        | py35_0, py27_0
     nnsrl/r-xgboost           |   0.71.2 | conda           | linux-64        | r350h29659fb_0
                                          : Extreme Gradient Boosting, which is an efficient implementation of the gradient boosting framework from Chen & Guestrin (2016) <doi:10.1145/2939672.2939785>. This package is its R interface. The package includes efficient linear  model solver and tree learning algorithms. The package can automatically  do parallel computation on a single machine which could be more than 10  times faster than existing gradient boosting packages. It supports various objective functions, including regression, classification and ranking. The package is made to be extensible, so that users are also allowed to define their own objectives easily.
     nubank/xgboost            |     0.47 | conda           | linux-64        | py27_0
     pmarelas/xgboost          |      0.4 | conda           | linux-64        | py35_0
                                          : An optimized general purpose gradient boosting library.
     pstey/r-xgboost           |    0.6_4 | conda           | linux-64        | r3.3.2_0
     r/_r-xgboost-mutex        |      2.0 | conda           | linux-64, osx-64, win-64 | cpu_0, gpu_0
     r/r-xgboost               |     0.72 | conda           | linux-64, win-32, win-64, linux-32, osx-64 | r332h8f6dcb1_0, mro343h5bcfacd_0, mro343h125f7dc_0, r332hf1cf349_0, r343h8b19950_0, r343hcdcee97_0, r343hc004794_0, r332hac3f3dd_0, r332h3717fef_0, mro343h2d050f9_0, r343h7e9b26e_0, mro343hb8b1496_0, mro343h9e8cafe_0, r343h7150583_0, r343h22c98a9_0
     r/r-xgboost-cpu           |     0.72 | conda           | linux-64, osx-64, win-64 | mro343h9e8cafe_0, r343hc004794_0
     r/r-xgboost-gpu           |     0.72 | conda           | linux-64        | r343h7ba8e84_0, r343h23e6c04_0, mro343h8e6da59_0, mro343h872fb70_0
     rdonnelly/libxgboost      |     0.60 | conda           | linux-64, osx-64, win-64 | hf484d3e_0, h0a44026_0, h801199c_0, h6538335_0
     rdonnelly/py-xgboost      |     0.60 | conda           | linux-64, osx-64, win-64 | py36h6538335_0, py36hf484d3e_0, py36h0a44026_0, py36h8e410d0_0, py27h58d39dc_0, py35hf484d3e_0, py27hf484d3e_0, py35h0a44026_0, py35h6538335_0, py27h0a44026_0, py35he55ec6b_0, py27h6538335_0
     rdonnelly/r-xgboost       |      0.7 | conda           | linux-64, osx-64, win-64 | r343hcdcee97_0, r343h7150583_0, r343h22c98a9_0, mro343h125f7dc_0, mro343hb8b1496_0
     riipl-org/xgboost         |      0.7 | conda           | linux-64        | py36h6bb024c_1
                                          : eXtreme Gradient Boosting
     sm4258a/r-xgboost         |   0.71.2 | conda           | win-64          | r343_0
                                          : Extreme Gradient Boosting, which is an efficient implementation of the gradient boosting framework from Chen & Guestrin (2016) <doi:10.1145/2939672.2939785>. This package is its R interface. The package includes efficient linear  model solver and tree learning algorithms. The package can automatically  do parallel computation on a single machine which could be more than 10  times faster than existing gradient boosting packages. It supports various objective functions, including regression, classification and ranking. The package is made to be extensible, so that users are also allowed to define their own objectives easily.
     softwaremechanic/xgboost  |    0.6a2 | conda           | linux-64        | py35_0
     upstart/xgboost           |      0.6 | conda           | linux-64        | py36_0, py36he1ec16c_0, py36hcd415c4_0
                                          : Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for
Python, R, Java, Scala, C++ and more. Runs on single machine, Hadoop, Spark, Flink
and DataFlow

     veltin/xgboost            |      dev | conda           | linux-64        | py27_3
     wenlong/r-xgboost         |    0.4_4 | conda           | linux-64        | r3.2.2_0
     wvlammeren/r-xgboost      |    0.6_4 | conda           | linux-64        | r3.3.2_0
Found 67 packages

So I know I have to use for example "mikesilva" for my python 3.6.

3. Run on prompt:
  conda install -c mikesilva xgboost
