Simplified PDFLaTeX Compilation
===============================

This simple scripts simplifies compilation of LaTeX files. 
* It deletes un-necessary build files and keeps only `.pdf` and `.log` files along with `.tex`. 
* Also it supresses log output on terminal keeping only content which include errors. 

How to install?
--------------
Just Do
   
    ./pdflatex/install


How to compile LaTeX files?
---------------------------------

To Compile `.tex` file do
    
    TexToPdf filename.tex

To keep all build files do
    
    TexToPdf filename.tex -k

For Help:

    TexToPdf -h

Delete downloaded file
-------------------
Just execute following command again

    ./pdflatex/install
