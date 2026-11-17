# Nexora Prompt Studio

Helps turn ideas into fuller, more focused AI instructions. Its main output is **prompt text**, not an image or video. You then copy that prompt into the image or video generation service you use.

A **prompt** is an instruction for an AI. A **reference** is an example image. A **blueprint** is a breakdown of the visual plan, such as the subject, setting, lighting, and composition.

## 1. First try: make a simple image prompt

1. Choose the **Image** mode.
2. In **Apa yang ingin kamu buat?** (What do you want to make?), write:

   > A poster for an iced milk coffee drink to promote a coffee shop. The coffee bottle is in the middle of a wooden table, warm morning light, brown and cream colors. Leave the top area free for a title.

3. Choose **Style: Photorealistic** or leave it on **Auto**.
4. Choose **Aspect ratio: 4:5** for a portrait poster.
5. Leave the settings on **Basic**. You don't need to open all the settings.
6. In **Target profile**, choose **Universal** if you don't know which model you'll use yet.
7. Choose the **Language** you want the prompt written in.
8. Press **Generate Prompt**.
9. Read the **Production Prompt** result, then press **Copy** or **Copy Prompt**.
10. Open [Nexora AI Image](aiimage.md) or the image service of your choice, paste the prompt, then create the image there.

The last step matters: pressing Generate Prompt in this studio doesn't produce an image yet.

## 2. Choosing a workflow

Six main options appear as buttons. The others are under **Workflow lainnya** (Other workflows). Choose based on the job you want to do, not just the name of the target AI.

| Workflow | Purpose | Reference images |
| --- | --- | --- |
| **Image** | Write an image prompt from an idea. | Not used. |
| **Video** | Write motion directions from an existing image. | 1–4 images. |
| **Edit** | Write directions for keeping and changing parts of an image. | 1–4 images. |
| **Reverse** | Read an image into a description and prompt. | 1–4 images. |
| **Product** | Plan product photos or ad material. | Optional, up to 4. |
| **Character** | Write directions with consistent character traits. | 1–4 images. |
| **Text → Video** | Design a video scene from text. | Not used. |
| **Image Edit** | Write image-editing instructions. | 1–4 images. |
| **Style Transfer** | Separate the subject image from the style example you want to imitate. | 2–4 images, including a reference with the Style role. |
| **First → Last** | Plan a change from a starting frame to an ending frame. | Exactly 2 images: Start Frame and End Frame. |
| **Storyboard** | Plan several connected scenes. | Optional, up to 4. |
| **Photography** | Create a photography prompt with camera and lighting directions. | Optional, up to 4. |
| **Anime** | Write anime illustration directions. | Optional, up to 4. |
| **3D / CGI** | Write directions for renders, materials, and 3D objects. | Optional, up to 4. |
| **Architecture** | Plan images of buildings or interiors. | Optional, up to 4. |
| **Enhance Prompt** | Clarify a prompt you already have. | Not used. |
| **Convert Target** | Adapt a prompt for another AI service. | Not used. |
| **Prompt Debugger** | Check a prompt for conflicts or gaps. | Optional, up to 4. |

If a mode requires images, the button can't be used until the image requirement is met. The note near the button explains what's missing.

## 3. Adding references correctly

1. Choose a workflow that supports references.
2. Press **Tambah** (Add) or the **Tap atau jatuhkan gambar di sini** (Tap or drop an image here) area.
3. Choose JPG, PNG, or WebP. Generally at most four images; First → Last mode takes only two.
4. Each source file can be at most 12 MB. The studio shrinks local images before sending; if it's still too large, choose a lighter file.
5. Check the images that were added, then set their role using the option on the image card.
6. Write directions explaining how the images relate to the result you want.

| Reference role | What it means |
| --- | --- |
| **Subject** | The person, product, animal, or object that is the main subject. |
| **Style** | A reference for the image style, colors, or visual treatment. |
| **Composition** | A reference for object placement and viewpoint. |
| **Environment** | A reference for the place or background atmosphere. |
| **Start Frame** | The view that starts the video in First → Last. |
| **End Frame** | The view that ends the video in First → Last. |

