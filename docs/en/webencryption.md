# Web Enkripsi V2 (Web Encryption V2)

Protects HTML with a password, or reopens an encrypted Nexora HTML file. Processing runs on your device; decrypted source is shown as text in Nexora.

## Encrypting HTML

1. Choose **Operasi: Enkripsi HTML** (Operation: Encrypt HTML).
2. Paste the original HTML into the editor or choose a file.
3. Fill in **Judul / nama file** (Title / file name).
4. Create a **Passphrase**, a long password of at least 12 characters.
5. Press **Enkripsi HTML** (Encrypt HTML).
6. Wait for the result, then use **Download HTML**.
7. Open the resulting file and test the password before sharing it.

Keep the original source and the password somewhere you control. Knowing the file name alone isn't enough to open the result without the password.

## Decrypting a Nexora file

1. Choose **Dekripsi file Nexora** (Decrypt Nexora file).
2. Upload or paste the encrypted Nexora HTML file/payload.
3. Enter the original password.
4. Press the decrypt button.
5. If it's valid, the source is shown as text and can be copied or downloaded.

This mode doesn't open every kind of encrypted HTML from other apps. Format support follows the Nexora formats it recognizes, including older formats the engine supports.

## Input and output limits

- The file picker accepts HTML, HTM, TXT, or JSON containing text source.
- The encryption limit is 5 MB; the decryption limit is 8 MB.
- The encryption result is a self-contained HTML file with a password-protected opening page.
- **Copy output** copies the result text.
- **Reset** clears or cancels the job the page is handling.

The password field on the form is called Passphrase: use a long, unique string of words, not the same sample text for every file. After a successful run, the password is cleared from the form.

## Example and issues

If you want to share an HTML page with team members, encrypt the file, test the result, then share the file and the password in a way that suits your needs.

If the browser says Web Crypto isn't available, use a modern browser and access Nexora over HTTPS. If decryption fails, check the file and the original password; changing the title or extension doesn't fix a wrong password.

Encryption protects the content while it's stored. People given the password can still read the source after opening it; this feature is no guarantee that recipients can't copy the source.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/web-encryption.js) · [List of all tools](README.md)
