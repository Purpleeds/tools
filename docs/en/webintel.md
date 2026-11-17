# Nexora Web Intelligence

Checks a website for SEO, security, performance, accessibility, and recognizable technologies. Use it to find out which parts need review, not as a certificate that a site is completely safe.

## How to use it

1. Enter the website address in the **SCAN WEBSITE** field.
2. Choose **Standard Scan** for a first try.
3. Press **SCAN WEBSITE**.
4. Wait for the report or a failure message.
5. Open the Overview, Findings, SEO, Security, Speed, and Stack tabs.
6. Start with the priority findings, then check their details.

Example: use a page of your own website to see the page title, security headers, and detected technology information.

## Standard Scan and Deep Intelligence

**Standard Scan** checks server/page information that can be fetched through a faster flow.

**Deep Intelligence** adds checks such as Lighthouse and reputation, depending on whether the supporting services are available. This option can take longer or not produce every section when a service isn't available yet.

Don't treat a section that hasn't been tested as a perfect score. Read the notes on which data is available, limited, or failed.

## Reading the result tabs

| Tab | Focus |
| --- | --- |
| **Overview** | A summary of the site's state. |
| **Findings** | Findings and check priorities. |
| **SEO** | Page elements related to how readable it is for search engines. |
| **Security** | Headers and security signals that can be checked. |
| **Speed** | The performance information that was obtained. |
| **Stack** | Technologies detected from public signals. |

If a technology isn't detected, that doesn't mean it isn't used. If a header is missing, read the impact of that finding before changing your configuration.

## Common issues

**Batalkan** (Cancel) stops the page from waiting. **New Scan** or Kembali ke scanner (Back to scanner) starts a new input.

Websites that block checks, require a login, or are currently unavailable may give limited results. If Deep fails, Standard is a check with a different scope, not a substitute for proof that all the Deep checks passed.

To fetch HTML code or a page package, use [Get Code HTML](getcode.md).

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/web-intelligence.js) · [List of all tools](README.md)
