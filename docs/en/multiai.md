# Nexora Multi-AI

Compare answers from several AIs, or use image, audio, and utility services from one page. There are four tabs: **Chat**, **Image**, **Audio**, and **Tools**.

## Chat: one question for several AIs

1. Choose the **Chat** tab.
2. Open the AI picker through the name chips or the available AI selection button.
3. Choose the services you want to compare. Start with two AIs so the results are easy to read.
4. Write your question in the prompt field.
5. Send it. On desktop, Enter sends; Shift+Enter makes a new line.
6. Watch each AI's card. Some may finish first.
7. Tap a card to read the full answer.

Example:

> Explain the difference between PNG and SVG images for beginners. Give examples of when each one is used.

Don't assume the AI count label in the catalog means they're all active at once. The options follow the registry that's loaded; the interface limits Chat selection to 14 services, and jobs may be queued.

## Reading the status and adjusting the view

- **Ready:** ready to take a question.
- **Queued:** waiting its turn to be processed.
- **Processing:** composing an answer.
- **Complete:** the answer is available.
- **Rate Limited:** the service is limiting requests.
- **Unavailable / Failed:** the request to that service hasn't succeeded.

Use **+ / −** to zoom and **Fit View** to show the card layout. On a phone or in some layouts, extra actions are under the **•••** button.

**Compare** helps you see answers side by side. **Copy All** copies the available results. **Best Answer** is your own marking, not proof that the answer is definitely correct.

**Retry** tries that card's service again. **Stop All** stops waits still running on the page; answers that have already finished can still be read. One failure doesn't mean all the other AIs failed.

## Image, Audio, and Tools

1. Choose the tab you need.
2. Choose a provider from that tab's list.
3. Fill in the form that appears; required fields must be filled.
4. Press **Run** on the chosen service.
5. Check the result, then use Open / Download or Copy URL if available.

Forms differ between services. Some ask for a prompt, some ask for an image URL, and some ask for special data. For image URLs, use an image file link that opens directly, not a post page.

Results can be text, images, audio, video, or structured information. The Image tab doesn't use a Puter account the same way as [Nexora AI Image](aiimage.md); they are different tools.

## If there are no services or results yet

If it says there's no active provider yet, that tab has no usable service at the moment. If only one card fails, read the message on that card and use Retry as needed. Save important results before switching or closing the page; this session isn't a permanent conversation archive.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/multi-ai-layout.js) · [List of all tools](README.md)
