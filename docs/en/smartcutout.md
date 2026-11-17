# Nexora Smart Cutout

Selects a specific object in a photo and exports it as a transparent PNG. You help the AI by tapping the parts to keep or discard.

## How to use it

1. Press **Upload Image** and choose a JPG, PNG, or WebP of at most 20 MB.
2. Wait for the image and the model to be ready.
3. Leave **Select +** on, then tap the middle of the object you want to keep.
4. Check the mask or area marker in the preview.
5. Add more Select + taps if parts of the object are still missing.
6. If background got selected too, choose **Remove −**, then tap the area you want to discard.
7. Choose a **Soft** or **Sharp** edge.
8. Press **Extract Object**.
9. Check the Result, then **Download PNG**.

## Settings and terms

A **mask** is a map of the parts to keep and discard. The mask PNG is not the final object image; use Download PNG for the colored object with transparency.

**Soft** makes edges gentler. **Sharp** uses crisper edges. Match it to your need; for example, hair often needs a more careful edge check.

**Crop to Object** crops the canvas close to the object with about 3% extra space around it. Turn it off if you want the result to keep the source canvas area.

**Undo** cancels the last selection step; **Reset** clears the mask selection so you can start selecting again. **Ganti** (Replace) chooses a new image.

## Example

In a photo of a table with a cup and a book, choose Select + and tap the cup. If the book gets included, switch to Remove − and tap the book. Once the preview looks right, Extract Object and save the PNG.

On a phone, pinch to zoom and drag while zoomed in so your taps land more precisely. Zoom only helps selection; it doesn't add detail to the image.

## If it doesn't work yet

The Extract button isn't active until the mask is ready. Wait for the model and add points on the object. If the result is still wrong, change the selection points and extract again. The model is downloaded when needed, but selection and image processing run in the browser.

To remove backgrounds with an automatic flow and a brush editor, see [Remove Background](removebg.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/smart-cutout-core.js) · [List of all tools](README.md)
