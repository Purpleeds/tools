# E-KTP Generator

Creates a **demo/parody E-KTP image** (Indonesian electronic ID card) from sample data. The result carries a parody watermark and is not an official identity document.

## How to use it

1. Open E-KTP Generator.
2. Replace the **Nama Dummy** (Dummy Name), **NIK Dummy** (Dummy ID Number), and other sample data as needed for the demo.
3. Fill in the province, regency/city, address, and supplementary information if needed.
4. Add a **Foto Demo Opsional** (Optional Demo Photo) if you want the sample to use a photo.
5. Press **Generate E-KTP Demo**.
6. Check the image, then use the download option that appears.

Use made-up data for practice. The NIK (ID number) in the form is sample text placed on the image, not the result of government issuance or identity verification.

## Understanding the fields

**RT/RW, kelurahan/desa, kecamatan, and alamat** (neighborhood unit, village/ward, district, and address) fill in the address section. **Tanggal Terbit** (Issue Date) fills in the location/date text in the sample's issuance section. **Berlaku Hingga** (Valid Until) is also just text on the demo image.

If no photo is chosen or it can't be read, the result may use the default placeholder image. The photo may be cropped to fit the card's photo area.

## Results and issues

The result is a PNG drawn on a canvas in the browser. Changing the fields after Generate doesn't update the old result; press Generate again.

Text that's too long may not fit well in the card area. Shorten the sample data and check the preview before downloading. The parody watermark remains part of the result.

[Audited feature source](https://github.com/akidwush/dika-nexora-ganteng/blob/25172f69c8c68d6c5c0371a16db73301e09740ab/assets/js/core/app.js) · [List of all tools](README.md)
