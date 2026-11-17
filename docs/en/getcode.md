# Get Code HTML

Fetches the HTML of a public page, shows a preview, and checks the assets it finds. There's also **SiteGrabber** for capturing one page or larger parts of a website as a download package.

## Choose the job you need

| Need | Option |
| --- | --- |
| You only want to view or save the HTML of one URL. | **Extract HTML**. |
| You want to check the asset links and endpoints found. | The static report and **Run Live Audit**. |
| You want a package of the page with the assets the service can capture. | **Capture via SiteGrabber X**. |

A page's publicly readable HTML is different from backend code or a database. This tool doesn't give you server content that hasn't been published.

## Fetching HTML

1. Enter the page address in the URL field.
2. Press **Extract HTML**.
3. Wait for the success status and for the code to appear.
4. Use **Copy HTML** or **Download HTML**.
5. Press **Preview** if you want to see the result.
6. Choose Desktop, Tablet, or Mobile to check the preview size.

**Clear Result** clears the result. History can help you repeat URLs you've checked before.

Example: enter the address of a sample page of your own, extract it, then see whether the main elements and asset links appear.

## Understanding the preview and report

The preview runs the HTML in a restricted space. It may look different if the page depends on a login, special JavaScript, assets that can't be fetched, or the source site's rules.

The static report shows the assets and endpoints found in the HTML. **Run Live Audit** performs limited network checks on those findings, for example HTTP status, redirects, file type, and cross-domain responses.

A detected endpoint is not proof that you can access all of its data. Use Copy JSON or Download JSON to save the available report.

## SiteGrabber: a website package

1. Use a target URL that you're actually allowed to capture.
2. In the SiteGrabber section, choose a **Capture Mode**:
   - **Maximum Fidelity · Full Website:** a more thorough capture request.
   - **Single Page · Faster:** focuses on one page.
3. Tick the target permission statement on the form.
4. Press **Capture via SiteGrabber X**.
5. Wait for the job to finish and read the Pages, Assets, Failed, and Size metrics.
6. Use **Download Clone ZIP**.
7. Save the report through Copy Report JSON or Reports ZIP if needed.

The Failed count needs checking. A successfully created ZIP doesn't mean every page, asset, or site function was captured.

## If it doesn't work yet

- The URL must be an accessible HTTP/HTTPS page.
- If you only need the HTML, don't start a full website capture.
- If SiteGrabber isn't available yet, its status needs to be restored by the related service; Extract HTML is a different flow.
- Login pages, apps that require private data, and backend functions don't automatically become a complete offline website.
- If the preview looks different, check the assets and the failure report before assuming it matches the source exactly.

For SEO, speed, and security checks on a page without fetching a website package, use [Web Intelligence](webintel.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/get-code.js) · [List of all tools](README.md)
