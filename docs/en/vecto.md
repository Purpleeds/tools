# Vecto

Converts PNG, JPG, or WebP into SVG through the **original Vecto 0.4.4 engine** on Nexora's VPS. Vecto has its own card and page at **/vecto**, separate from AUTO TRACE.

## Getting started

1. Open the **Vecto** card and log in if asked.
2. Choose or drop an image of at most 12 MB.
3. Start with **Style: Auto**, **Detail: Medium**, and **Warna: Auto** (Colors: Auto).
4. Leave the advanced engine parameters at their initial values.
5. Press **Buat SVG** (Create SVG) once.
6. Wait for the finished status and for the Vector result to be available.
7. Compare Original and Vector, then download the SVG through the result button.

An easy practice example: a simple PNG logo with three or four colors. Once you understand the flow, try a more complex illustration.

## What the main settings mean

| Setting | Purpose |
| --- | --- |
| **Style: Auto** | Lets the engine choose the handling that suits the input. |
| **Crisp** | A style option for trying sharper edges or shapes. |
| **Blended** | A style option for trying blended shapes or colors. |
| **Photo** | A style option provided for photo images. |
| **Detail: Low / Medium / High** | The level of detail requested from the engine; start with Medium, then compare as needed. |
| **Warna: Auto** (Colors: Auto) | The engine decides the colors within the Auto limit you set. |
| **Warna: 1–64** (Colors: 1–64) | Requests a specific number of colors. More colors doesn't always make the file simpler. |

The Style and Detail options are engine parameters, not a change of engine version. Input is processed without resizing or re-encoding by this Vecto integration.

## Original engine parameters

Open **Parameter engine asli** (Original engine parameters) if you need more control:

- **Auto: maks. warna** (Auto: max. colors): the color limit when using Auto; range 1–64, with an initial value of 16.
- **Seed:** the starting number for processes that involve variation; initial value 1. Change it only when you want to compare variations.
- **Geometri: Kurva asli** (Geometry: Original curves): the normal option for curved results.
- **Poligon (debug)** (Polygon (debug)): a polygon shape option for special checks; you don't need it for initial use.
- **Epsilon poligon** (Polygon epsilon): a polygon simplification parameter; the initial value of -1 follows the engine's default handling.

Raising every parameter at once makes comparison hard. Change one thing, run it again, then check the shapes and size of the result.

## Using the preview

- **Original / Vector:** switches between the source image and the SVG result.
- **+ / −:** zooms the view in or out.
- **Fit:** fits the view to the preview area.
- Drag the preview to see specific parts when zoomed in.

Moving and zooming the preview doesn't change the content of the downloaded SVG. The checkerboard background helps you check transparency; that pattern isn't part of the result image.

## Saving and solving issues

Download the SVG before pressing **Bersihkan** (Clear) or leaving the page. The result file uses the SVG from the engine, whose identity and hash have been checked.

If Buat SVG (Create SVG) isn't active yet, make sure an image is chosen, the service is configured, and no job is still running. If the server is busy or limits requests, wait your turn. If it times out or the result hash is rejected, the request hasn't produced usable output; read the status and try again once the cause is resolved.

**Batalkan permintaan** (Cancel request) stops the browser from waiting; don't assume it always immediately stops all of the engine's work. If you want an XML result for Alight Motion, take the checked SVG on to [SVG → Alight XML](svgalight.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/vecto/page.mjs) · [List of all tools](README.md)
