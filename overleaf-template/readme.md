# Overleaf Template
We recommend to use Overleaf.com for collaborative latex document editing. 

* To import the template to Overleaf, just create a new project and select 'upload project'
* Select the thesis template .zip file and drag and drop it to overleaf

# Error Handling
If you encounter such an error when compiling the notebook for the first time:
```text
No PDF
This compile didn’t produce a PDF. This can happen if:

• There is an unrecoverable LaTeX error. If there are LaTeX errors shown below or in the raw logs, please try to fix them and compile again.
• The document environment contains no content. If it’s empty, please add some content and compile again.
• This project contains a file called output.pdf. If that file exists, please rename it and compile again.
```
You may need to change your settings like this:

1. Go to `Menu > Compiler` make sure _`pdfLaTeX`_ is selected
2. Go to `Menu > Main Document` make sure _`main.tex`_ is selected