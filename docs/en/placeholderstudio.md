# Nexora Placeholder Studio

Creates filler images for design mockups, thumbnails, banners, or web pages. There are two ways:

- **Classic:** a simple image with text and colors you choose; the preview is made on your device.
- **Prompt:** requests an image from a description through the public service placeholdr.dev.

Use Classic if you just need a box that says "Foto Produk" (Product Photo). Use Prompt if you want a scene or illustration. For a fuller choice of AI models, use [Nexora AI Image](aiimage.md).

## 1. Start with Classic

Example: making a filler image for a product catalog.

1. Open the **Nexora Placeholder Studio** card.
2. Make sure the **Classic** tab is selected.
3. Choose the **Square 1:1** preset, or enter Width 600 and Height 400.
4. Fill in **Teks** (Text) with "Foto Produk" (Product Photo).
5. Choose a gray **Background** and a white **Warna teks** (Text color).
6. Leave **Auto-fit teks** (Auto-fit text) on and **Skala** (Scale) at 1×.
7. Check the preview, which changes after you edit the settings.
8. Enter a **Nama file** (File name), then use **Download** to save the preview.

**Audit note for this version:** the Download button in Classic saves the **local SVG preview**, even when the Format option shows PNG. This was checked through a download in a local browser. If you need a PNG/JPG from the provider, use the original URL or Open Original as explained in section 5.

## 2. Size presets: choose based on your need

| Preset | Size | Example use |
| --- | --- | --- |
| **Square 1:1** | 1080 × 1080 | A square post or catalog card. |
| **Landscape 16:9** | 1280 × 720 | A landscape image. |
| **Portrait 4:5** | 1080 × 1350 | A poster or portrait post. |
| **Story 9:16** | 1080 × 1920 | A Story or vertical phone content. |
| **OG Image** | 1200 × 630 | The card image shown when a link is shared. |
| **Hero** | 1600 × 900 | A large opening image for a web page. |
| **Banner** | 1500 × 500 | A landscape banner. |
| **Thumbnail** | 1280 × 720 | A video cover image. |
| **Custom** | Entered yourself | A special size. |

**Width** means width; **Height** means height, in pixels. For example, 600 × 400 means 600 pixels across and 400 down.

Classic accepts **10–4,000 pixels** per side. Prompt accepts **128–2,048 pixels** per side. Large sizes are heavier for your device and don't automatically make the image content better.

## 3. What the Classic settings mean

| Setting | Purpose |
| --- | --- |
| **Teks** (Text) | The text shown on the placeholder, for example "Banner Promo" or "600 × 400". |
| **Background** | The image's base color. Use the color picker or a color code such as #1c1c1e. |
| **Warna teks** (Text color) | The color of the text. Choose a color different enough from the background to be readable. |
| **Background transparan** (Transparent background) | Removes the base color in the local preview. Use SVG to keep a transparent result in this version. |
| **Auto-fit teks** (Auto-fit text) | Automatically adjusts the text size in the local preview. Still check very long text. |
| **Format** | The format included in the provider URL: PNG, JPEG, WebP, SVG, AVIF, or GIF. See the local download limitation in section 5. |
| **Font** | The typeface, for example Lato, Poppins, or Montserrat. |
| **Skala** (Scale) | A 1×, 2×, or 3× request in the provider URL; for example, a base size of 600 × 400 at 2× requests a raster twice as large. The local SVG preview keeps its base size. |
| **Perataan teks** (Text alignment) | Center, left, or right alignment in the local preview. |
| **Tukar** (Swap) | Swaps the width and height. |
| **Kunci rasio** (Lock ratio) | Keeps the width-to-height ratio when the Classic size is changed. |

**Color examples:** #ffffff is white, #000000 is black. Use the color picker if you're not used to these codes.

JPEG doesn't support transparent backgrounds. Choosing JPEG together with Background transparan (Transparent background) will be rejected by validation.

## 4. Using Prompt mode

Example: making a temporary illustration for a coffee shop banner.

1. Choose the **Prompt** tab.
2. Choose the **Landscape 16:9** preset or enter Width 1280 and Height 720.
3. Replace the example in the Prompt field with the description you want:

   > Cozy coffee shop interior, morning sunlight through the window, wooden counter, warm brown and cream colors, no text.

4. Choose **Style: Photographic**.
5. Use **Seed: 1** for a first try.
6. Press **Generate Prompt**.
7. Wait until the result image is actually visible. "Generating" or "Processing" text from the provider is not the final result yet.
8. If it succeeds, use Download or copy the result URL.

