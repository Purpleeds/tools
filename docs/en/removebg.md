# Remove Background

Removes an image's background and provides an editor for fixing parts that are still wrong. The final result can be used as a transparent image in other designs.

## Getting started

1. Choose the **Upload** tab and add a JPG/PNG/WebP of at most 12 MB, or use the **URL** tab for a direct image file link.
2. If **AI otomatis setelah upload** (Automatic AI after upload) is on, wait for processing. If not, press **Proses** (Process).
3. Read the status until the result is actually ready.
4. Use **Bandingkan** (Compare) to see the source and the result.
5. If it's clean, press **Download**.
6. If parts are missing or background remains, open **Edit manual / rapikan hasil** (Edit manually / tidy up the result).

Links from post pages or search results aren't necessarily direct image files. If a URL fails, try uploading the file from your device.

## Tidying up the result with the editor

| Tool | Purpose |
| --- | --- |
| **Hapus** (Erase) | Removes the area the brush passes over. |
| **Pulihkan** (Restore) | Brings back erased parts of the image. |
| **Hapus area** (Erase area) | Erases an area, taking the chosen tolerance into account. |
| **Geser** (Pan) | Moves the view when zoomed in. |
| **Ukuran kuas** (Brush size) | The width of the stroke. Small for detail, large for wide areas. |
| **Ketegasan** (Hardness) | How hard or soft the brush edge is. |
| **Toleransi area** (Area tolerance) | How widely similar areas are reached by the area-erase tool. |
| **Undo / Redo** | Undoes or redoes corrections. |
| **Rapikan tepi** (Tidy edges) | Helps thin out leftover edges with the available options. |
| **Terapkan hasil** (Apply result) | Applies the editor's corrections to the result that will be saved. |

Example: if part of the hair went missing, choose Pulihkan (Restore) with a small brush. If background remains between the arm and the body, zoom in and then Hapus (Erase) carefully.

## The preview is not the file's color

The **Transparan / Putih / Hitam** (Transparent / White / Black) background helps you check the object's edges. Changing the viewing background is not the same as changing the result file's background to that color.

Use +/− or Pas layar (Fit screen) to navigate. When you finish tidying up, Terapkan hasil (Apply result), then check the download, not just the editor preview.

## If something goes wrong

Wait for the previous process to finish before adding a new job. If the input is damaged or too large, choose an image within the limit. If a correction isn't right, use Undo, Redo, or Ulang koreksi (Redo corrections) before applying it.

Automatic results still need checking, especially fine hair, glass, shadows, and objects whose colors resemble the background.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/remove-background-v4.js) · [List of all tools](README.md)
