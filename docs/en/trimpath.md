# Trimpath Generator

Creates letter animations for Alight Motion in which the strokes appear to be traced or drawn step by step. Suitable for handwriting-style titles that appear along a path.

## First steps

1. Fill in **Tulis di Sini** (Write Here) with a short word that's easy to test.
2. Choose **Trimpath Biasa** (Regular Trimpath).
3. Leave Aktifkan Style (Enable Style) off to see the basic motion.
4. Use the default size, spacing, and timing.
5. Press Generate XML, download, then play the result in Alight Motion.
6. Once the flow works for you, add colors or a Style.

## Options and terms

| Setting | What it means |
| --- | --- |
| **Pilih Animasi** (Choose Animation) | Trimpath Biasa (Regular Trimpath) or motion variations such as Move In, Move In Up, In Up Move, and Move From Left. |
| **Aktifkan Style / Style** (Enable Style / Style) | Extra visual effects beyond the basic animation. |
| **Ukuran Font / Jarak antar Huruf / Line Gap** (Font Size / Letter Spacing / Line Gap) | The size and spacing of the text. |
| **Italic** | Guidance for slanted text. |
| **Stagger (ms)** | The start delay between letters; small numbers make them appear closer together. |
| **End Hold (ms)** | How long the text holds after the motion. |
| **Extend Layer** | The option to extend how long the layers exist. |
| **Layer Graph** | The rate of change of the motion, for example Smooth or Linear. |
| **Aktifkan Color Mapping** (Enable Color Mapping) | Uses a color distribution pattern from the palette. |

The **Single** mapping mode uses one color; **Linear**, **Mirror**, and **Repeat** apply different color arrangements. **Repeat every** sets the repeat interval in the modes that use it. Mapping Style sets the colors of the extra effect, separately from the letters' base color.

## An easy example

Use "NEXORA", Trimpath Biasa (Regular Trimpath), a white base color, and Stagger 30 ms. After seeing the result in Alight Motion, try Style Orange so the change is easy to spot.

Don't change many values at once. If the motion feels too slow or too busy, change one timing or style setting, Generate again, then compare.

## Limits and results

The engine uses letter data that's already available. If the message **Karakter belum tersedia di engine** (Character not yet available in the engine) appears, replace the character it names; emoji and every letterform aren't automatically supported.

The result is XML, not a final video. The web preview helps you read the text, while the full motion needs checking in the imported project. History and custom palettes are stored locally on the device.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [List of all tools](README.md)
