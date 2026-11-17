# BMKG Indonesia

Shows official data from BMKG (Indonesia's Meteorology, Climatology, and Geophysics Agency) for earthquakes, three-day weather forecasts, and early warnings. The three menus have different workflows.

## Gempa (Earthquakes)

1. Choose **Gempa** (Earthquakes).
2. Wait for the latest or felt earthquake data.
3. Read the time, magnitude, depth, location, and any available notes.
4. Check the update time and the BMKG source link.

Magnitude and felt intensity are not the same term. Use the source's explanation when you need to make decisions based on earthquake data.

## Cuaca (Weather): requires an ADM4 code

1. Choose **Cuaca** (Weather).
2. Fill in the **kode wilayah ADM4** (ADM4 area code), the code of a village/urban ward in the format **XX.XX.XX.XXXX**.
3. Press **Lihat prakiraan** (View forecast).
4. Make sure the village/ward name that appears is correct.
5. Read the forecast by time for three days.

The official example shown in the interface: **31.71.03.1001 for Kemayoran**. This is an example for recognizing the format, not automatically where you are.

If you don't know your area code yet, use the **Panduan resmi** (Official guide) available on the form. Typing "Jakarta" or just a city name into the code field doesn't follow the required format.

## Peringatan (Warnings)

1. Choose **Peringatan** (Warnings).
2. Read the list of nowcasts or warnings the feed currently returns.
3. Note the area, time, and description.
4. Open **Detail BMKG** for the source information.

No warnings in the feed when you check is not a guarantee that the weather will always be safe. The data can change, so read the update time.

## Issues and results

The browser may remember the last code to make weather lookups easier. Data may also be cached to reduce requests.

If a code is rejected, check the dot pattern and the number of digits. If the area name in the result is wrong, replace it with the correct code. If the source is unavailable, try again after the service recovers; the tool doesn't make up a substitute forecast.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/features/bmkg-open-data.js) · [List of all tools](README.md)
