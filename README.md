# David_Williams_Gaps
David Williams 著 "Probability with martingales" の行間とか復習のメモ。見つけた人はご自由にご利用ください。

# pdfの読み方
1. 緑色のボタンをクリックし、Download Zipをクリック
2. ダウンロードしたフォルダの中にDavid_Williams_Gaps.tex , pis.tex , kawawan.tex があることを確認。
3. David_Williams_Gaps.tex をお手元の環境でコンパイルしてください

# なんで初めからpdf見られるようにしてないの
ごめんなさい。いろいろあったんです。解決策もあるようなので早めに解決したいです。

# お手元にtex環境入ってないですが
Cloud LaTeX https://cloudlatex.io/ などを利用してみてください。
## Cloud LaTeX利用方法一例
会員登録などは済ませてください。

David_Williams_Gaps.tex の
`\begin{document}
  \maketitle
  \begin{abstract}
    タイトル通り。ネットの海からこれを見つけ出した方は参考にしていただけると嬉しい。
    David Williams 著 "Probability with Martingales"。
  \end{abstract}

  \input{pis.tex}

  \input{kawawan.tex}
\end{document}`
の
`
\input{pis.tex}

\input{kawawan.tex}
`
を消去し、
pis.tex , kawawan.tex の内容をすべて David_Williams_Gaps.tex の先ほど消した部分に
コピペしてください。

# 執筆者向け
commitする際はpdfは上げないこと。
作業したファイルだけadd commit push!
