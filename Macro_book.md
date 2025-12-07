% Options for packages loaded elsewhere
\PassOptionsToPackage{unicode}{hyperref}
\PassOptionsToPackage{hyphens}{url}
\documentclass[
]{article}
\usepackage{xcolor}
\usepackage{amsmath,amssymb}
\setcounter{secnumdepth}{-\maxdimen} % remove section numbering
\usepackage{iftex}
\ifPDFTeX
  \usepackage[T1]{fontenc}
  \usepackage[utf8]{inputenc}
  \usepackage{textcomp} % provide euro and other symbols
\else % if luatex or xetex
  \usepackage{unicode-math} % this also loads fontspec
  \defaultfontfeatures{Scale=MatchLowercase}
  \defaultfontfeatures[\rmfamily]{Ligatures=TeX,Scale=1}
\fi
\usepackage{lmodern}
\ifPDFTeX\else
  % xetex/luatex font selection
\fi
% Use upquote if available, for straight quotes in verbatim environments
\IfFileExists{upquote.sty}{\usepackage{upquote}}{}
\IfFileExists{microtype.sty}{% use microtype if available
  \usepackage[]{microtype}
  \UseMicrotypeSet[protrusion]{basicmath} % disable protrusion for tt fonts
}{}
\makeatletter
\@ifundefined{KOMAClassName}{% if non-KOMA class
  \IfFileExists{parskip.sty}{%
    \usepackage{parskip}
  }{% else
    \setlength{\parindent}{0pt}
    \setlength{\parskip}{6pt plus 2pt minus 1pt}}
}{% if KOMA class
  \KOMAoptions{parskip=half}}
\makeatother
\setlength{\emergencystretch}{3em} % prevent overfull lines
\providecommand{\tightlist}{%
  \setlength{\itemsep}{0pt}\setlength{\parskip}{0pt}}
\usepackage{bookmark}
\IfFileExists{xurl.sty}{\usepackage{xurl}}{} % add URL line breaks if available
\urlstyle{same}
\hypersetup{
  hidelinks,
  pdfcreator={LaTeX via pandoc}}

\author{}
\date{}

\begin{document}

\batchmode
\makeatletter
\def\input@path{{"/Users/rolandclarke/Dropbox/AA Rolands New Files 2020/Lyx_documents/Macroeconomic_book/"}}
\makeatother
\documentclass[11pt,oneside,A4]{book}
\usepackage[utf8]{inputenc}
\setcounter{secnumdepth}{3}
\setcounter{tocdepth}{3}
\usepackage{parskip}
\synctex=-1
\usepackage{amsmath}
\usepackage{geometry}
\geometry{verbose,tmargin=2.5cm,bmargin=2.5cm,lmargin=2.5cm,rmargin=2.5cm}

\makeatletter
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% User specified LaTeX commands.
% dont number subsections
%sets no indents use \noindent for ad hoc indentation RC
\usepackage{tikz}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}

\usepackage{lipsum}%% dummy text package

\usepackage{sectsty}% for centering section titles
%\sectionfont{\centering}  % for centering section titles

\parskip=6pt %sets space between paragraphs

\usepackage{dcolumn}
\usepackage{booktabs}%\usepackage{tabulary}

\usepackage[authordate]{biblatex-chicago}
\bibliography{biblio/biblio} 

\graphicspath{{figures/}} % all figures stored in subdirectory
\usepackage[hang,flushmargin]{footmisc}%stops indents on footnotes Must be placed after {biblatex-chicago} to work

\renewcommand{\labelenumi}{(\alph{enumi})} %sets default list to (a) (b) (c)

%=====================================================================

\makeatother

\usepackage[style=chicago-authordate]{biblatex}
\addbibresource{7_Users_rolandclarke_Dropbox_AA_Rolands_New_Fil____documents_Macroeconomic_book_biblio_biblio.bib}
\begin{document}
\title{Macroeconomics for the 21\textsuperscript{st} Century \\[3ex] }
\author{Roland Clarke\thanks{Roland Clarke is an independent researcher and may be contacted at
rolandclarke97@icloud.com}}

\maketitle
\newpage{}

\tableofcontents{}

\include{8_Users_rolandclarke_Dropbox_AA_Rolands_New_Fil___ts_Macroeconomic_book_Chapters_Introduction}

\include{9_Users_rolandclarke_Dropbox_AA_Rolands_New_Fil___acroeconomic_book_Chapters_Macro_since_1930}

\include{10_Users_rolandclarke_Dropbox_AA_Rolands_New_Fi___s_Macroeconomic_book_Chapters_Current_macro}

\include{11_Users_rolandclarke_Dropbox_AA_Rolands_New_Fi___croeconomic_book_Chapters_Behav_foundations}

\include{12_Users_rolandclarke_Dropbox_AA_Rolands_New_Fi____Macroeconomic_book_Chapters_Interest_rates}

\include{13_Users_rolandclarke_Dropbox_AA_Rolands_New_Fi___s_Macroeconomic_book_Chapters_Fiscal_policy}

\include{14_Users_rolandclarke_Dropbox_AA_Rolands_New_Fi___Macroeconomic_book_Chapters_Monetary_policy}

\label{summaryandconclusions}

\printbibliography

\end{document}

\end{document}
