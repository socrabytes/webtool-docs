---
title: Overview
weight: 2
prev: .
next: quickstart
---

## What is OCR?

OCR (Optical Character Recognition) converts documents into editable, structured text. This tool uses Mistral AI's Vision API to process documents and output clean Markdown.

## Supported Formats

| Format | Extension | Notes |
|--------|-----------|-------|
| PDF | `.pdf` | All PDF types supported |
| PowerPoint | `.pptx` | Microsoft PowerPoint |
| Word | `.docx` | Microsoft Word |
| Images | `.png`, `.jpg`, `.jpeg`, `.gif`, `.webp` | Common image formats |

## Key Features

### Batch Processing

Upload multiple documents at once. Choose how results are organized:
- **Merge mode:** All documents combined into single Markdown file
- **Separate mode:** Each document as its own file (download as ZIP)

### Image Extraction

Embedded images are automatically extracted and referenced in the Markdown output with annotations.

### Download Options

After processing, download your results:
- **Single file:** Download individual Markdown files
- **Merged:** All results in one `ocr_results.md` file
- **ZIP archive:** All files packaged for download

## Privacy & Data

- Uploaded documents are sent to Mistral AI's OCR API for processing
- Processed results are stored temporarily in cloud storage
- **All files are automatically deleted after 24 hours**
- No user accounts, no cookies, no tracking

## File Limits

| Limit | Value |
|-------|-------|
| Maximum file size | 50MB |
| Supported formats | PDF, PPTX, DOCX, PNG, JPG, GIF, WebP |

## Rate Limits

To ensure fair usage, the following limits apply:

| Action | Limit |
|--------|-------|
| Uploads | 50 per day, 10 per minute |
| Downloads | 100 per day, 10 per minute |
| Page views | 2 per second |

If you exceed these limits, you'll see a message asking you to wait before trying again.

## Data Retention
- All uploaded files and processed results are **automatically deleted after 24 hours**
- No permanent storage of user documents
- No user accounts or data tracking