# Nexora OCR Intelligence

Extracts text from photos or PDFs so it can be copied and searched. **OCR** means reading text in an image; the result still needs correcting if the source is blurry or hard to read.

## Getting started

1. Add a JPG, PNG, GIF, BMP, TIFF, or PDF of **at most 1 MB**.
2. To take a new photo, use **Kamera** (Camera) and follow your browser/device's camera picker.
3. Choose an available **Bahasa dokumen** (Document language), or Auto detect.
4. For a first try, use **Engine 2 · balanced**.
5. Turn on Searchable PDF or Table mode if needed.
6. Press **Ekstrak & analisis** (Extract & analyze).
7. Read the result while comparing it with the original document.
8. Use Copy, TXT, JSON, or the PDF download if the result is available.

## Options to understand

| Option | Purpose |
| --- | --- |
| **Engine 2 · balanced** | A balanced starting option. |
| **Engine 3 · handwriting** | Tries working with handwriting; accuracy isn't guaranteed. |
| **Engine 1 · fastest** | An option geared toward speed. |
| **Searchable PDF** | Requests a PDF with a text layer so the OCR text can be searched. |
| **Table mode** | Helps handle the layout of tables, invoices, or receipts. |
| **Cari di dokumen** (Search in document) | Searches for words in the text that has been read. |

The language list follows the options actually present in the form. Indonesian isn't listed as a separate option in this interface; use a suitable option or try Auto detect, then check the result.

## Examples

For a shopping receipt, upload a straight, readable photo, choose Table mode, then Ekstrak & analisis (Extract & analyze). Check prices, quantities, and decimal separators in particular.

For a scanned document you want to be searchable, turn on Searchable PDF before processing. The result isn't automatically a Word document with the same layout.

## If the result isn't good

Take the photo in even light, avoid shadows and strong tilting, then try again. Don't shrink the file until the letters become unreadable just to meet the file limit.

If the PDF or image is over 1 MB, prepare the parts you need in a lighter file. If you only want to summarize the content once the text has been read, use [Document AI](documentai.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/ocr-intelligence.js) · [List of all tools](README.md)
