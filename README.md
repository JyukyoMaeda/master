# Site-Master

新しいサイトの制作を行う場合、こちらのマスターディレクトリを複製してからWEB開発を行うこと。

# DEMO

・ある程度テンプレート化することで、スピーディーかつ安定したクオリティーのWEB開発を行うことができる。
・ディレクトリ構成は、「各物件名/サイト/scss/style.scss」のようにすること。
・サイト制作を行う際には、必ず「物件名ディレクトリ」からVsCordを開き、SassCompilerを起動してください！

# Features

・ScssにてCssコーディングを行う。

# Requirement

「js/introduction/~」内のファイルの使用に関しては、全て「js/jquery-3.6.3.min.js」を読み込むこと。
* Colorbox 1.6.4　→　「scss/introduction/_colorBox.scss」
* slick-1.8.1　→　「scss/introduction/_slick-theme.scss + _slick.scss」

# Usage

DEMOの実行方法など、"hoge"の基本的な使い方を説明する

```bash
git clone https://github.com/hoge/~
cd examples
python demo.py
```

# Note

Cssコーディングには「Scss」を用いているため、コンパイルできる環境が必須となる。
VsCordの拡張機能である「Live Sass Compiler」の使用をオススメします。
また、仮想サーバーを使用すると、「 Global site tag (gtag.js) - Google Analytics」の影響でエラーが発生してしまうので、面倒ではあるが使用を控え、更新のタイミングでいちいち
「Ctrl + r」でリロード確認をすること。

# Author

* 作成者：前田 龍汰
* 所属　：広報部
* E-mail：maeda-r@jyukyo.com

