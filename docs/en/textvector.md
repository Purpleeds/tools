# Text to Vector

Converts text into vector letter shapes and prepares an Alight Motion XML. Once they become shapes, the letters are no longer just an ordinary text field whose content is easy to change.

## Getting started

1. Fill in **Teks** (Text) with a short word, for example "NEXORA".
2. Choose a local Font, for example Poppins, and a Style available for that font.
3. Leave **Mode: Character**, **Vector Style: Fill + Stroke**, **Contour: AM Fix A**, and **Path: Cubic Bézier** for a first try.
4. Set the Fill and Stroke colors.
5. Press Generate XML.
6. Check the vector preview created after Generate.
7. Download the XML and import it into Alight Motion.

## The most important settings

| Setting | What it means |
| --- | --- |
| **Font / Style** | The letter shapes and their weight. The Style list adapts to the font. |
| **Font Size** | The size of the letter geometry that's created. |
| **Letter Spacing** | The spacing between letters. |
| **Padding** | Extra space around the text. |
| **Mode: Character / Word** | Sets grouping per letter or per word. |
| **Fill Only** | Only the shape fill. |
| **Stroke Only** | Only the shape outline. |
| **Fill + Stroke** | Both fill and outline. |
| **Stroke Width** | The outline thickness. |
| **Contour: AM Fix A/B/Original** | Options for handling letter contours for compatibility; start with the default. |
| **Path: Cubic Bézier / Flatten** | Curves, or a more fragmented segment approximation. |
| **Duration / FPS** | The XML project's timing and frame rate. |

## Example use

For white text with a purple outline, choose Fill + Stroke, a white Fill, a purple Stroke, and an initial outline thickness that isn't too large. If you only want an outline, choose Stroke Only.

Letters such as "O", "B", or "A" have empty space inside. Check that space in the preview and in the Alight Motion import. If it looks different, compare the Contour options rather than changing every parameter straight away.

## Results and issues

Font processing is done locally through a browser worker. Wait for the font and the job to finish before downloading. If a font Style isn't available, choose one of the weights that actually appears after switching fonts.

The file name can be changed separately from the project name. After changing the text or font, run Generate XML again. If what you need is an SVG image from a PNG/JPG, use [Vecto](vecto.md); this tool is specifically for turning text/fonts into Alight Motion shapes.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [List of all tools](README.md)
