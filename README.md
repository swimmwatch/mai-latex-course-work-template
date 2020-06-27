# mai-latex-course-work-template
This project contains template for common MAI works.

## How to use?
1. Fork this repository
2. Create TeX document
3. Insert this code:
    ```latex
    \documentclass[a4paper,12pt]{article}
    \usepackage{maicoursework}

    %%% Преамбула
    \author{Васильев Дмитрий Олегович}
    \MAIWorkTitle{Применение фундаментальных алгоритмов для анализа данных}
    \MAIDate{\today}
    \MAITeacherName{Родников Александр Владимирович}
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
You can create there are table, picture, code listing and use Python within LaTeX document (you need to use pythontex)! All necessary packages are included.

## Recommended environment
I prefer to use [VS Code](https://code.visualstudio.com/) with extension [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).
![VS Code Workflow](https://github.com/James-Yu/LaTeX-Workshop/raw/master/demo_media/preview.gif)
Also you can set [build task](https://code.visualstudio.com/docs/editor/tasks#_custom-tasks) that will run ```pythontex```.
![Build pythontex](https://psv4.userapi.com/c856428/u170702424/docs/d9/7a40900ee798/vs_code_task_buid.gif)

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