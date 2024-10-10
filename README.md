Process Overview

1.
Extracting Tables: 
Utilized Tabula to extract tables from the PDF into Pandas DataFrames, supporting both scanned and structured PDFs.

2.
Decrypting PDFs:
Used PikePDF for handling password-protected PDFs, decrypting them temporarily for processing.

3.
Filtering Tables:
Extracted relevant tables based on keywords like "Date," "Transaction," and "Amount" to focus on financial information.

4.
Data Cleaning:
Dropped NaN values in the "Amount" column.
Filled NaN values in the "Date" column with the previous available date.
Split concatenated dates into individual rows.
