# Nexora AI Image

A studio for creating new images, editing images, or creating images from visual references. There are four modes, and the steps differ depending on the mode you choose.

**Easiest way to start:** choose **Generate**, connect a Puter account, describe the image you want, use the recommended model, then press **Buat Gambar** (Create Image).

## 1. Setup: connect Puter

1. Open the **Nexora AI Image** card from the dashboard. Log in to Nexora if asked.
2. Wait until the model list and the connect button are ready.
3. Press **Hubungkan** (Connect) or the large **Hubungkan Puter** (Connect Puter) button.
4. Finish logging in in Puter's official window. Allow pop-ups if your browser blocks them.
5. Go back to the studio. The status will show the connected Puter account.

**Your Nexora account and your Puter account are different.** The Nexora login controls access to the tool; the Puter account provides the AI service and its usage allowance. Nexora membership does not automatically add Puter allowance.

If your first press only opened the login, check the settings again once connected and press the create button to start.

## 2. Choose the right mode

| Mode | Use it when | Images to prepare |
| --- | --- | --- |
| **Generate** | Creating a new image from text. | No image needed. |
| **Edit** | Changing an existing image. | One source image. |
| **Reference** | Creating a new scene using an image as a reference for a character, product, outfit, style, or atmosphere. | One reference image. |
| **Multi** | Combining references from several images. | At least two, at most as the studio indicates; the interface limits this to four images. |

The model list adapts to the mode. A model that appears in Generate does not necessarily support Edit or Reference. For example, Leonardo Lucid Origin in this catalog only supports Generate; Qwen Image supports a single reference, not Multi.

### Generate: a new image from text

1. Choose **Generate**.
2. Fill in **Ide gambarmu** (Your image idea) with the subject, place, style, lighting, and composition.
3. If you like, press one of the **Quick style** options.
4. Choose a model, aspect ratio, and quality.
5. Press **Buat Gambar** (Create Image) once and wait for the result.

Ready-to-try example:

> Product photo of a bottle of iced milk coffee on a wooden table, slightly blurred coffee shop background, morning light from the left side, warm colors, the bottle is the main focus, no extra text.

Easy starting settings: the **GPT Image 2.5 Flare** model if available, aspect ratio **1:1**, and the default quality. This is a starting point for experimenting, not a guarantee of a particular result.

### Edit: change specific parts of an image

1. Choose **Edit**, then add one image.
2. Use PNG, JPG, or WebP as allowed by the file picker; each file can be at most 15 MB.
3. In **Instruksi edit** (Edit instructions), explain what should change and what should stay the same.
4. Choose a model available in this mode.
5. Press **Edit Gambar** (Edit Image).

Example:

> Change the background to a light gray studio. Keep the person, face, clothing colors, pose, and camera position. Don't add new objects.

Sentences like "make it nice" are too broad. Instructions that name specific parts are easier to steer. AI results still need checking, including faces, text, hands, and product details.

### Reference: an image as a reference

1. Choose **Reference**, then add one image.
2. Describe the new scene you want to create.
3. State which elements should follow the reference.
4. Press **Buat dari Reference** (Create from Reference).

Example for a character image:

> Use the character in the reference image, keep their hairstyle and clothing colors. Create a scene of the character standing at a bus stop on a rainy night, cinematic lighting, full-body view.

Reference gives the AI a direction. This feature does not guarantee that every detail of the original image will be copied exactly.

### Multi: several references in one image

1. Choose **Multi**.
2. Add at least two images. Read the maximum count shown; the studio's limit may be lower than what the model can generally handle.
3. Note their order in the list: **Reference 1**, **Reference 2**, and so on.
4. Explain the role of each image in **Prompt komposisi** (Composition prompt).
5. Press **Gabungkan Reference** (Combine References).

Example:

> Use the character from the first image, the outfit from the second image, and the room atmosphere from the third image. Create one cohesive scene with natural light. Keep the identity of the character from the first image.

If you add the wrong image, remove it or use **Hapus semua** (Remove all), then add them again in the right order. Choosing a model with a lower reference limit can reduce the number of images the studio keeps; check the list before creating a result.

## 3. Understanding the settings

