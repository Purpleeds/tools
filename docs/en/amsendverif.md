# AM Send & Verif

Sends a **magic link**, an Alight Motion authentication link received by email, and then submits that link for verification through the service connected to Nexora.

This tool handles the authentication flow. A verification result does not automatically prove that a Premium subscription is active.

## Before you start

Use the email address you actually use for Alight Motion, with an inbox you can open. Log in to Nexora if asked.

## Stage 1 — Kirim Magic Link (Send Magic Link)

1. Fill in **Alamat email** (Email address) in the correct format.
2. Press **Kirim Magic Link** (Send Magic Link) once.
3. Wait for the service's message.
4. If the service accepts the send, check your inbox and spam folder.
5. Copy the full authentication link from the correct email.

Don't resend just because the email hasn't appeared within a few seconds. Nexora applies a delay between sends; if it times out, check your inbox first, because the service may already have accepted the request.

## Stage 2 — Verifikasi Link (Verify Link)

1. Make sure **Email yang digunakan** (Email used) is the same as the email in stage one.
2. Paste the full magic link into the **Magic link** field.
3. Use a valid HTTPS link from the email, not the email's subject or truncated text.
4. Press **Verifikasi Link** (Verify Link).
5. Wait for and read the result status.

The magic link is cleared from the form after the request. If you need to try again, make sure you have a link that is still valid and follow the service status.

## Results and their limits

The result panel explains whether the request was accepted or failed, based on a correctly formatted response from the service. An HTTP 200 response alone does not prove the whole account process is complete.

The tool doesn't display an ID token, refresh token, or credentials. There is no step for copying the resulting token elsewhere.

**Ulangi proses** (Restart process) clears the input and returns to the start of the flow.

## If it fails

- Email empty or wrongly formatted: fix it before sending.
- Link empty or not HTTPS: copy the full link from the email.
- Too many requests: wait for the delay you're told.
- Provider not available or timed out: check the message and your inbox first; don't press repeatedly.
- Status accepted by the service: check the authentication state through the legitimate Alight Motion flow if needed.

[Alight Motion Premium 1 Tahun](alightpremium.md) (1 Year) is a separate tool, not another name for this feature.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/am-send-verif.js) · [List of all tools](README.md)
