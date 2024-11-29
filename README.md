# PDF Text Extraction and Querying with xAI

This project demonstrates how to extract text from PDFs, split the content into chunks, generate embeddings using the xAI API, and use the resulting embeddings for querying the document. It also includes the functionality to handle scanned PDFs using OCR.

## Features:
- **PDF Text Extraction**: Extracts text from PDFs using `unstructured` and other libraries.
- **Text Chunking**: Splits the extracted text into manageable chunks for processing and embedding generation.
- **Embedding Generation**: Uses the xAI API to generate text embeddings for efficient search and retrieval.
- **OCR Handling**: Can process image-based PDFs using OCR (requires `pytesseract`).

## Requirements:
- **Python 3.x**
- **Google Colab or Local Python Environment** (with internet access)
  
### Required Libraries:
- `langchain`
- `nltk`
- `requests`
- `unstructured`
- `pdf2image`
- `pytesseract` (for OCR)
- `tesseract-ocr` (system dependency for OCR)

## Installation

Before running the script, ensure the required packages are installed in your environment.

### 1. Install Python Libraries:
Install the necessary Python libraries via `pip`:

```bash
!pip install langchain unstructured pdf2image pytesseract requests

### Acknowledgments
This project leverages LangChain for document processing and text embedding generation.
Thanks to the authors of the unstructured and pdf2image libraries, which helped with extracting text from complex PDFs.
