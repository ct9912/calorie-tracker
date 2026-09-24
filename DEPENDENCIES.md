# Third-party dependency record

## Barcode scanner

- Package: @zxing/browser
- Version: 0.2.1
- File: vendor/zxing-browser.min.js
- Source: https://github.com/zxing-js/browser
- Licence: MIT — see vendor/ZXING-LICENSE.txt

## If a security issue is found

1. Check the official ZXing advisory or release notes.
2. Download one specific fixed version from the official source.
3. Replace vendor/zxing-browser.min.js.
4. Update the version above.
5. Increase the cache version in service-worker.js, for example v3 to v4.
6. Test the app locally.
7. Upload the reviewed files to GitHub and test the phone app.