# Nexora Document AI

Helps you read documents through summaries, analysis, study notes, table extraction, and questions and answers about their content.

## Material you can use

The form accepts **PDF, JPG, PNG, WebP, TXT, MD, and CSV**. Documents can be at most **3 MB**; camera photos can be up to **12 MB before optimization**. The page will make large images lighter.

## Getting started

1. Press **Pilih File** (Choose File) and add one document.
2. Check the name and size shown.
3. Choose an analysis mode.
4. Press **Analisis Dokumen** (Analyze Document).
5. Wait for the finished status, then read the Ringkasan (Summary), Poin (Points), Teks (Text), and Tabel (Table) tabs, depending on the result.
6. To ask further questions, open **Tanya AI** (Ask AI) and write a question about that document.
7. Save the parts you need through the export options.

## Choose a mode based on your goal

| Mode | What it's for |
| --- | --- |
| **Smart Summary** | Getting the gist of the document and the key facts. |
| **Deep Analysis** | Reading the context, risks, and recommended actions. |
| **Study Notes** | Creating more structured study notes. |
| **Table Extract** | Extracting table data so it can be reviewed or saved as CSV. |

Example: for lecture material, choose Study Notes. For a report you want to read quickly, choose Smart Summary. For a sales table, try Table Extract, then compare the figures with the source.

## Asking about the document

Analyze the document first. Once the result is available, write a specific question such as:

> What are the three main conclusions in this document? Name the sections that support them.

Questions that refer to specific sections are easier to check than "explain everything". If you switch documents, analyze the new document before using the results.

## Exporting and checking

Common options include **TXT**, **JSON**, and **Word**. Tables that were actually found may have their own **CSV** button. Word is a report output prepared by the tool, not a guarantee that the document's original layout stays exactly the same.

AI can misread or mis-summarize. Match numbers, dates, names, and table contents against the original file. No table appearing may mean no table was found, not that there's an empty CSV to download.

If the button isn't active yet, make sure the file loaded successfully. If the size is rejected, choose a file within the limit. The online AI service needs to be ready; this differs from [PDF Lab Local](pdflab.md), which processes PDF structure on your device without AI analysis.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/document-ai.js) · [List of all tools](README.md)
