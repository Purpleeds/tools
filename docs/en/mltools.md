# ML Tools Nexora

A collection of Mobile Legends utilities with three menus: script search, a win-rate calculator, and MLBB profile lookup.

## Script ML

1. Choose **Script ML**.
2. Fill in **NAMA HERO** (HERO NAME), for example "Fanny".
3. Press **CARI SCRIPT** (FIND SCRIPT).
4. Read the result links and the sources shown.

If the main provider isn't available, the page may show alternative web search links. That is not proof that a script file is available or has been downloaded.

This tool shows search results; it doesn't automatically install scripts into the game or vouch for the contents of external links.

## Winrate: calculate a win target

1. Choose **Winrate**.
2. Fill in **TOTAL MATCH**.
3. Fill in **WR SEKARANG** (CURRENT WR) as a percentage.
4. Fill in the **TARGET WR** you want to reach.
5. Press **HITUNG WINRATE** (CALCULATE WINRATE).

Example: 100 matches, current WR 50, target 60. If every following match is a win, you need 25 more wins to reach 75 wins out of 125 matches.

If there's a new loss, recalculate with the latest total and WR. If the target is already reached or the input doesn't make sense, read the result note rather than forcing a number.

**Note:** the FF Tools calculator asks for the number of wins, while this ML menu asks for the current WR percentage.

## Stalk MLBB

1. Open **Stalk MLBB**.
2. Fill in **USER ID** and **ZONE ID** according to the player's profile.
3. Press **CEK AKUN** (CHECK ACCOUNT).
4. Read the available profile information.

The Zone ID is the account's server/zone code, usually shown together with the User ID. Don't merge them into the same field; the form provides two fields.

## Results and issues

Account data depends on the provider. If nothing is found, check for typos in the User ID and Zone ID. If only alternative search links are available in Script ML, treat them as alternative searches, not verified file results.

This feature doesn't change statistics, add wins, or log in to a game account.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/apps/ml-tools/index.html) · [List of all tools](README.md)
