# AI Image Eksperimental (Experimental AI Image)

A place to try **five groups of services** that do different jobs. Some create images over the internet; others analyze or process images locally in the browser.

Don't assume every option creates a new image from text.

## Choose a group based on your need

| Group | What it does | Where it runs |
| --- | --- | --- |
| **AI Horde** | Creates images through community workers; can use a starting image if that mode is available. | Online service. |
| **Pollinations** | Creates images through a public Classic service. | Online service. |
| **Transformers** | Classification, object detection, segmentation, or depth estimation. | Browser. |
| **MediaPipe** | Face/hand/pose detection, effects, or separating objects/people. | Browser. |
| **ONNX** | Object masks, object focus with a blurred background, or special upscaling. | Browser. |

## First try

To try image generation, choose AI Horde or Pollinations and write a short description. To separate a person from the background, choose MediaPipe and the person segmentation task.

Image files for this workspace are limited to **8 MB** and **16 million pixels**. Large images may be scaled down depending on the mode and the device. This differs from Vecto, which keeps its original input.

## AI Horde: a new image

1. Choose **AI Horde**.
2. Load the model list with the model button if needed.
3. Choose an active model that is available.
4. Write a prompt, choose a size, and check Steps.
5. If using a starting image, turn on the related option and upload the image.
6. Press **Generate gambar** (Generate image).
7. Wait for the queue and processing to finish, then check and download the result.

**Steps** is the number of stages the model works through. The form allows 4–30, with a default of 20. A higher value doesn't guarantee a better-matching image and can add time.

Example:

> A quiet Indonesian village after rain, warm afternoon sunlight, detailed illustration, no text.

The community queue can be long, or a model may be unavailable. A queue status doesn't mean the image has been created yet.

## Pollinations: a public Classic service

1. Choose **Pollinations**.
2. Fill in the prompt and the settings shown.
3. Run Generate gambar (Generate image).
4. Wait for the final image; save the result if available.

This mode uses a single model option from the provider, not a list of many models to choose from freely. This integration enforces a minimum gap of **45 seconds per IP**. The provider's logo may appear, and results may be stored in the provider's public cache. If you see 401/403 or Authentication Required, that anonymous service is currently unavailable for the request.

## Transformers: reading what's in an image

1. Choose **Transformers**.
2. Choose a task, then upload an image.
3. For segmentation, set the target if that field is shown.
4. Press **Proses di perangkat** (Process on device) and wait for the model to load.
5. Read the analysis result or check the visual output.

| Task | How to read the result |
| --- | --- |
| **Klasifikasi gambar** (Image classification) | Estimated labels for the image's main content. |
| **Deteksi objek** (Object detection) | Objects with their positions or boxes. |
| **Segmentasi dan mask objek** (Segmentation and object mask) | The pixel area estimated to belong to the object. |
| **Estimasi depth relatif** (Relative depth estimation) | An estimate of near and far parts; not a distance measurement in meters. |

## MediaPipe: faces, poses, and masks

Choose a task before processing:

- **Deteksi wajah / filter kacamata** (Face detection / glasses filter): finds faces or places an effect.
- **Face landmarks:** shows facial reference points.
- **Hand landmarks:** hand reference points.
- **Pose landmarks / efek neon** (neon effect): points or effects that follow the body's pose.
- **Segmentasi orang** (Person segmentation): separates the person area into a transparent PNG.
- **Mask objek — tap pada gambar** (Object mask — tap on the image): tap the object in the preview first, then press Process.

These options process still images; they don't automatically open the camera or create live video.

## ONNX: masks, focus, or upscaling

1. Choose **ONNX**.
2. Choose a task and add an image.
3. Run Proses di perangkat (Process on device).
4. Compare the results before downloading.

**U²-NetP mask** tries to separate the object. **Fokus objek** (Object focus) uses the mask to blur the background. **ESPCN** in this integration produces a 3x upscale from a source limited to 224 pixels per side; it is not a service for enlarging large photos with the original detail guaranteed to come back.

## Results and common issues

Use the comparison preview, then **Download** for images. A JSON download, if available, stores information about the analysis result, not an image.

Local models are downloaded when needed. Don't close the tab while loading or processing. If memory runs out, use a smaller image and close heavy tabs. Cancel if you want to stop waiting on the page. A cloud failure does not automatically switch to a local model, because the two may do different jobs.

For more focused options, use [AI Image](aiimage.md) for image generation or [Smart Cutout](smartcutout.md) for selecting objects.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/ai-image-experimental/workspace.mjs) · [List of all tools](README.md)
