# Bank statement Analysis


Bank statements are a crucial source of information for monitoring financial transactions, but manual processing of bank statements is susceptible to errors, and traditional accounting software may not provide detailed insights into transactions. This research project proposes a solution that leverages advanced machine learning and natural language processing techniques to extract relevant information from bank statements and accurately classify transactions.

The users can classify transactions into debit and credit categories and identify transactions into specific categories based on user-defined rules. Additionally, the platform provides summaries of transactions, including the number of transactions, minimum and maximum balances, minimum and maximum debits, and maximum credits.

**Files**
1. extract.py: contains functions for extracting data from pdfs of diffetent banks(currently, Yes Bank and Allahabad Bank)

2. analysis.py: contains functions for processing and analizing the data

3. main.py: the driver code that accepts the filename of the PDF

**Setup**
Prequisites:- Python 3 and tesseract need to be installed
for tesseract, see: https://github.com/tesseract-ocr/tesseract/wiki


1. Run 
	pip install -r requirements.txt

2. Run
	python main.py <filename.pdf>

This starts the process and generates the outputs in excelsheets and returns JSON output

