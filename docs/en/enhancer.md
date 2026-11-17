# Nexora Image HD Enhancer V4

Improves image quality through an online service. The input can be a gallery file or a direct image file link.

## How to use it

1. Open **Nexora Image HD Enhancer V4**.
2. Choose **Upload** for a JPG/PNG/WebP of at most 12 MB, or **URL** for an image link.
3. Make sure the source preview is correct.
4. Press **Proses** (Process).
5. Wait for the result to finish and read the size or scale information.
6. Use **Bandingkan** (Compare) to see the changes.
7. Press **Download** to save the result.

Example: upload a small product photo, process it, then check the label text and texture before using the result for a catalog.

## How to read the result

**Quality improvement** and **dimension enlargement** are not always the same. An image can look cleaner without its pixel count increasing.

The interface checks input/output sizes if that information is available. The message **Upscale terverifikasi** (Upscale verified) means the enlarged dimensions have been checked. A message that the scale is awaiting verification means you shouldn't assume the result has been enlarged by a particular factor.

Don't conclude every image becomes 4× just from the name HD. For clear 2× or 4× control, use [Perbesar Gambar 4x](bigjpg-nexora.md) (Enlarge Image 4x).

## Buttons and issues

- **Bandingkan** (Compare): checks the source and result; doesn't reprocess.
- **Download:** fetches the result that's already available.
- **Gambar lain** (Another image): prepares a new input.
- **Batalkan proses** (Cancel process): stops the wait handled by the page.

If a URL fails, make sure the link opens an image file, not a web page. If the service is unavailable or applies a request limit, read the message and wait before trying again.

Download before closing the tool. Check faces, small text, lines, and details in the result, because AI processing can change how they look.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/image-lab-shell.js) · [List of all tools](README.md)
