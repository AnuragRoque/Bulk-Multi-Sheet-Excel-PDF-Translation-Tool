# Bulk Multi-Sheet Excel & PDF Translation Tool

## Overview
This repository provides a tool for bulk translating multi-sheet Excel files and scanned PDF documents. Designed to handle large datasets and scanned files, this tool uses advanced Optical Character Recognition (OCR) to extract and translate text, making it ideal for users who need quick, accurate translations at scale.

### Supported File Formats:
- **Excel Files**: Multi-sheet support for translating cell data in .xlsx files.
- **PDF Files**: Support for translating both standard and scanned PDFs, including images with text.

### Key Features
- **Bulk Translation for Excel**: Automatically translate text in multi-sheet Excel files.
- **PDF Translation (Including Scanned)**: Translate both standard and scanned PDFs, with OCR for extracting text from images.
- **Multi-Language Support**: Supports translation to and from multiple languages, including English, Spanish, French, German, and more.
- **OCR Technology**: Uses Tesseract OCR and Google Cloud Vision API to extract text from scanned PDFs, even in low quality.
- **Automated Process**: Save time and effort with automated translation for bulk files.

## Tech Stack
- **Programming Language**: Python
- **Libraries and Tools**:
  - **Google Translate API**: For translation functionality.
  - **OpenPyXL**: For working with multi-sheet Excel files.
  - **Pandas**: For handling and processing data.
  - **Tesseract OCR**: For extracting text from scanned PDFs.
  - **Google Cloud Vision API**: For OCR in scanned PDFs.
- **Additional Tools**:
  - **PyPDF2**: For PDF handling.
  - **pdf2image**: For converting PDF pages to images.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your_username/bulk-multi-sheet-excel-pdf-translation-tool.git
