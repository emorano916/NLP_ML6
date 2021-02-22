# NLP_ML6

### Step to process the Safety Data Sheet pdf

1) Create a VE for the project
2) Open different PFD of the project and list the element that can be extracted => Patterns that always come back.
3) Open the pdf
4) Extract the Raw text from the pdf ; Hint => With Librairies  pyPDF2 package, PDFtoText/Xpdf, pdf2ascii, tika
5) Converting the data to HTML or XLM ? using "pdfminer"  HTML tags might help us to identify specific pieces
6) Extracting identification informations using Regex or **SDSParser 0.2.2** 
7) split the text data into address chunks => Use tags and RE to split the data with Python's finditer 
8) Pull out the easy bits => Product name, adresses,phone number, 
9) Pull out semi-easy bits => ex more difficult adresses to extract
10) Write a program with conditions
11) Convert extractions to dictionnaries
12) Save a Json file

Source
http://zevross.com/blog/2014/04/09/extracting-tabular-data-from-a-pdf-an-example-using-python-and-regular-expressions/
