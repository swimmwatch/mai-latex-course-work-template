# mai-latex-course-work-template
This project contains template for common MAI works.

## How to use?
1. Fork this repository
2. Create TeX document
3. Insert this code:
    ```latex
    \documentclass[a4paper,12pt]{article}
    \usepackage{maicoursework}

    \author{Васильев Дмитрий Олегович}
    \MAIWorkTitle{Применение фундаментальных алгоритмов для анализа данных}
    \MAIDate{\today}
    \MAIWorkType{Курсовая работа}
    \MAISubject{Теория графов}

    \begin{document}

    \maketitle

    \tableofcontents

    \clearpage

    \section{First Section}
    This document is an example of \texttt{natbib} package using in bibliography management. Three items are cited: \textit{The \LaTeX\ Companion} book \cite{latexcompanion}, the Einstein journal paper \citet{einstein}, and the Donald Knuth's website \cite{knuthwebsite}. The \LaTeX\ related items are \cite{latexcompanion,knuthwebsite}.

    \clearpage

    \bibliography{sourselist}

    \end{document}
    ```
4. Compile TeX document
5. Enjoy!

## What can you do?
You can create there are table, picture, code listing and use Python within LaTeX document (you need to use pythontex)!

## Input parameters
These parameters are setting in preambule:

| Parameter                | Description                          |
| ------------------------ |:------------------------------------ |
| ```\author```            | Author of document                   |
| ```\MAIInstitute```      | Institute number                     |
| ```\MAIInstituteName```  | Institute title                      |
| ```\MAIDepartment```     | Department number                    |
| ```\MAIDepartmentName``` | Department name                      |
| ```\MAISubject```        | Subject                              |
| ```\MAIWorkTitle```      | Title                                |
| ```\MAIWorkType```       | Course work, course project and etc. |
| ```\MAIProfessorName```  | Professor name                       |
| ```\MAIGroup```          | Group ID                             |
| ```\MAIDate```           | Date of completion                   |