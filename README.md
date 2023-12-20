# 修論・卒論のテンプレート

修論・卒論のテンプレートです。
デフォルトでは卒論になっているため、ソース中のコメントを見て適宜書き換えて下さい。

## 前提

TeXがインストールされていて、きちんと動作すること。

## Usage

本文の書き方やファイル構成、タイプセット（コンパイル）の仕方については ``thesis.pdf`` に書かれています。

## Overleafでの使い方

1. New Project > Upload Projectでzipファイルをアップロードする。
2. Menu > Settings > CompilerでLaTeXを選択する。
3. Recompileする。

以上！

Resumeを作る場合は`resume.tex`を開いた状態でRecompileすればOK。

## 参考文献を手動で編集するには

* bibtexを実行すると生成される`.bbl`ファイルを`ref.tex`などの名前に変更して`\input`で読み込む。
  * `main.tex`でやってるので参照のこと。
* Overleafで`.bib`ファイルを取得するためにはPreviewの「Recompile」の横にあるLogs and output files > Other logs & filesとたどって`bbl`を選択する。

## Copyright, License

Copyright (c) 2015-2020, Shigemi ISHIDA

**DO NOT REDISTRIBUTE THIS PROGRAM NOR A PART OF THIS PROGRAM.**
