# watermarker
Python script that uses the PyPDF2 library to add a watermark to a PDF file. Let me break down the code for you:

1. Import PyPDF2: This line imports the PyPDF2 library, which is used for working with PDF files.

2. Open PDF Files: It opens two PDF files - 'super.pdf' as the main template and 'wtr.pdf' as the watermark.

3. Create PdfWriter Object: The PdfWriter object is created to store the output PDF, where the watermark will be added to each page of the template.

4. Loop Through Template Pages: It iterates through each page of the template PDF using a for loop.

5. Merge Pages: For each template page, it merges the page with the first page of the watermark PDF using the merge_page method.

6. Add Merged Page to Output PDF: The merged page is added to the output PDF using the add_page method.

7. Write Output PDF to File: Finally, the resulting watermarked PDF is written to a new file named 'watermarked.pdf'.
