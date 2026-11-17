# Foto To Link (Photo to Link)

Uploads an image to public storage and then produces a **direct URL**, a link that opens the image file directly.

## How to use it

1. Choose a JPG, PNG, WebP, or GIF of at most **10 MB**.
2. You can use the file picker, drag & drop, or paste an image from the clipboard if your browser supports it.
3. Check the preview and file name.
4. Press **Upload & Buat Link** (Upload & Create Link).
5. Wait until a verified-upload message and the resulting link appear.
6. Press **Salin** (Copy) to copy the direct URL.
7. Use **Buka gambar** (Open image) to check the link.
8. **Upload lagi** (Upload again) prepares the next image.

Example: upload a product image you actually intend to share, copy its link, then use it in a service that asks for a direct image URL.

## Understanding the status

The initial preview only shows the file you chose on your device. That **doesn't yet mean the file has been uploaded successfully**.

A ready-to-use link appears after the upload is verified. If it times out and the button changes to **Periksa Upload** (Check Upload), use that button to check the state of the earlier job before trying a new upload.

## Limits and results

The resulting link is public; anyone with the URL can open the image. Choose images that are appropriate to share this way.

**Salin** (Copy) copies the address; it doesn't send the image to another app. If clipboard access is denied, select the URL text and copy it through the browser menu.

If the size or format is rejected, choose a suitable file. If verification hasn't succeeded, don't share the local preview as a public link. A valid link must open the file from the storage service.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/photo-to-link.js) · [List of all tools](README.md)
