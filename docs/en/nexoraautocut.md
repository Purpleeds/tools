# NEXORA Auto Cut

Separates parts of an image into several transparent PNGs and prepares an XML so those layers can be used in Alight Motion. The result works as material for cut-out animation; it doesn't automatically create full character motion.

## Prepare your material

- One character or object image with reasonably clear parts.
- A reference Alight Motion XML if you want to carry over timing and transform settings from a source project. This XML is optional.
- Alight Motion, for importing and working with the result.

## How to use it

1. Choose an image in the **Input** section.
2. If you have a reference XML, add it through **XML Alight referensi** (Reference Alight XML).
3. Note the **AI otomatis setelah upload** (Automatic AI after upload) option. If it's on, background removal may start once the image is added.
4. If it hasn't been processed yet, press **Auto Cut**.
5. Check the preview and the **Layer hasil** (Result layers) list.
6. If the mask isn't quite right, use **Edit manual / rapikan hasil** (Edit manually / tidy up the result).
7. Once the result is right, press **Download XML + PNG**.

The reference XML is used so that the workflow can keep the source's timing and transforms. This doesn't mean any XML project will fit; read the message if the source can't be processed.

## What do you get?

A single **ZIP** containing:

- An Alight Motion XML.
- Several transparent PNG files, one for each cut-out layer.
- Short instructions in the package.

The XML arranges the result layers into one group. Extract the ZIP, keep all the PNGs and the XML, then import the XML into Alight Motion. If the app asks for media, use the resulting PNGs from the same package.

## Example use

For a character with several clearly separated parts, run the cut, check the resulting layers, then animate each layer in Alight Motion. If two parts are merged in the original image, don't expect them to always be recognized as separate pieces.

## If the result isn't right yet

- If the background is still included, tidy up the mask before downloading.
- If part of the object went missing, restore that area with the manual editor.
- If there are no layers to export, recheck the image and the background removal result.
- If the image hasn't finished processing, wait for the final status before Download.
- After changing the input or making corrections, recheck the result you'll use.

To separate just one object into a single PNG, [Smart Cutout](smartcutout.md) may be simpler.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/nexora-auto-cut.js) · [List of all tools](README.md)
