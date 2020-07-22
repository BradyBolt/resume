# resume
Latex Resume and dot graph for college courses.

After installing `sudo apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra`, run:
```
pdflatex ./resume.txt
```
Don't run:
```
pdftex ./resume.txt
```
To make directed graph of college courses (install `xdot` and `eog`):
```
cd ./college_graph
./gen
```