| Setting | What it means and how to choose |
| --- | --- |
| **Ide gambarmu / Instruksi edit / Prompt komposisi** (Image idea / Edit instructions / Composition prompt) | The text that is the AI's main instruction. At least 3 characters are required; the field is limited to 2,000 characters. |
| **Acak ide** (Random idea) | Helps fill in an example idea. If the field already contains text, the extra idea may be appended; reread it before running. |
| **Quick style** | Adds a style phrase to your text, such as Anime, Cinematic, Product Photo, or Minimal. You can edit the phrase directly in the prompt field. |
| **Model** | The AI engine that handles the request. Choose based on your needs and the models currently available. |
| **Lihat semua model** (See all models) | Opens extra options beyond the recommended cards. |
| **Rasio gambar** (Image ratio) | The image's shape: square, portrait, or landscape. It does not determine the scene's content. |
| **Quality** | A quality or size option passed to the model. The names and number of options differ between models; follow what's shown on screen. |

Aspect ratio guide:

- **1:1:** square, for example a profile picture or a square post.
- **3:4:** a portrait photo or illustration.
- **4:3:** a landscape image with plenty of width.
- **9:16:** vertical content such as Stories or phone wallpapers.
- **16:9:** a landscape image such as a thumbnail or a widescreen illustration.

Don't assume the labels **1K**, **high**, and **1 MP** mean the same thing. Each follows how its model works. The quality option also doesn't tell you the price or the allowance that will be used; that information comes from Puter.

### Choosing a model without memorizing them all

The short descriptions on the cards help you choose:

- **GPT Image 2.5 Flare:** a general starting point, labeled fast and balanced.
- **GPT Image 2.5 Sunburst:** a detail-oriented option.
- **FLUX.2 Klein 4B:** an option for artwork.
- **Gemini 3.1 Flash Image:** an option for long prompts and references.
- **Grok Imagine 2.0:** an option for creativity and composition.
- **Seedream 5 Pro:** an option for realism and detail.
- **Qwen Image:** an option for posters and text; still check the spelling.
- **Leonardo Lucid Origin:** design and illustration in Generate mode.

The catalog also includes **GPT Image 2** and **Seedream 5 Flash**. Flash only appears if the Puter service reports it as available. This list describes the options in the source; actual availability still depends on the service when you open it.

## 4. After the image appears

| Button | What happens |
| --- | --- |
| **Lihat penuh** (View full) | Opens a large preview. Close it with the close button, or Escape on desktop. |
| **Unduh** (Download) | Downloads the result that was created. The file format follows the image returned by the service. |
| **Buat lagi** (Create again) | Runs a new generation request with the current settings. This uses the AI service again. |
| **Edit gambar** (Edit image) | Sets the result as the source image in Edit mode. Write the changes, then run it when ready. |
| **Jadi reference** (Use as reference) | Sets the result as the reference in Reference mode. |
| **Buat variasi** (Create variation) | Sets the result as a reference and fills in a variation instruction. In this version the button only prepares the form; press the create button to run it. |
| **Edit prompt** | Takes you back to the prompt field so you can edit it. |
| **Salin prompt** (Copy prompt) | Copies the prompt of the last result, or the field's content if there is no last result yet. |

Save the results you want to use before closing the tool. The studio does not keep a permanent image project history in Nexora.

## 5. If it doesn't work yet

| Symptom | What you can do |
| --- | --- |
| The button is still preparing or Puter isn't available yet | Wait for the initial load; check your connection and ad blocker. |
| The login doesn't open | Allow pop-ups for the Nexora site, then press Hubungkan (Connect) again. |
| Asked to confirm your Puter email | Complete the confirmation through Puter. |
| Edit or Reference can't run yet | Make sure one valid image has been added. Multi needs at least two. |
| The model isn't visible after switching modes | Choose a model that supports that mode from the current list. |
| Not enough allowance | Check your Puter account's allowance. Pressing the button again doesn't add allowance. |
| Too many requests | Wait before trying again. |
| The prompt is rejected by AI rules | Change the request so it complies with the service's terms. |
| The result fails to download | Check your connection, then try Unduh (Download) from the result that is still shown. |

If a model is unavailable, the studio may try one compatible replacement model. Read the message about which model was actually used. This fallback does not apply to every type of error, such as an exhausted quota or a safety rejection.

**How it differs from Prompt Studio:** AI Image produces images. [Prompt Studio](promptgenerate.md) helps you write instruction text that you can then use in AI Image or other services.

[Audited interface source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/puter-image.js) · [List of all tools](README.md)
