# PDF Lab Local

Processes PDFs right on your device. The available jobs include arranging pages, merging, splitting, creating a PDF from images, adding a watermark or text, changing document information, and filling in forms.

## Getting started

1. Choose an **operation** first.
2. Add files in the upload area.
3. Wait for the pages or file list to appear.
4. Make the changes for that operation.
5. Press **Export PDF**.
6. Open the resulting file to check its pages and content.

Changes such as deleting and rotating are applied to the exported result. The original file on your device isn't automatically overwritten.

## Choose the right operation

| Operation | Specific steps |
| --- | --- |
| **Organize** | Tap pages to select them. Use the arrows on a page to change the order, Hapus (Delete) to remove it from the result, and Rotate +90° to rotate it. |
| **Merge** | Add at least two PDFs. They're merged in the order of the file list. Check the order before Export. |
| **Split / Extract** | Fill in the Rentang (Range) field to choose which pages are split off. |
| **Images → PDF** | Add PNG/JPG/WebP files. Choose a Page size that follows the image or A4, then set the Margin in mm. |
| **Watermark** | Fill in the watermark text, size, opacity, and angle. |
| **Add Text** | Fill in the text, size, and X/Y position as percentages. |
| **Metadata** | Change the Title, Author, Subject, or Keywords. Clear metadata removes that information. |
| **Fill Form** | Fill in the interactive form fields found in the PDF. |

### Split / Extract example

To take pages 1 to 3 and page 5 into one file, enter:

> 1-3,5

To create two separate files, use a semicolon:

> 1-3,5; 6-10

The part before the semicolon becomes one result, and the part after it becomes another. Page numbers start from **1**, not 0.

### Watermark and Add Text

**Target halaman: Semua halaman** (Target pages: All pages) applies the change to the whole document. For **Halaman terpilih** (Selected pages), tap at least one page in the preview before Export.

For the watermark, a low **Opacity** makes the text more transparent; **Angle** sets the tilt. For Add Text, X/Y sets the text position; use the exported result to check that the position is right.

### Filling in forms

Fill Form only recognizes interactive PDF fields, or **AcroForm**. A plain scanned PDF doesn't automatically become a form.

**Flatten form** merges the form values into the page's appearance so they're no longer easily editable fields. Check your entries before choosing it.

## Example use

You want to send the important pages from a 20-page document:

1. Choose Split / Extract.
2. Add the PDF.
3. Enter "1-2,8" if you need pages 1, 2, and 8.
4. Export PDF.
5. Open the result and make sure only those three pages are there.

## Storage and issues

Processing uses the browser; documents aren't uploaded to Nexora's server. However, the app's libraries or assets still need to be available when you open it.

The per-file limit in the code is 250 MB, with a notice for files over 80 MB. That limit isn't a guarantee your phone can handle it; start with smaller documents.

If Export isn't active yet, make sure the file has been read. Merge needs more than one PDF. If a PDF can't be read, check whether the file is damaged, encrypted, or uses unsupported features.

**Add Text adds new text; it doesn't automatically edit existing paragraphs in the PDF.** To read text from a scan, use [OCR Intelligence](ocrintel.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/pdf-lab/src/workspace.js) · [List of all tools](README.md)
