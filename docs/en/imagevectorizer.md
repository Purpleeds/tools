# AUTO TRACE

Converts PNG/JPG/WebP images into SVG with the **Vector Ink** engine. The result is built by tracing the image's shapes and colors, so it's easiest to understand with a logo or simple illustration first.

AUTO TRACE and [Vecto](vecto.md) are two separate tools with different engines.

## First steps

1. Prepare a PNG, JPG, or WebP of at most 12 MB.
2. Upload it through **Drop atau pilih gambar** (Drop or choose an image).
3. For a first try, use the default settings: Color Detail 6/8, Smoothness 70, Noise Removal 14.
4. Press **Trace dengan Vector Ink** (Trace with Vector Ink).
5. Wait until the SVG is actually available.
6. Compare the **Original**, **Split**, and **Vector** views.
7. If it looks right, press **Download SVG**.

Zooming into the preview doesn't bring back detail that isn't in the source image. Photos with lots of gradients can produce a more complex SVG than a logo with a few colors.

## Three main settings

| Setting | How to understand it |
| --- | --- |
| **Color Detail** | Guidance on how much color detail is kept. Change it a little at a time, then compare. |
| **Smoothness** | Guidance on how smooth the shapes/curves in the result are. Values that are too high can make corners or details look different. |
| **Noise Removal** | Guidance on removing small specks. Use it carefully if the image has important small details. |

These three controls are linked to the advanced parameters. After changing a value, **run Trace again** to create a new result; moving a control doesn't automatically replace an SVG that has already finished.

## Advanced Settings

If you don't understand the technical parameters yet, keep the default values. The available parameters include:

- **Speckle:** the size of small specks targeted for removal.
- **Color Precision:** how precisely colors are distinguished.
- **Corner Threshold:** guidance on how corners are handled.
- **Segment Length / Splice Threshold:** guidance on how segments are formed and joined.
- **Max Iterations:** the limit on process repetitions for the provided parameters.
- **Path Precision:** the precision of path coordinates.

The final effect depends on how the engine processes the request; there's no guarantee that any given number will always make the result better. **Reset Settings** restores the initial parameters.

## Results and Ungroup

**Ungroup** tries to break apart SVG groups so shapes are easier to select separately in another editor. This is not a feature for cutting a character into body parts or separating every color with a guaranteed perfect result.

Some groups may be skipped to preserve the appearance. Read the notes from the Ungroup result, and use **Undo Ungroup** to go back. Downloads use the currently active version of the result SVG.

- **Copy SVG:** copies the SVG code.
- **View code:** shows the result code.
- **Download SVG:** saves the SVG file.
- **Reset:** clears the job for the next image.
- **Retry Vector Ink:** retries a failed request.

If the Vector Ink service has problems, read its failure message. Successfully uploading or seeing the Original image doesn't mean the trace has finished. Save the SVG before closing the tool.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/image-vectorizer.js) · [List of all tools](README.md)
