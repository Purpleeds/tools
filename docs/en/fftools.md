# FF Tools Nexora

A collection of Free Fire utilities for finding players, viewing statistics, checking ban reports, calculating win-rate targets, and reading the account information that's available.

## Choose a menu

| Menu | What it needs | Output |
| --- | --- | --- |
| **Search** | Player name and region. | The players found. |
| **Stats** | UID, region, BR/CS mode, and match type. | The statistics the service provides. |
| **Ban Check** | UID, and region if asked. | The available ban status report. |
| **Winrate** | Total matches, number of wins, and a target percentage. | The additional wins needed. |
| **Stalk FF** | UID and region. | An available account summary or account intelligence. |

**UID** is the player's numeric ID. **Region** is the account's area/server; choose it according to the account, not where you're opening Nexora from.

## Searching and viewing statistics

1. To search, open Search, enter a name of at least three characters, choose the region, then **CARI PEMAIN** (FIND PLAYER).
2. For statistics, open Stats and enter the exact UID.
3. Choose **Battle Royale** or **Clash Squad**.
4. Choose the **Career**, **Ranked**, or **Normal** scope as needed.
5. Press **ANALISIS STATISTIK** (ANALYZE STATISTICS) and read the sections that are actually filled in.

Statistics for different modes shouldn't be treated as the same. Empty data may mean the provider doesn't supply that information, not that the value is definitely zero.

## Calculating win rate

1. Open Winrate.
2. Enter the TOTAL matches.
3. Enter the **number of wins**, not the WR percentage, in the wins field.
4. Enter the target WR.
5. Press **HITUNG WINRATE** (CALCULATE WINRATE).

Example: 100 matches and 50 wins means a 50% WR. To reach 60% without losing again, you need 25 wins in a row: 75 wins out of 125 matches = 60%.

This calculation doesn't predict the outcome of your next matches and doesn't change your account.

## Ban Check and issues

Enter the UID, then press CEK STATUS BAN (CHECK BAN STATUS). Read the status and the source of the result. If the check fails, the account status is **unknown**; don't assume that failing to fetch data means the account is ban-free.

Stalk FF shows the data the service managed to get, not access to passwords, private inventory, or all of a player's activity. If the account isn't found, check the UID and region before trying again.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/apps/ff-tools/index.html) · [List of all tools](README.md)
