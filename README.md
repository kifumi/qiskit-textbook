
| stable: | [![Build Status](https://travis-ci.com/qiskit-community/qiskit-textbook.svg?branch=stable)](https://travis-ci.com/qiskit-community/qiskit-textbook) | master: | [![Build Status](https://travis-ci.com/qiskit-community/qiskit-textbook.svg?branch=master)](https://travis-ci.com/qiskit-community/qiskit-textbook) |
|---|---|---|---|

# Qiskit Textbook Source Code - Japanese version

翻訳の進め方と翻訳担当についてはこちらをご覧ください：[翻訳の進め方.md](https://github.com/kifumi/qiskit-textbook/blob/ja/%E7%BF%BB%E8%A8%B3%E3%81%AE%E9%80%B2%E3%82%81%E6%96%B9.md)

こちらは、オープンソースの[Learn Quantum Computation using Qiskit](http://community.qiskit.org/textbook) テキストブックのレポジトリーです。このテキストブックは、大学の量子アルゴリズムの授業の補足として、また、量子プログラミングに興味のある方が自分で学習するためのガイドとして使用できます。

[`content` folder](content/)フォルダーに、テキストブックの各セクションに対応するJupyterノートブックがあります。 このノートブックのコードは、常に最新バージョンのQiskitに更新される予定です。

ノートブックはhtmlにコンパイルされ、[ウェブサイト](http://community.qiskit.org/textbook)にエクスポートされます。


## Installing the `qiskit_textbook` Package

The Qiskit Textbook provides some tools and widgets specific to the Textbook. This is not part of Qiskit and is available through the `qiskit_textbook` package. The quickest way to install this with [Pip](https://pypi.org/project/pip/) and [Git](https://git-scm.com/) is through the command:

```pip install git+https://github.com/qiskit-community/qiskit-textbook.git#subdirectory=qiskit-textbook-src```

Alternatively, you can download the folder [`qiskit-textbook-src`](qiskit-textbook-src) and run:

```pip install ./qiskit-textbook-src``` 

from the directory that contains this folder.

# License
The materials and associated source code of this open-source textbook are licensed under [Apache License 2.0](http://github.com/qiskit-community/qiskit-textbook/blob/master/LICENSE.txt).

# Contact
For any issues, please contact Francis Harkins (francis.harkins@ibm.com) and Abraham Asfaw (abraham.asfaw@ibm.com).
