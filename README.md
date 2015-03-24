## これは？

python2.7jaのdash用 docsetです。

## 使い方

~~~ bash
% git clone https://github.com/umiyosh/py2.7jaDocset.git
% cd py2.7jaDocset ;open Python2.7ja.docset
~~~

pyja: で検索できます。

## このdocsetの作成手順

~~~ bash
% sudo pip install doc2dash
% wget https://python-doc-ja.googlecode.com/files/python-doc-2.7ja1-html.tar.gz
% tar xvzf python-doc-2.7ja1-html.tar.gz
% doc2dash -n Python2.7ja -i ./python-doc-2.7ja1-html/_static/py.png -I index.html -d ./output ./python-doc-2.7ja1-html
~~~

## 著作権・ライセンスについて

このdocsetは [python-doc-ja - Pythonドキュメント日本語翻訳プロジェクト ](https://code.google.com/p/python-doc-ja/) で翻訳されたドキュメントを使用してdocsetにまとめたものです。
このPythonドキュメント翻訳プロジェクトの成果物は、底本の著作権およびライセンスによる制限のない限り、翻訳著作権はこれを Python ドキュメント翻訳プロジェクト(責任者: 稲田、増田、川西)に帰属し、Python と同じ Python Software Foundation(PSF) ライセンスの下に公開するものとします。

