# Tm Docs Reader releases

Release files for **Tm Docs Reader**, a free Qlik Sense extension from Tallmaker AS that shows the docs of the Tallmaker extensions installed on your tenant, inside the app.

Each release holds:

- `tmdocsreader-<version>.zip`: the extension. Upload it in the Qlik Cloud management console under Extensions.
- `release-demo-<version>.qvf`: a demo app with a help sheet.
- `release-manifest.json` and one `.sha256` file per asset: checksums.

## Use it

1. Upload the extension zip.
2. Add **Tm Docs Reader** to a sheet. It lists the installed Tallmaker products that ship docs.
3. Set **Product** to lock it to one product, for a help sheet in that product's app.

The reader is free and reads no licence. It is English only. It shows the docs of the installed version of each extension; extensions add their docs at their next release.
