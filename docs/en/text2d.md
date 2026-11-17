# 2D Text Animate / Text FX

Creates 2D text animation XML for Alight Motion. Suitable for titles, text intros, and entrance effects per letter or word.

## First try

1. Write one or two lines of text in **Teks (maks. 2 baris)** (Text, max. 2 lines).
2. Choose a **Preset animasi** (Animation preset).
3. Leave **Aktifkan Style FX** (Enable Style FX) off at first so the basic motion is easy to recognize.
4. Choose **Layer per: Karakter** (Character) for a per-letter effect or **Kata** (Word) for a per-word effect.
5. Choose a font and color.
6. Press **Generate XML**, then **Download** once the result has been created.
7. Import the XML into Alight Motion and play the project.

Example text: "NEXORA" on the first line and "CREATIVE" on the second.

## Main settings

| Setting | What it means |
| --- | --- |
| **Preset animasi** (Animation preset) | The motion pattern used. |
| **Style FX** | An extra effect style; turn its switch on if you want it applied. |
| **Font lokal / Style font** (Local font / Font style) | The typeface and weight, for example 400 is thinner than 700. |
| **Ukuran font** (Font size) | The text size in the engine's settings, not the size of the page preview. |
| **Spacing / Line height** | The spacing between letters and between lines. |
| **Stagger (ms)** | The start delay between letters or words. 1,000 ms = 1 second. |
| **Spread (ms)** | Controls how start times are spread across the animation. |
| **Durasi layer / Extend layer** (Layer duration / Extend layer) | How long the layers exist, and the option to extend them. |
| **Kurva Bézier** (Bézier curve) | The character of the motion's changes, for example Smooth or Linear. |
| **Random (%) / Seed** | The timing variation the engine provides, and the reference number for that variation. |

To start, use the default timings and only change Stagger if you want letters to appear closer together or further apart.

## Color and results

**Single** uses one color. The Linear, Mirror, and Repeat modes distribute colors from the palette in different patterns. **Repeat every** sets the repeat interval when the related mode is used.

Choose a built-in palette or add colors such as "#7C3AED, #22D3EE, #FFFFFF". Up to 15 custom palettes are saved in the browser. Local history keeps up to 10 results per generator; Download All may trigger several downloads.

The Alight Motion project name and the download file name can be set separately. The page preview helps you check the text, but a full motion check still happens with the XML in Alight Motion. After changing settings, Generate XML again before downloading a new result.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [List of all tools](README.md)
