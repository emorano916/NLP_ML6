# NLP_ML6

### Step to process the Safety Data Sheet pdf

1) Create a VE for the project
2) Open different PFD of the project and list the element that can be extracted => Patterns that always come back.
3) Open the pdf
4) Extract the Raw text from the pdf ; Hint => With Librairies  pyPDF2 package, PDFtoText/Xpdf, pdf2ascii, tika
5) Converting the data to HTML or XLM ? using "pdfminer"  HTML tags might help us to identify specific pieces
6) Extracting identification informations using Regex or **SDSParser 0.2.2** 
7) Install regex Develloper Gui from SDSParser
8) Add a manufacturer with Regex developper tool
9) split the text data into address chunks => Use tags and RE to split the data with Python's finditer 
10) Pull out the easy bits => Product name, adresses,phone number, 
11) Pull out semi-easy bits => ex more difficult adresses to extract
12) Write a program with conditions
13) Convert extractions to dictionnaries
14) Save a Json file

**Source**

http://zevross.com/blog/2014/04/09/extracting-tabular-data-from-a-pdf-an-example-using-python-and-regular-expressions/

https://github.com/astepe/sds_parser

https://pdfminersix.readthedocs.io/_/downloads/en/latest/pdf/

https://stackoverflow.com/questions/48744241/extract-text-from-a-pdf-with-regex

https://towardsdatascience.com/how-to-extract-data-from-pdf-forms-using-python-10b5e5f26f70



### **Reasearch work :**

How SPS sparser work under the hood ; 
What pdfminer is doing in the librairy? Explore the python file and documents

How OCR is used with pytesseract ? Explore the python file and documents

Can we add a new key ? 

Can we write a loop to add a new manufacturers in one time

Compare the test pdf and our pdf and find what is the difference and why does it doesn't work half of the time with our pdf. 

Discuss with the developper on how to log to mangodb as root and launch the Gui (more details and explanations)

Try to find in the code some structure they used, copy regex code they use.
