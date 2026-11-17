# Nexora Avatar Studio

Creates avatars from a range of character styles, then lets you adjust the details without drawing from scratch. Results can be downloaded as SVG or a regular image.

## Getting started

1. Open **Nexora Avatar Studio**.
2. In **Choose a base style**, pick a style you like. Use Search style if the list is long.
3. In **Avatar controls**, change the details available for that style.
4. See the changes in **Live Preview**.
5. For an avatar that's ready to use, choose **Download PNG**. For a vector file, choose **Download SVG**.

For a quick start, use **Randomize Avatar / Shuffle Avatar** or **Random Style**, then adjust the result.

## Understanding the Seed and settings

The **Seed** is reference text or a number used to build the avatar. The same seed with the same style and settings helps recreate the same arrangement. The seed is not an account number.

**Random Seed** changes the variation reference. **Copy** in the seed section copies it. Changing the style can bring up different settings; a style doesn't necessarily have the same hair, eye, or clothing options.

Use **Search settings** to find a control, for example "Hair" or "Background". Start with the colors, background, and facial features that the style actually offers.

## Formats and sizes

| Option | Used for |
| --- | --- |
| **SVG** | A vector avatar that can be scaled up wherever SVG is supported. |
| **PNG** | A general image, including when you need transparency, if the result supports it. |
| **JPG** | An image without transparency. |
| **WebP / AVIF** | Modern image formats; support depends on the browser. |
| **JSON** | The avatar's configuration or information, not a picture of the avatar. |

**Raster size** sets the output size of regular images. The 512 or 1024 options in the interface are produced by processing in the browser; the raster API source has different limits. Download through Download selected if you're using a format chosen from the list.

## Saving so you can reuse it

- **Save Preset** saves your choices in that device's browser.
- **Copy Config JSON** saves the arrangement of settings; good for reusing through Import Config.
- **Copy SVG URL / Copy Image URL** copies the source link.
- **Copy &lt;img&gt; / Copy Markdown** copies the code for embedding the image in a page or document.
- **Share Config** helps you share settings that can be reproduced.

Example: create a style you like, set the Seed to "nexora-kopi", save a preset, then download a PNG for your profile picture. Save the configuration if you want to recreate it on another device.

If exporting a particular format fails, try SVG or PNG. **License Info** shows information about the style; check it when the result will be used in a product you share.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/avatar-studio.js) · [List of all tools](README.md)
