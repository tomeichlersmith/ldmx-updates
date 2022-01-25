# UMN-styled slides for LDMX in LaTeX + Beamer

The `makefile` is pretty rudimentary and it assumes you have [texfot](https://ctan.org/pkg/texfot?lang=en) installed.

## main.tex
Starting a new presentation is done by including the preamble tex file before beginning the document.
```tex
\documentclass[aspectratio=169]{beamer}
\input{preamble-update.tex}
\title[Short Subtitle]{Long title only appearing on title slide}
\def\with{List collaborators here}

\begin{document}
\begin{frame}
  \maketitle
\end{frame}
\end{document}
```
