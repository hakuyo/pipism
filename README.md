
Markdownという記法でHTMLを記述し、「.md」「.markdown」みたいにそれっぽい拡張子をつけてREADMEファイルを　　
作ってやれば、リポジトリページのトップの下の方にgithubの便利機能で、READMEファイルの中身が自動的に　　
ように表示されるようになってます。


見出し（h1〜h6）

# This is an H1

## This is an H2

###### This is an H6

段落（p）
空白行に囲まれた複数行の文章(一行の場合も含む)がまとめて一つの段落として扱われます。  
スペースやタブだけの行も空白行に含まれます。) 通常段落の行頭にスペースやタブがあってはいけません。

改行（br）
その行の末尾を二つ以上のスペースを記述してから改行する。
引用（blockqute）

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

リスト（ul li）

*   Red
*   Green
*   Blue

番号付きリスト（ol li）

1.  Bird
2.  McHale
3.  Parish

ソースコードを表現（pre code）
単純に各行の冒頭に4つ以上のスペースもしくは1つ以上のタブを挿入。

    This is a code block.
	
リンク（a）

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.