Style Transfer example: the first image is a photo of a shoe, the second a watercolor illustration. Give the shoe the **Subject** role and the illustration the **Style** role. Write "keep the shoe's shape, use watercolor brushstrokes like the style reference."

Images only serve as material for analysis when composing the prompt. If you later use another AI, that service may still need the same images uploaded again.

## 4. What do you need to fill in?

### The idea and presets

The idea field is limited to 4,000 characters. For text-based workflows, enter at least three characters; ideally a clear sentence.

An easy pattern:

> What the subject is + what it's doing + where + visual style + lighting + things that must be kept or avoided.

Presets such as **Portrait**, **Commercial**, **Perfume**, or **TikTok 9:16** give a starting direction. A preset doesn't replace explaining your idea. Still read the Style and Aspect ratio options after choosing one.

### Style and Aspect ratio

**Style** sets the visual direction: for example Photorealistic for a photo look, Anime for anime illustration, or Vector Art for a vector graphic style.

**Aspect ratio** sets the frame's shape. Use 1:1 for square, 4:5 for a portrait poster, 9:16 for phone video, or 16:9 for landscape video. Auto lets the composition adapt to the context.

Choosing Vector Art produces vector-style directions; it doesn't guarantee the target image generator outputs an SVG file. To convert an image into SVG, use [Vecto](vecto.md) or [AUTO TRACE](imagevectorizer.md).

## 5. Basic, Advanced, and Pro

All three open groups of settings. Start with Basic, then open the other groups only if needed. Some controls only appear in certain workflows.

### Basic: the essentials

| Field | How to use it |
| --- | --- |
| **Subject** | The type of subject: person, character, product, vehicle, building, and so on. Auto is fine if you don't need to be specific yet. |
| **Detail** | Clean for tidier directions, Balanced for a middle ground, Detailed or Maximum for more detail. |

### Advanced: visual direction

| Field | Simple explanation |
| --- | --- |
| **Shot** | How close the camera is: Close-up for faces or details; Full body for the whole body; Wide for a large environment. |
| **Lighting** | The light source or atmosphere: Natural, Golden hour, Studio, Neon, and other options. |
| **Composition** | How the image is arranged: Centered for a subject in the middle; Rule of thirds for off-center placement; Negative space for empty space. |
| **Mood** | The atmosphere, for example calm, cheerful, tense, or luxurious. |
| **Palette** | The main colors, for example "cream, coffee brown, warm white". |
| **Preserve / Do not drift** | The parts of the reference you want kept: face, pose, clothing, background, and so on. |
| **Transform** | The parts you want changed: style, place, lighting, clothing, and so on. |

Avoid choosing the same part to keep and to change without explanation. For example, don't ask for the clothing to stay the same and also be completely replaced.

In **Product** mode, extra settings are available:

- **Product type:** the kind of product, for example perfume or shoes.
- **Output variant:** the direction of the result, such as Product Hero, Social Ad, or Clean E-commerce.
- **Pedestal / support:** the base or stand for the product.
- **Reflections / material:** reflections and surface properties.
- **Background:** the background you want.
- **Safe zones:** empty space for a headline or logo. This prepares the space; it doesn't automatically place a logo.

Video workflows have motion directions:

- **Subject motion:** the subject's movement, for example walking or turning their head.
- **Camera motion:** the camera's movement. Pan means turning horizontally; Dolly in means moving closer with the camera; Orbit means circling the subject.
- **Environment:** movement in the surroundings, for example rain, wind, or smoke.
- **Speed:** the speed of movement you want.
- **Stability:** a static, stable, handheld, or dynamic camera.
- **Duration intent:** the duration you want stated in the prompt.
- **Motion strength:** how strong the motion directions are.

The duration and motion here are **part of the instruction text**. What's actually possible depends on the video service where you run the prompt.

### Pro: specialized details

- **Camera angle:** for example "eye level" for a view at eye height, or "low angle" for a view from below.
- **Focal length:** for example "50mm" to suggest a lens character.
- **Aperture / depth:** for example "f/2.8, soft background" for depth of field.
- **Realism:** how realistic or stylized it looks.
- **Exact text:** text that must be included exactly in the instruction.
- **Font character:** the nature of the lettering, for example bold sans-serif.
- **Placement:** where the text goes, for example the top area.
- **Timeline builder:** directions per time segment for video workflows. Turn it on, then fill in the scenes in the available time fields.

