# DocExtract Pipeline

Intelligent document processing pipeline that extracts structured data from unstructured PDFs, invoices, and contracts using AI-powered OCR and NLP.

## Features
- Multi-format support (PDF, DOCX, images)
- Multi-language OCR (English, Indonesian, Mandarin)
- Table extraction with structure detection
- Entity recognition and classification
- Batch processing with progress tracking

## Installation
```
pip install -r requirements.txt
```

## Usage
```
python main.py process ./invoices/ --output results.json
python main.py extract contract.pdf --fields vendor,date,amount
```

## License
MIT