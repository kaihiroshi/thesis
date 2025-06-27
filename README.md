# はじめに

卒論／修論用のスタイルファイルです。以下の3つのファイルがあります。

> sample.tex：サンプルTeXファイル

> golfer.eps：サンプルTeXファイルで使われる図(Ghostscriptのサンプルファイルから)

> thesis.cls：卒論／修論用のスタイルファイル

# コンパイルの仕方

(1) DVIファイルの作成
3つのファイルを同じディレクトリに置いて、以下のように2回platexを実行します。
1回目でおおまかな文書を作成し、2回目で参考文献番号や目次が作成されます。

> platex sample.tex

> platex sample.tex

(2) PDFファイルの作成

> dvipdfmx sample.dvi

# 注意

graphicx.sty, amsmath.sty, amssymb.sty, enumerate.styは既に読み込んでいますので新たに指定する必要はありません。

そのほかスタイルファイルが必要であれば usepackage してください。