In Placeholder, **Generate Prompt requests an image from the provider**. This differs from the Generate Prompt button in [Prompt Studio](promptgenerate.md), which produces instruction text.

### Style options

| Style | The look requested |
| --- | --- |
| **Photographic** | A photo-like look. |
| **Artistic** | An artwork look. |
| **Anime** | An anime-style illustration. |
| **Oil Painting** | An oil painting style. |
| **3D Render** | A three-dimensional render look. |
| **Cartoon** | A cartoon illustration. |

### What is a Seed?

A seed is a variation choice in the image request. In this tool its value can only be **1, 2, or 3**. The **Acak seed** (Random seed) button picks one of those three numbers.

To ask for a variation, change the seed and run it again. Using the same seed is not an absolute guarantee of an identical result; the public service may change or store its results on its own.

The Prompt field is limited to **1,000 words**, not 1,000 characters. The interface cuts off text beyond that limit. Check the last sentence if you paste a long description.

## 5. Tell the preview, the local file, and the public URL apart

There are three things that look similar but work differently.

### The Classic local preview

The preview is made in the browser and can appear without waiting for the image service. Alignment, Auto-fit, and transparency apply to this preview.

**Grid**, **Gelap** (Dark), and **Terang** (Light) only change the background of the viewing area. Switching from Grid to Dark doesn't change the image file's colors.

### The file from the Download button

In the audited source version, Classic saves the local SVG preview. Choosing PNG in the Format list doesn't make that button download a PNG. The file name follows the Nama file (File name) field, while the extension follows the file actually downloaded.

If there's already a Prompt result, the Download button saves the result image file received. If the service restricts direct fetching, the page may open the original source instead.

### The original URL and Open Original

The Classic URL points to placeholderimage.co. The Prompt URL points to placeholdr.dev. These links are useful for placing the image on a website or sharing it.

**The Classic URL doesn't carry all of the local preview settings.** Alignment and Auto-fit aren't included in the URL. When Background transparan (Transparent background) is on, the tool doesn't produce a Classic URL.

Therefore:

- To save the local preview as it looks, use Download SVG.
- To try a PNG/JPG/WebP format from the provider, choose the Format, copy the original URL or press Open Original, then save the result from that source if available.
- Compare the source result with the preview; the typeface and layout may differ.
- Don't just rename an SVG file's extension to PNG; that doesn't change the image format.

## 6. Result buttons and when to use them

| Button | What gets copied or opened |
| --- | --- |
| **Download** | The result file currently available; note the Classic remark above. |
| **Copy URL** | The image link from the public service. |
| **HTML** | An image tag snippet for an HTML page. |
| **Markdown** | An image embed text snippet for a Markdown document. |
| **CSS** | A background-image setting snippet for a website's CSS. |
| **SVG** | The local SVG code in Classic mode; this button isn't available for Prompt. |
| **Open Original** | Opens the image's source URL in another tab. |
| **Refresh** | Re-requests the Prompt result with the existing configuration. |
| **Batalkan** (Cancel) | Stops the wait or request the page is handling. |

**Nama file** (File name) sets the download name. Changing it doesn't change the image content or the service address.

**Recent** contains configurations saved in that device's browser. Prompt requests are recorded when they run. Choosing a Prompt entry fills its settings back in; press Generate Prompt if you want to run it. **Clear** clears the local history.

## 7. If the result isn't right yet

| Problem | What to check |
| --- | --- |
| Classic has no Create button | Normal: the Classic preview updates automatically after settings change. |
| The downloaded image is SVG even though PNG was chosen | Behavior of the audited version; use the source URL to try the provider's format. |
| The URL is empty when transparent | Transparency is only available in the local result, not the Classic URL. |
| The preview and Open Original look different | Not all local settings are carried to the CDN URL. Use the result that suits your need. |
| The size is rejected | Classic 10–4,000; Prompt 128–2,048 pixels per side. |
| The seed is rejected | Enter 1, 2, or 3. |
| The provider is still Processing | Wait; if the time limit runs out, use Refresh or Open Original. |
| Copy URL/HTML/CSS doesn't work | Make sure there's a result URL. These options can't use a preview that exists only locally. |
| The text is too long or hard to read | Shorten the text, enlarge the area, and use colors with enough contrast. |

Prompt mode is sent as part of the public service's URL. Use descriptions that are appropriate to share with that service.

[Audited interface source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/placeholder-studio.js) · [List of all tools](README.md)
