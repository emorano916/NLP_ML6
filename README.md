# NLP_ML6

### Step to process the Safety Data Sheet pdf

1) Create a VE for the project
2) Open the pdf
3) Extract the Raw text from the pdf ; Hint => With Librairies  pyPDF2 package, PDFtoText/Xpdf, pdf2ascii
4) Converting the data to HTML or XLM ? using "pdfminer"  HTML tags might help us to identify specific pieces
5) Extracting identification informations using Regex
6) split the text data into address chunks => Use tags and RE to split the data with Python's finditer 
7) Pull out the easy bits => Product name, adresses,phone number, 
8) 