Exact text helps keep the spelling right in the prompt. The target image AI can still draw letters wrongly; check the final result.

## 6. Target profile, Language, and Negative prompt

**Target profile** tells the studio how to compose the prompt:

- For images: Universal, Midjourney, FLUX, Stable Diffusion / SDXL, or Ideogram.
- For video: Universal Video, Runway, Veo, Kling, Hailuo, or Luma.

Choose the target that matches the service you'll use. Choosing a target doesn't mean the studio has connected an account or run a generation on that service.

**Language** chooses the language of the resulting prompt: English or Bahasa Indonesia. You can still write your initial idea in whatever language you understand.

**Negative prompt** contains things you want to avoid, for example "random text, duplicate objects, blurry image". This option only appears for compatible targets. Copy it into the target service's negative field if that service has a separate field.

## 7. Examples of more complex jobs

### Writing video directions from a product photo

1. Choose **Video** and add one product photo.
2. Write:

   > The camera slowly moves toward the perfume bottle. Keep the bottle's shape, label, colors, and background arrangement. Add subtle light reflections, without changing the product.

3. In Advanced, choose **Camera motion: Dolly in**, **Subject motion: Still**, and speed **Slow**.
4. Choose the aspect ratio and the Target profile of the video service you'll use.
5. Generate Prompt, copy the result, then use it together with the product photo in that video service.

### Planning two frames

1. Choose **Workflow lainnya → First → Last** (Other workflows → First → Last).
2. Add two images: the starting state and the ending state.
3. Make sure the **Start Frame** and **End Frame** roles are correct.
4. Explain how the change happens, including the parts that must stay consistent.
5. Generate Prompt, then read the Motion Plan and Continuity Notes sections if available.

## 8. Reading and using the result

| Result section | What it's for |
| --- | --- |
| **Production Prompt** | The main text you copy into the target AI. |
| **Negative Prompt** | Directions to avoid, if the target supports it. |
| **Parameters** | Settings composed for the target. |
| **Visual Blueprint** | A breakdown of the subject, place, camera, lighting, color, and style. |
| **Motion Plan** | A movement plan for video, if any. |
| **Continuity Notes** | Reminders to keep identity, clothing, background, or direction of motion consistent. |
| **Warnings & Diagnostics** | Conflicts or things to check. |
| **Meaningful Variants** | Alternative prompts; each can be copied. |
| **Prompt Quality** | A score of how complete the prompt's elements are, not a likelihood of being correct or a guarantee of image quality. |

**Improve**, **More Cinematic**, **More Realistic**, and the other Refine options recompose the prompt. Use them when you actually want a change; each one is a new AI request.

To save:

- **Copy Prompt:** only the main prompt text.
- **Copy All:** the combined text of the available results.
- **TXT / Markdown / JSON:** a download in the chosen format.
- **History:** up to 20 results in that device's browser, with Open, Duplicate, and Favorite.

History and request exports don't store the reference image contents. **Duplicate** fills the idea and workflow back in; it doesn't fully restore all the settings and all the images.

## 9. If the button isn't active or no result appears

- **Tulis ide sedikitnya 3 karakter** (Write an idea of at least 3 characters): complete the idea field.
- **Tambahkan reference** (Add a reference): upload the number of images the workflow requires.
- **Tetapkan Start Frame dan End Frame** (Set Start Frame and End Frame): fix the roles of the two images.
- **Tambahkan reference dengan role Style** (Add a reference with the Style role): change one reference's role to Style.
- **Reference terlalu besar** (Reference too large): choose a lighter image; accepted formats are JPG, PNG, and WebP.
- **Engine belum dikonfigurasi** (Engine not configured yet): the AI service on Nexora isn't ready; changing the prompt content doesn't fix that configuration.
- **There's a prompt but no image yet:** copy the prompt into [AI Image](aiimage.md) or the target service to create the image.

[Audited interface source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/prompt-generator.js) · [List of all tools](README.md)
