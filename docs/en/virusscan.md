# Nexora Virus Scan

Checks URLs, files, hashes, domains, or IPs for suspicious traits **locally in the browser**. This is not a multi-antivirus cloud scan or a full internet reputation check.

A local check means the tool looks at traits that can be examined from the input, for example double extensions, file type, or URL structure.

## Choose a menu and run it

| Menu | Input | What's checked |
| --- | --- | --- |
| **URL** | An HTTP/HTTPS link. | Link structure, HTTPS, direct IPs, encoding, download extensions, and other traits. |
| **File** | A supported file, at most 32 MB. | Name/extension, file type, basic signature, and patterns in a sample. |
| **Hash** | MD5, SHA-1, or SHA-256. | Whether the hash format is valid; not a cloud malware list. |
| **Domain** | A domain name. | The name's structure and local traits that can be analyzed. |
| **IP** | IPv4 or IPv6. | Format and network classification. |

1. Choose the tab that matches your input.
2. Fill it in or choose a file.
3. Press **Analisis URL** (Analyze URL), **Analisis File** (Analyze File), **Validasi Hash** (Validate Hash), or the related menu button.
4. Read the risk level **together with the check details**.
5. Save it through Download JSON or Bagikan Ringkasan (Share Summary) if needed.

## How to understand the result

- **LOW:** few risk traits were found by this check; not proof that it's free of malware.
- **MEDIUM / HIGH:** there are traits that need further checking; not a definite verdict that the file is dangerous.
- **UNKNOWN:** can't be determined by the available checks.

Example: the name "foto.jpg.exe" can trigger a double-extension flag. Conversely, a normally named file can still be dangerous even if the local patterns don't find anything.

## Hashes specifically

Enter a correct hexadecimal hash:

- MD5: 32 characters.
- SHA-1: 40 characters.
- SHA-256: 64 characters.

A valid hash only means its structure is correct. The tool doesn't link the hash to a threat database, so its risk result stays UNKNOWN. **Validasi Hash** (Validate Hash) is not the same as "this file is safe".

## Limits to understand

Files aren't uploaded for this analysis and aren't run by the scanner. File analysis only uses the traits and samples it reads; it doesn't observe the program's full behavior or thoroughly unpack every archive's contents.

The URL menu doesn't automatically visit the whole site and check all the downloads on it. The IP menu also doesn't detect who personally owns that address.

If the format is rejected, check your input and the file limit. If it says the local engine failed to load, use Coba lagi (Try again) or reopen it once the assets are available. For files you're actually going to run, also use appropriate device security protection.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/apps/virus-scan/engine.js) · [List of all tools](README.md)
