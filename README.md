PDF Table Extraction using Tabula & PDFPlumber
Overview
This project extracts tables from PDF documents using tabula-py and saves them as separate Excel files.
It helps automate data extraction from structured PDF documents.

Features
1. Extract tables from PDF using tabula-py library.
2. Saves extracted tables as separate Excel files.
3. Supports multi-page PDFs.

Installation
Ensure you have Python and the required dependencies installed:

!pip install tabula-py pandas openpyxl 

Usage
1. Place the PDF file in the project directory
Ensure the PDF file you want to process is available in the directory.

2. Run the Jupyter Notebook
tabula_method.ipynb → Uses tabula-py for extraction.

3. Extracted tables will be saved automatically
The extracted tables will be stored in:

extracted_tables_from_pdf/ 
Each table is saved as a separate .xlsx file.
