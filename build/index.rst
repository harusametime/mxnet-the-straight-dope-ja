Deep Learning - The Straight Dope
==================================

このレポジトリでは、Deep Learning、MXNet、Gluonを知るためのノートブックを紹介しています。ノートブックを利用することで、文章、画像、数式、そしてコードを1箇所にまとめて説明することを目的としています。ここでの取り組みがうまくいけば、その成果は書籍、教材、チュートリアルの一部、有用かつ流用可能なコードになると思います。私達の知りうる限りでは、(1) 最新の Deep Learning の幅広いコンセプトと (2) 実行可能なコードを容易に利用できるノートブック、これらの双方を提供するものはいままでありませんでした。この試みを行う特別な理由がいまのところ見つかっていないとしても、いずれ、その理由が見つかると考えています。


このコンテンツのもう一つの独特な側面として執筆プロセスがあります。このリソースは完全にオープンかつフリーで利用することができます。通常、書籍というものは、文体を統一したり、コンテンツを絞り込むために、少数の著者によって執筆されます。ここでは、コミュニティからの貢献を歓迎しており、専門家やコミュニティのメンバーと各章をともに執筆することを望んでいます。例えば、誤字・脱字といった訂正については、多くの協力をみなさんから頂いています。


このレポジトリに貢献したい方へ
=================
Githubの `Deep Learning - The Straight Dope <http://github.com/zackchase/mxnet-the-straight-dope>`_ を見てください！

実行に必要なライブラリ (Dependencies)
============

ここのノートブックを実行するためには最新のMXNetが必要です。``pip``を利用することで最新のMXNetをインストールすることができます。

    $ pip install mxnet --pre --user

さらに詳しい方法については　`here <docs/C01-install.html>`_ をごらんください。


Part 1: Deep Learning の基礎
==================================

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Crash course

   chapter01_crashcourse/preface
   chapter01_crashcourse/introduction
   chapter01_crashcourse/ndarray
   chapter01_crashcourse/linear-algebra
   chapter01_crashcourse/probability
   chapter01_crashcourse/autograd


.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Introduction to supervised learning

   chapter02_supervised-learning/linear-regression-scratch
   chapter02_supervised-learning/linear-regression-gluon
   chapter02_supervised-learning/logistic-regression-gluon
   chapter02_supervised-learning/softmax-regression-scratch
   chapter02_supervised-learning/softmax-regression-gluon
   chapter02_supervised-learning/regularization-scratch
   chapter02_supervised-learning/regularization-gluon
   chapter02_supervised-learning/perceptron
   chapter02_supervised-learning/environment

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Deep neural networks

   chapter03_deep-neural-networks/mlp-scratch
   chapter03_deep-neural-networks/mlp-gluon
   chapter03_deep-neural-networks/mlp-dropout-scratch
   chapter03_deep-neural-networks/mlp-dropout-gluon
   chapter03_deep-neural-networks/plumbing
   chapter03_deep-neural-networks/custom-layer
   chapter03_deep-neural-networks/serialization

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Convolutional neural networks

   chapter04_convolutional-neural-networks/cnn-scratch
   chapter04_convolutional-neural-networks/cnn-gluon
   chapter04_convolutional-neural-networks/deep-cnns-alexnet
   chapter04_convolutional-neural-networks/very-deep-nets-vgg
   chapter04_convolutional-neural-networks/cnn-batch-norm-scratch
   chapter04_convolutional-neural-networks/cnn-batch-norm-gluon

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Recurrent neural networks

   chapter05_recurrent-neural-networks/simple-rnn
   chapter05_recurrent-neural-networks/lstm-scratch
   chapter05_recurrent-neural-networks/gru-scratch
   chapter05_recurrent-neural-networks/rnns-gluon

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Optimization

   chapter06_optimization/optimization-intro
   chapter06_optimization/gd-sgd-scratch
   chapter06_optimization/gd-sgd-gluon
   chapter06_optimization/momentum-scratch
   chapter06_optimization/momentum-gluon
   chapter06_optimization/adagrad-scratch
   chapter06_optimization/adagrad-gluon
   chapter06_optimization/rmsprop-scratch
   chapter06_optimization/rmsprop-gluon
   chapter06_optimization/adadelta-scratch
   chapter06_optimization/adadelta-gluon
   chapter06_optimization/adam-scratch
   chapter06_optimization/adam-gluon

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: High-performance and distributed training

   chapter07_distributed-learning/hybridize
   chapter07_distributed-learning/multiple-gpus-scratch
   chapter07_distributed-learning/multiple-gpus-gluon
   chapter07_distributed-learning/training-with-multiple-machines



Part 2: アプリケーション
====================

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Computer vision

   chapter08_computer-vision/object-detection
   chapter08_computer-vision/fine-tuning
   chapter08_computer-vision/visual-question-answer
.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Natural language processing

   chapter09_natural-language-processing/tree-lstm

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Recommender systems

   chapter11_recommender-systems/intro-recommender-systems

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Time series

   chapter12_time-series/lds-scratch
   chapter12_time-series/issm-scratch

Part 3: 発展
=======================

.. toctree:: Unsupervised Learning
   :glob:
   :maxdepth: 1
   :caption: High-performance and distributed training

   chapter13_unsupervised-learning/vae-gluon

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Generative adversarial networks

   chapter14_generative-adversarial-networks/gan-intro
   chapter14_generative-adversarial-networks/dcgan
   chapter14_generative-adversarial-networks/pixel2pixel


.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Variational methods

   chapter18_variational-methods-and-uncertainty/bayes-by-backprop.ipynb
   chapter18_variational-methods-and-uncertainty/bayes-by-backprop-gluon.ipynb


.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Cheat sheets

   cheatsheets/kaggle-gluon-kfold.ipynb

.. toctree::
   :glob:
   :maxdepth: 1
   :caption: Developer documents

   docs/*
