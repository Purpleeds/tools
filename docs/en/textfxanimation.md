# Text FX Animation

Creates text animation XML from effect presets for Alight Motion. This option suits you if you want to start from a ready-made effect and adjust the text.

## How to use it

1. Fill in **Teks** (Text), for example "selamat datang" ("welcome").
2. Choose a **Preset FX** from the list shown.
3. Choose **Mode: Per character** for a per-letter effect, or **Per word** for a per-word effect.
4. Choose a **Font lokal** (Local font) and **Style font** (Font style).
5. Set the Font Size within the provided range.
6. Choose a palette if you want to replace the preset's colors.
7. Fill in the project name and file name if needed.
8. Press Generate XML, Download, then import it into Alight Motion.

## What the settings mean

**Per character** splits the effect more finely. For long text, the number of layers and the processing can be larger than with Per word.

**Style font** (Font style) is the font weight, not the animation effect choice. The effect is set in Preset FX.

**Font Size** in this form has a range of **8–12**. That is the scale this engine provides; don't equate the number directly with font sizes in other design apps.

## Colors and history

Without a palette change, the engine may keep the preset's default colors. If you choose a palette, check the resulting colors after Generate. Custom palettes accept color codes and are limited to 15 in the device's browser.

Local history keeps up to 10 results for this generator. Download All downloads the saved results; it doesn't create one combined video.

## Example and issues

Start with two words, one preset, and the default font. Import the XML and play it in Alight Motion before making long text. If the effect doesn't fit, change the preset and Generate again.

The result is not an MP4. If you need a final video, finish your adjustments and export the video from Alight Motion. For more timing control, see [2D Text Animate](text2d.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [List of all tools](README.md)
