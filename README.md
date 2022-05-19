# Beamer Template for Zhejiang University

## NEW: Use the template on Overleaf

[https://www.overleaf.com/latex/templates/beamer-template-for-zhejiang-university/tyvhsqvfnpnt](https://www.overleaf.com/latex/templates/beamer-template-for-zhejiang-university/tyvhsqvfnpnt)

## Changelog

- 2022.5.18 Fix some issues
- 2020.3.17 Initial commit

## Author

Zhiyuan Pan, Zhejiang University

## Usage

### Set metadata

- Customize your title, author name, institute and date in `frame/cover.tex`. The default date is set to `\today`
- Customize your Table of Contents in `frame/toc.tex`
- Customize your credits & bibliography page in `frame/credits.tex, frame/bib.tex`
- To create frames, use

```tex
\section{...} % appears in toc, bookmarks
\begin{frame} % beamer frame
    \ftitle{...} % appears in the top of the frame
    % Contents start here ...
\end{frame}%
```

### Compile

- General pipeline: XeLaTeX -> XeLaTeX
- If you have external bib file, follow `xe -> bib -> xe -> xe` pipeline
