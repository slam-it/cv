# cv

## Export md file to html:
```shell
pandoc --standalone -o cv.html --css cv.css cv.md
```

## Export html file to pdf:
* Open `cv.html` in Firefox 
* Select File -> Print...
* Change the following settings:
  * Paper size -> A4
  * Print headers and footers -> uncheck
  * Print backgrounds -> check

## Export markdown to Word
Just don't use Word. 
pandoc -o resume.docx --reference-docx=resume-docx-reference.docx resume.md


