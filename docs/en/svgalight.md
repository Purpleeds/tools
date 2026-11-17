# SVG → Alight XML

Converts a static SVG into an XML that can be imported into Alight Motion. Suitable when you want to use a logo or vector illustration as shapes in an animation project.

**SVG** is a shape-based image. **XML** here is the output for Alight Motion, not a PNG image or a video.

## Getting started

1. Prepare an SVG file of at most 2 MB. PNG/JPG isn't accepted directly as SVG.
2. Open **SVG → Alight XML** and choose or drop the file.
3. Wait for the preview and the layer list to be read.
4. For a first try, choose **Maximum Fidelity**.
5. Set the project size, project name, FPS, and duration.
6. Check the shapes selected in the layer list.
7. Press **Convert ke XML** (Convert to XML).
8. Read the status and warnings, then use **Download XML**.
9. Import the result through Alight Motion's XML project import and check how it looks.

If your source is still PNG/JPG, create an SVG first with [Vecto](vecto.md) or [AUTO TRACE](imagevectorizer.md).

## Choose a conversion mode

| Mode | Purpose | What to watch for |
| --- | --- | --- |
| **Maximum Fidelity** | Keeps the source's detail and arrangement as much as possible. | The starting choice when shape accuracy matters more. |
| **Smart Color Groups** | Groups shapes that share the same solid color. | Read the stacking order and conflict report; not every shape can be grouped without changing the appearance. |
| **Small Patch Cleanup** | Reduces small areas considered to be fragments. | Small details that actually matter need rechecking. |

In Cleanup, **Small Patch Threshold** sets the limit for small areas and **Protect Thin Details** helps protect thin details. Start with the default values and compare results, especially eyes, lines, or small gaps.

## Project and shape settings

- **Asli / 1:1 / 16:9 / 9:16 and others** (Original / 1:1 / 16:9 / 9:16): canvas size or ratio options.
- **Dimensi custom** (Custom dimensions): a width and height you enter yourself.
- **FPS:** the project's frames per second; not the image's level of detail.
- **Durasi** (Duration): the project length in seconds.
- **Semua / Tidak Ada / Balik** (All / None / Invert): controls the shape selection in the list.
- **Flat:** shapes are arranged directly.
- **Nested Groups:** keeps the group arrangement in the output structure.
- **Detect Primitive Shapes:** tries to use compatible basic shapes where possible; the rest stay as paths.

**Rekonstruksi overlap fill** (Overlap fill reconstruction) is an extra option in Maximum Fidelity for handling areas that cover each other. Curve shapes may change; use it only when needed and compare the results.

## Preview and result

The **− / + / Fit** buttons only help you view the preview; they don't change the export size. **Nama project Alight Motion** (Alight Motion project name) differs from **Nama file download** (Download file name): the first is the name inside the project, the second is the XML file's name on your device.

**Salin XML** (Copy XML) copies the result text. **Tampilkan penuh** (Show full) opens a long result. If you change the shape selection or settings after converting, run the conversion again so the result matches your latest choices.

## If it doesn't work yet

If an engine option is disabled, the service didn't offer that option when checked; use **Cek ulang** (Check again) once the service is ready. If the SVG can't be read, check its format and avoid files that only had their extension changed from PNG to SVG. If it looks different in Alight Motion, check the shapes, effects, gradients, and compatibility warnings.

For motion that's already in the SVG code, use [SVG Animasi → Alight XML](svganimation.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/svg-alight.js) · [List of all tools](README.md)
