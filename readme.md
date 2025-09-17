# PDF Parsing and JSON Extraction

## Objective
This project parses a PDF factsheet and extracts its content (paragraphs, tables, charts) into a structured JSON format.

## Requirements
- Python 3.8+
- Libraries: pymupdf, pdfplumber, pandas, pillow

## How to Run (Colab)
1. Open the notebook `pdf_parser.ipynb` in Google Colab.
2. Upload the input PDF file when prompted.
3. Run all cells.
4. The output will be:
   - `factsheet_output.json` → structured JSON
   - `factsheet_images/` → extracted charts/images


