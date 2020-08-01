# mai-latex-course-work-template
This project contains template for common MAI works.

Main benefits:
* Template has been made in accordance with [GOST](http://www.agni-rt.ru/docs/institute/science/niokr/GOST%207.32-2001.pdf?roistat_visit=3184839). You and your professor don't need to check if course work is valid.
* All necessary packages are included. There are encoding, table, picture, code listing and [pythontex](https://github.com/gpoore/pythontex).

## How to use?
1. Use this repository as template
2. Compile TeX document
3. [Enjoy](./document.pdf)!

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
| ```\title```             | Title                                |
| ```\MAIWorkType```       | Course work, course project and etc. |
| ```\MAIProfessorName```  | Professor's name                     |
| ```\MAIGroup```          | Group ID                             |
| ```\date```              | Date of completion                   |

## Recommended environment
I prefer using [VS Code](https://code.visualstudio.com/) with extension [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).
![VS Code Workflow](https://github.com/James-Yu/LaTeX-Workshop/raw/master/demo_media/preview.gif)

Also you can set [build task](https://code.visualstudio.com/docs/editor/tasks#_custom-tasks) that will run ```pythontex```.
![Build PythonTeX](https://i.ibb.co/XV2VgZP/ezgif-com-video-to-gif.gif)

## Useful services
* [mathurl](http://mathurl.com) – Easy way to write formulas.
* [Detexify](http://detexify.kirelabs.org/classify.html) – Anyone who works with LaTeX knows how time-consuming it can be to find a symbol in sheet that you just can't memorize. Detexify is an attempt to simplify this search.
* [latexsheet](http://wch.github.io/latexsheet/latexsheet.pdf) – LaTeX sheet.