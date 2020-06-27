# mai-latex-course-work-template
This project contains template for common MAI works.

Main benefits:
1. Template has made in accordance with [GOST](http://www.agni-rt.ru/docs/institute/science/niokr/GOST%207.32-2001.pdf?roistat_visit=3184839). You and your professor don't need to check if course work is valid.
2. All necessary packages are included. There are encoding, table, picture, code listing and [pythontex](https://github.com/gpoore/pythontex)).

## How to use?
1. Fork this repository
2. Create TeX document
3. Insert this code:
    ```latex
    \documentclass[a4paper,12pt]{article}
    \usepackage{maicoursework}

    %%% Преамбула
    \author{Иванов Иван Иванович}
    \MAIWorkTitle{Применение фундаментальных алгоритмов для анализа данных}
    \MAIDate{\today}
    \MAITeacherName{Петров Пётр Петрович}
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
5. [Enjoy](./document.pdf)!

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

## Recommended environment
I prefer to use [VS Code](https://code.visualstudio.com/) with extension [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).
![VS Code Workflow](https://github.com/James-Yu/LaTeX-Workshop/raw/master/demo_media/preview.gif)

Also you can set [build task](https://code.visualstudio.com/docs/editor/tasks#_custom-tasks) that will run ```pythontex```.
![Build PythonTeX](https://i.ibb.co/XV2VgZP/ezgif-com-video-to-gif.gif)