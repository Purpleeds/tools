# 3D Text Animate

Creates three-dimensional-style text XML for Alight Motion. The effect is built through motion templates, thickness, color layers, and shadows.

## Getting started

1. Enter short text, for example "NEXORA".
2. Choose **Preset 3D: Flip 3D** for a first try.
3. Choose Timing target per character or per word.
4. Use the default font and size at first.
5. Check the colors in **Color roles**.
6. Press Generate XML, download, then import it into Alight Motion.

The tool produces an XML project, not a 3D model such as OBJ or a video file.

## Preset options

| Preset | The look |
| --- | --- |
| **Flip 3D** | A flipping motion with a three-dimensional feel. |
| **Right** | A rightward motion variation. |
| **Popup Rotate Extrude** | A pop-up appearance with rotation and thickness. |
| **Long Shadow** | Emphasis on a long shadow. |
| **Offset Kosongan** (Offset Blank) | A layer-shift variation. |
| **Offset Orange Style** | An offset variation in an orange style. |
| **Offset Green Fire** | An offset variation in a green style. |

## Important settings

- **Timing target:** motion per character or per word.
- **Graph preset:** the motion's speed pattern, such as Smooth, Linear, or a random option.
- **Extrude / Depth (%):** guidance for the effect's thickness or depth.
- **Border:** turns on edges according to the preset.
- **Link font size & spacing:** when on, changing the font size also adjusts the spacing.
- **Spacing / Line gap:** the spacing between letters and between lines.
- **Stagger:** the start delay between parts.
- **Last Start:** sets the last start time in the animation arrangement.
- **End Hold:** how long the result holds after the motion.
- **X Position / Y Position:** position settings; start with the default values before experimenting.

## Setting colors

Color roles change with the preset. A preset may have different colors for the surface, edges, or shadow. Don't assume one color changes the whole result.

Choose a palette to fill the color roles, then adjust specific colors if needed. History and custom palettes are stored locally, not as a project that automatically syncs to all devices.

## Results and issues

Generate again after changing the preset or colors. If the text is too long or the position isn't right, check the spacing and size in the resulting project in Alight Motion. The file name is different from the project name inside the XML.

The web preview is not a full simulation of every Alight Motion effect. Save the XML you like from Download or the local history.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora/nexora-runtime.js) · [List of all tools](README.md)
