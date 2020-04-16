
| stable: | [![Build Status](https://travis-ci.com/Qiskit/qiskit-textbook.svg?branch=stable)](https://travis-ci.com/Qiskit/qiskit-textbook) | master: | [![Build Status](https://travis-ci.com/Qiskit/qiskit-textbook.svg?branch=master)](https://travis-ci.com/Qiskit/qiskit-textbook) |
|---|---|---|---|

# Qiskit Textbook Source Code - Japanese version

翻訳の進め方と翻訳担当についてはこちらをご覧ください：[翻訳の進め方.md](https://github.com/kifumi/qiskit-textbook/blob/ja/%E7%BF%BB%E8%A8%B3%E3%81%AE%E9%80%B2%E3%82%81%E6%96%B9.md)

こちらは、オープンソースの[Learn Quantum Computation using Qiskit](http://community.qiskit.org/textbook) テキストブックのレポジトリーです。このテキストブックは、大学の量子アルゴリズムの授業の補足として、また、量子プログラミングに興味のある方が自分で学習するためのガイドとして使用できます。

[`content` folder](content/)フォルダーに、テキストブックの各セクションに対応するJupyterノートブックがあります。 このノートブックのコードは、常に最新バージョンのQiskitに更新される予定です。

ノートブックはhtmlにコンパイルされ、[ウェブサイト](http://community.qiskit.org/textbook)にエクスポートされます。


# Contributors Guide

## General Guidelines 

We love contributions and need them to ensure the textbook is a high-quality resource. If you notice any mistakes and want to fix them, then feel free to go ahead and make a pull request. If you want to contribute original content, there are a few things you can do to make sure your efforts have the biggest impact:

- Please open an issue explaining your proposed additions. Here we can discuss where your contribution will fit in, as well as making sure it fits the style and format of the rest of the textbook.
- Create a pull request while your chapter is in progress, this way we can review it in the process of writing instead of asking for large changes after you have already written it.
- Try to follow the formatting and tone of the existing notebooks to ensure everything renders correctly and the textbook is coherent.

## How to Edit the Textbook

The textbook uses jupyter book to generate the site from jupyter notebooks. To edit the pages you will first need to install jupyter and Qiskit, you can use the links below to help you do this:

- [Install Qiskit](https://qiskit.org/documentation/install.html)
- [Install Jupyter](https://jupyter.org/install)

If you are unfamiliar with git, you can follow this guide to making contributions:

- [Github Desktop Tutorial](https://github.com/firstcontributions/first-contributions/blob/master/github-desktop-tutorial.md)

You will need to fork the textbook, make changes in your own branch, then submit a pull request which we will review before merging. You must use jupyter notebook to edit the pages. If you change any code, please re-run the notebook (you can do this using the ⏭  button at the top of the notebook editor) to update the cell outputs.

**Important:** The notebooks to edit are inside the `content` folder.

## Tags in Qiskit Textbook Notebooks

After writing your chapter, you must a few tags to your cells (You can see the tags using `view > tags`).

- If you include the chapter's title in your notebook, move this to its own cell and add a `remove-cell` tag to avoid duplicate titles on the website. This is only for the title that will appear in the sidebar.
- If you intentionally raise an exception in a cell, add a `raises-exception` tag to that code cell so our checking script knows this is intentional.
- Any code cell that uses IBM hardware, or relies on the results from such a cell needs a `uses-hardware` tag to alert the user this cannot be run on the website through thebe lab.
- Finally, after adding these tags, go to `view > none` and save your notebook to stop the tags from showing automatically when a reader opens the notebook.

For a list of contributors, see the [.bib](https://github.com/Qiskit/qiskit-textbook/blob/master/content/qiskit-textbook.bib) file.

# License
The materials and associated source code of this open-source textbook are licensed under [Apache License 2.0](http://github.com/Qiskit/qiskit-textbook/blob/master/LICENSE.txt).

# Contact
For any issues, please contact Abraham Asfaw (abraham.asfaw@ibm.com).
