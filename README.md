# Invoice To Database Scanner

A project for a startup company based in Great Falls, Virginia.

The project containts a Python script that automates the process of scanning invoices, extracting essential information, and organizing it into a structured database for documentation efficiency. The script is designed to streamline invoice processing by eliminating manual data entry, reducing errors, and improving the speed of documentation.

Using Optical Character Recognition (OCR) technology, the script reads invoice PDFs or scanned images, identifies key fields such as invoice number, date, client name, total amount, and line-item details. The script is highly customizable, allowing users to define additional fields or adjust for varying invoice formats.

The system uses Python’s pytesseract library for OCR and pandas for data manipulation. The extracted information is stored in a structured format, in BigQuery.

This solution saves considerable time and ensures that all financial records are up-to-date, well-organized, and easily searchable for future audits or analysis.
